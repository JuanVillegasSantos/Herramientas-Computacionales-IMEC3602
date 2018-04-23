# Enunciado

El proyecto para este curso se propone sea el de escribir un programa que permita corregir la velocidad angular en RPM adquirida de la señal de PWM de una hélice  a partir de la señal de voltaje generada por un sensor óptico tipo laser que apunta a una de las aspas de esta hélice en partícular.

El programa debe adqirir automáticamente los archivo de texto resultantes de cada medición (Habrá mínimo 3 mediciones con sus respectivos archivos en cada carpeta) conteniendo los datos de Empuje, Torque, Velocidad angular PWM y señal de voltaje contra tiepo del sensor optico. El programa debe arrojar las gráficas de Empuje vs RPM, Torque vs RPM y Potencia Mecánica vs RPM con susrespectivas tendencias y sus barras de errores asociados. (Se debe tener cuidado con la temporalidad de cada archivo, cada uno de estos contiene un registro del tiempo que registra el computador al guardar cada dato y este se usará como criterio para determinar la temporalidad del análisis)

Adicional a esto, se debe realizar un ajuste a la curva de Potencia vs RPM, asumiendo 2 tipos de curvas de ajuste:

* P=C$\omega^k$

para realizar el ajuste de de velocidad angular necesario y calcular sus respectivos indicadores de error, se propone comparar 3 indicadores: 

* Error RMS
* Error de Sesgo medio
* Indice de Kolmogorov Smagorinski

Finalmente se requiere analizar cual es el método más eficaz para realizar el ajuste propuesto

## Acerca del sensor:

El sensor a trabajar es un sensor óptico Omron modelo E3FB-TN11-L el cual es de tipo laser para su medición, con un alcance máximo de 20m. A continuación se muestra como está el montaje de este sensor para la medición de velocidad angular:
<img src="https://github.com/JuanVillegasSantos/Herramientas-Computacionales-IMEC3602/blob/master/Proyecto/Sensor.png" width="500">

