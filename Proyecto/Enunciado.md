# Enunciado

El proyecto para este curso se propone sea el de escribir un programa que permita calcular la velocidad angular en RPM de una hélice  a partir de la señal de voltaje generada por un sensor óptico tipo laser que apunta a una de las aspas de esta hélice en partícular.

En resumen, el programa a construir debe simular un encoder.

## Acerca del sensor:

El sensor a trabajar es un sensor óptico Omron modelo E3FB-TN11-L el cual es de tipo laser para su medición, con un alcance máximo de 20m. A continuación se muestra como está el montaje de este sensor para la medición de velocidad angular:
![Sensor](https://github.com/JuanVillegasSantos/Herramientas-Computacionales-IMEC3602/blob/master/Proyecto/Sensor.png)

Con fines ilustrativos solamente, a continuación se presenta el diagrama de conexión del sensor óptico. La adquisición de los datos se realiza mediante el software LabView.
![Sensor](https://github.com/JuanVillegasSantos/Herramientas-Computacionales-IMEC3602/blob/master/Proyecto/diag.Conexion.jpeg)

## Parámetros:

Al programa propuesto le deben ingresar como parámetro la señal de voltaje vs tiempo generada por el sensor descrito. esta señal tiene el siguiente comportamiento:
![Sensor](https://github.com/JuanVillegasSantos/Herramientas-Computacionales-IMEC3602/blob/master/Proyecto/diag.Conexion.jpeg)
