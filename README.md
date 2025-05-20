# Poyecto para la asignatura de diseño de equipos electrónicos

Este proyecto consistió en diseñar una PCB tipo "expansion board" para la tarjeta STM32 nucleo, con el objetivo de conectar un motor DC con encoder y un potenciómetro para controlar su posición como servo motor.

El diseño fue realizado en Eagle y se encuentra en la carpeta con ese nombre, consiste en una placa simple de dos capas y con el tamaño necesario para que sus pines se conecten directamente con los pines d el atarjeta nucleo, se envió a PCBway para su fabricación.

Se compraron los componentes SMD por Mouser y se soldaron a la PCB con un horno.

Finalmente de diseñó la lógica en STM32 IDE con un controlador PI y la medición del encoder para controlar la posición del motor DC.