# Primer Proyecto
![Tinkercad](./img/ArduinoTinkercad.jpg)


## Integrantes 
- Juan Cruz Mendez
- Nicolas Larochi
- Julian Ortiz 
- Lucas Torres
- Joaquin Montiel


## Proyecto: Semaforo.
![Tinkercad](./img/ContadorBinario.png)


## Descripción
Este proyecto consiste en un semaforo de 9 luces led, 3 de cada color. Simula un semaforo
con señalizacion para personas no videntes. Ya que posee un piezo que suena mientras esten
encendidas las luces de color rojas y amarillas, indicando el momento en el que se puede 
cruzar.

## Función principal
Esta funcion enciende y apaga los leds cada cierto rango de tiempo, y controla la frecuencia
de sonido, y los lapsos de tiempo del piezo.

B0, B1, B2, B3 son #define que utilizamos para agregar los leds, asociandolo a pines de la placa arduino.

(Breve explicación de la función)

~~~ C (lenguaje en el que esta escrito)
void EncenderBinario(int estado3, int estado2,int estado1,int estado0)
{
  digitalWrite(B3,estado3);
  digitalWrite(B2,estado2);
  digitalWrite(B1,estado1);
  digitalWrite(B0,estado0);
}
~~~

## :robot: Link al proyecto
- [ProyectoSemaforo](https://www.tinkercad.com/things/bGMXosfeWJt-1g-dojo-uno-larrochi-nicolas-gaston/editel?sharecode=263m2zKwATqCoa8Coq27JEYd2aZZqxgr7D1R8_IoB30)
