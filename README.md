# Atomik robo-car
*Para mi niño interior....*

## La idea.... 
... es armar un vehículo motorizado que se pueda conducir con algún control externo.

El móvil contará con dos ruedas delanteras con tracción independiente, es decir, un motor impulsará cada una de las ruedas. En la parte de atrás habrá una rueda libre, que sirve de apoyo y puede moverse según el sentido que el vehículo tome.

Cada rueda independiente puede moverse hacia adelante, hacia atrás, o permanecer detenida. De esta forma, se definen los siguientes movimientos posibles del coche:

Rueda Izquierda | Rueda Derecha | Efecto
----------------|---------------|-------
Adelante | Adelante | Adelante línea recta
Adelante | Detenida | Gira derecha lentamente
Adelante | Atrás | Gira derecha rápidamente
Detenida | Adelante | Gira izquierda letnamente
Detenida | Atrás    | Gira derecha lentamente
Atrás | Adelante | Gira izquierda rápidamente
Atrás | Detenida | Gira izquierda lentamente
Atrás | Atrás | Atrás en línea recta

## Adicionales

Además de moverse, el vehículo contará con:

* Un rastreador de línea, que permite que el coche siga automáticamente un trazo oscuro sobre el piso.
* Un sensor de distancia ultrasónico, que permite que el coche detecte obstáculos y tome alguna acción. El sensor estará montado sobre un soporte con dos grados de libertad: izquierda y derecha, arriba y abajo.
* Un receptor Bluetooth, que permite el control a distancia desde una pc, tableta, o celular.

## Lista de Materiales

1. Arduino Duemilanove. Basado en ATMel328P.
1. Driver de motores L298. 
1. 2x Motores DC, con caja de engranaje y ruedas de goma.
1. 2x Servo Motores SG-90
1. 1x receptor bluetooth HC-05 (o HC-06)
1. 2x Baterias 18650, 4000mAh, 3.7V
1. Chassis de acrílico.
