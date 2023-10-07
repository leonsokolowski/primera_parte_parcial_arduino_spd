# Primera parte parcial arduino
![Logo arduino](https://github.com/Estebamq/EjemploDocumentacion/raw/main/img/ArduinoTinkercad.jpg)
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
