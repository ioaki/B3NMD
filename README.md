# B3NMD
#### Creador: ioaki
#

El nombre del proyecto proviene de: "**B**lock **N**um, **B**lock **M**ayus, **B**lock **D**espl". (Teclas en español)
La idea del proyecto es poder enviar mensajes provientes de un archivo dde texto plano .txt, a través de las luces led del teclado. Algo así cómo un método de "comunicación espía".

![Ejemplo de LEDS](/photo_illustration_of_keyboard_LED_indicators.jpg)

#
#### El uso de esta herramienta es simple:
1. Usted debe ubicar el archivo executable en un directorio determinado, (Ejemplo: Escritorio)
2. Debe crear un archivo de texto plano con el nombre de ("msg.txt").
3. Ejecute el archivo inicial.
4. Los LEDs de su teclado deberían comenzar a indicar patrones.

#
#### Sobre los patrones:
* *Determinemos en órden los LED, ABC.*
* *El LED A corresponde a "0".*
* *El LED C corresponde a "1".*



Corresponde la siguiente secuencia:
1. -todos se apagan-
2. Se enciende B, se apaga B. [Secuencia de inicialización
3. Inicia la secuencia de 0's y 1's.

*NOTA:
      Por cada encendido/apagado del LED, luego de la "Secuencia de inicialización", le corresponde un 0 ó un 1, según corresponda. Es           decir, si el LED A, se prende y se apaga, el fragmento de la secuencia es "00"*
#



