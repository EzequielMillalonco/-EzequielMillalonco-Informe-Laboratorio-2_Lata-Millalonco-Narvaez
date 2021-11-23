# Informe-Laboratorio-2

## 1. OBJETIVOS
 
	General: 

Comprobar experimentalmente el Análisis de Mallas.
        
	Específicos: 

a. Entender el funcionamiento de las mallas en los circuitos elecctricos mediante su aplicacion y analisis experimentral y simulado.

b. Aplicar los conocimientos teóricos que se tiene sobre el analisis de mallas utilizando la Ley de Voltajes de Kirchhoff, esto con el proposito de entender sus 2 metodos de analisis: Metodo de las corrientes de mallas y metodo de las corrientes de rama.

c. Construir un circuito eléctrico de manera experimental y simulado con el fin de identificar sus partes básicas y realizar cálculos teoricos, experiméntales y simulados para expresar voltajes en funcion de corrientes.

## 2. MARCO TEÓRICO

El método de la corriente de malla es otro método bien organizado para resolver circuitos (el otro es el del voltaje en los nodos). Al igual que en cualquier análisis de circuito, tenemos que resolver un sistema de 2E2E2, E ecuaciones independientes, donde EEE es el número de elementos del circuito. El método de la corriente de malla facilita el análisis, y produce un número relativamente pequeño de ecuaciones a resolver. El método de la corriente de malla se basa en la ley de voltaje de Kirchhoff (LVK).

![Screenshot 2021-11-22 202012](https://user-images.githubusercontent.com/93826527/142958250-6a3e6eff-5d82-48c0-a40e-6956fb42373d.png)

El método de la corriente de malla utiliza dos términos especiales: lazo y malla.

Un lazo es cualquier trayectoria cerrada alrededor de un circuito. Para formar un lazo, debes comenzar en la terminal de algún componente y trazar un camino a través de elementos conectados hasta llegar nuevamente al punto de partida. Un lazo solo puede pasar por un elemento una vez (de tal forma que no obtengas lazos que parezcan el número 8). En el circuito de arriba hay tres lazos: dos representados con una línea continua y otro con una línea punteada.

**Una malla es una clase restringida de lazo; una malla es un lazo que no contiene otros lazos, el lazo punteado no es una malla, pues contiene dos lazos distintos.**

![Blank diagram (3)](https://user-images.githubusercontent.com/93826527/142958704-42b687b4-f30c-4307-b342-6734275d7551.png)

![Screenshot 2021-11-22 202727](https://user-images.githubusercontent.com/93826527/142958750-f2396ed8-4603-4c0e-a38a-0db76b003a69.png)


## 3. EXPLICACIÓN DEL PROCEDIMIENTO

2.5.1 Implemente el circuito que se presenta en la figura 2.1.

![image](https://user-images.githubusercontent.com/93396250/142574532-470a83f0-8b53-47b6-b9be-ee7c354d538b.png)

Implementación del circuito: 



2.5.2 Primera parte: Mida cada una de las corrientes de malla

	-18+I1R1+R4(I1-I2)=0

	1820I1-1000I2=18	ECUACIÓN 1

	I2R2+R5(I2-I3)+R4(I2-I1)=0

	-2200I3+4400I2-1000I1=0		ECUACIÓN 2

	I3R3+5+R5(I3-I2)=0

	2590I3-2200I2=-5	ECUACIÓN 3

	**RESOLVEMOS EL SISTEMA DE 3 ECUACIONES CON 3 INCÓGNITAS, 
	POR CUALQUIER MÉTODO, EN ESTE CASO TRABAJAREMOS CON ELIMINACIÓN DE GAUSS-JORDAN**

	I1= 11.45 mA

	I2= 2.84 mA

	I3= 488.12 μA

2.5.3 Primera parte: Simule en el software Multisim, Proteus, o cualquier otro simulador, el circuito de la figura 2.1, obteniendo los valores de las corrientes de malla.

	Circuito 2.1 simulado en Multisim

![Malla sin caminos dibujados](https://user-images.githubusercontent.com/93396250/142806171-7c315ae9-3e42-40e9-950c-805c172b70a5.JPG)

Mallas del circuito:

![Mallas](https://user-images.githubusercontent.com/93396250/142805873-d15fc757-1fdb-4eb7-84b2-d750f297fcbf.JPG)

	Malla 1:

![image](https://user-images.githubusercontent.com/93396250/142909685-bc4c2510-9f47-4d46-86c9-283376edc608.png)


	Malla 2:

![image](https://user-images.githubusercontent.com/93396250/142909884-c2a871a0-7e09-416b-aa57-da001b5fc0d8.png)


	Malla 3:

![image](https://user-images.githubusercontent.com/93396250/142910035-43ca2c3d-c486-481a-a41e-c89b8c17344b.png)



## 4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

        2.5.2. Segunda parte: Mida cada una de las corrientes de malla y anote los resultados en la tabla 2.1.

        2.5.3. Segunda parte: Anote los resultados en la tabla 2.1

        2.5.4. Compare los valores de la tabla 2.1 y realice sus conclusiones.
        
![Screenshot 2021-11-22 213959](https://user-images.githubusercontent.com/93826527/142963670-8945d966-2016-4ce8-b052-6e44bca72cd2.png)

        
	
**Se aplica la formula del error porcentual para calcular cual fue el error entre las medidas, siendo el error porcentual aceptable del 5%**

![image](https://user-images.githubusercontent.com/93396250/141480859-765210f6-609f-4c8b-9ad1-4f4543fa9817.png)

La tabla 2.1 tiene un error porcentual menor al 5% aceptable, siendo estos en los cálculos y experimentación:

	Malla 1 tiene un error del 0.43%

	Malla 2 tiene un error del 0.35%

	Malla 3 tiene un error del 0.02%
        
Conclusiones: 

Por tanto, se concluye que el presente laboratorio fue exitoso ya que se pudo demostrar experimentalmente que la suma de corrientes dentro de una malla es igual a cero y que una malla es una clase restringida de lazo; una malla es un lazo que no contiene otros lazos.
## 5. VIDEO

        Link del video ¨Informe de laboratorio 2¨ en donde se comprueba experimentalmente el Análisis de Mallas.
        

	
	
[![Presentación Tarea 2](https://img.youtube.com/vi/QaQNKTvchSc/0.jpg)](https://www.youtube.com/watch?v=QaQNKTvchSc)

## 6. CONCLUSIONES

a. El funcionamiento de las mallas en los circuitos electricos fue entendido de manera exitosa garcias a su aplicacion y analisis experimental y simulado.

b. Los conocimeintos teoricos del analisis de mallas utilizando la Ley de Voltajes de Kirchhoff y sus 2 metodos de analisis fueron aplicados correctamente a lo largo del laboratorio.

c. Los calculos teoricos, experimentales y simulados resultaron ser correctos, ya que cada uno de estos fue comprobado (mediante la construccion de un circuito) y comparado para tener el menor margen de error posible.

## 7. BIBLIOGRAFÍA

Alulema Darwin. Guías Primer Parcial https://classroom.google.com/u/0/w/NDEyOTg4NDk2MDQx/t/all?hl=es
