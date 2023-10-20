![Logo arduino](https://github.com/Estebamq/EjemploDocumentacion/raw/main/img/ArduinoTinkercad.jpg)
# Primera parte parcial arduino
## Integrantes:
* León Sokolowski

* Marcelo Villalba

* Matías Zunini

## 💾Proyecto Tinkercad:
![Imagen](https://cdn.discordapp.com/attachments/1135765368091189298/1159964003162935358/tpspd.png?ex=6532efa9&is=65207aa9&hm=d0b18653ef4ef5333b13d4cf7e5a91f286fb476931c05d7cf8644e5762f41a53&)

## [Contador de 0 a 99 con Display 7 Segmentos 👌](https://www.tinkercad.com/things/gtrNZ25SJ6C-stunning-snicket-bruticus/editel?sharecode=ngabwr7mSPKAcHE1rzQirIVSepD4qL_jp-wnj3otTP0 "Nuestro Proyecto😊")

## Descripción:
Esta placa *Arduino* está programada para mostrar, mediante 2 displays de 7 segmentos y el método de multiplexación, un **contador de 00 a 99**. Para modificar el contador cuenta con **3 pulsadores**, uno para sumar 1 dígito, otro para restar 1 dígito y un tercero para volver al contador a 00.

### Funciones:
#### » printDigit:
>Recibe el numero que se deberia mostrar en pantalla. Apaga todos los Led's, y prende los necesarios para c/N°. No devuelve nada

#### » prendeDigito:
>Recibe el numero que se deberia mostrar en pantalla. Apaga los display, y prende con el numero en su valor posicional. No devuelve nada

#### » printCount:
>Recibe un numero. Lo transforma a unidad o decena. No devuelve nada

#### » KeyPressed:
>No recibe nada. Evalua cual boton fue pulsado y que mantener apretado el botón no sume o reste reiteradas veces. Devuelve una respuesta dependiendo el boton

## » Fuente:

[SPD clase 4](https://www.youtube.com/watch?v=_Ry7mtURGDE&list=PL7LaR6_A2-E11BQXtypHMgWrSR-XOCeyD&index=5&ab_channel=UTNFRA)

# Segunda parte parcial arduino
![Imagen](https://media.discordapp.net/attachments/1134581114934136892/1165000832572461086/image.png?ex=65454293&is=6532cd93&hm=09f5db58ab97c8bd8afdf788db63389c3f5272ecf14b6b0e28896eb71f888717&=&width=862&height=449)

## [Punto 1. Interruptor Deslizante elige entre Contador de 0 a 99 y Números Primos 👌](https://www.tinkercad.com/things/bqtRvhsIdk0-parcial-spd-parte-2/editel?sharecode=w9nvc2ZHukHZodwYwDCbXnDpT-iWCn7dYNIy1Y0lOzA "Nuestro Proyecto😊")

## Descripción
Esta placa *Arduino* está programada para mostrar o bien, un **contador de 00 a 99**, o un **contador de número primos**. Para realizar esta tarea se vale de un **Interruptor Deslizante**. Para modificar los contadores cuenta con **3 pulsadores**, uno para sumar, otro para restar y un tercero para volver al contador a 00.

### Funciones:
#### » esPrimo:
>Recibe el numero que se quiere comprobar si es primo. Comprueba que no sea 1 y empieza a dividir por todos los numeros anteriores al elegido en cuestión menos el 1 y el elegido. Devuelve True si el número es primo, devuelve False si no lo es.

#### » obtenerNumeroPrimoSiguiente:
>Recibe el número. Utiliza la función esPrimo para comprobar si el numero es primo o no. Si no lo es, suma un dígito hasta encontrar alguno. Devuelve el número encontrado.

#### » obtenerNumeroPrimoAnterior:
>Recibe el número. Utiliza la función esPrimo para comprobar si el numero es primo o no. Si no lo es, resta un dígito hasta encontrar alguno. Devuelve el número encontrado.

## Punto 2. Motor de corriente continua.
![Imagen](https://media.discordapp.net/attachments/1134581114934136892/1165010205193539685/image.png?ex=65454b4d&is=6532d64d&hm=3b225e461089f9181603b6f00a2e52adc3d4097fb4546943f3e0193dc08c0f53&=&width=1423&height=676)

>El motor de CC (corriente continua), tiene la capacidad de generar energía mecánica de manera giratoria, gracias a una energía eléctrica. nosotros implementaríamos el motor de una manera que este tenga diferente dirección dependiendo un segundo switch haciendo que cambie la dirección en la que rota este, con los botones aumentaríamos o disminuiríamos la velocidad del motor,  la misma estaría dividida de una manera sencilla: (0-9) 10%, (10-19) 20%, etc... , con el display de 7 segmentos veríamos cual seria la velocidad actual.
