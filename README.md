# Mouse Jiggler USV

STM32F103C8T6 - Only emulate usb

### Para movimento randomico use:
```C
srand() // Para fazer o seed
```
e dentro da função de interrupção:

```C
rand() //inteiro que varia entre 0 a 255
```


### Contador de tempo do movimento
```C
intervaloSeg = 2; //a cada 2 segundos move o mouse
```
