# INFORME TAREA 7

**UNIVERSIDAD DE LAS FUERZAS ARMADAS**

**DEPARTAMENTO DE ELECTRICA Y ELECTRÓNICA**

**FUNDAMENTOS DE CIRCUITOS ELECTRICOS**

**Nombres:** Martin Coronel, Jefferson Chicaiza, Tito Obando 

**Carrera:** Electrónica y Automatización 

**NRC:** 10133

**1. OBJETIVOS**

**2.MARCO TEORICO(RESUMEN)**

**3. EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS**

***CAPITULO N° 13***

El inductor básico
1. Convierta los siguientes valores en milihenries: 
(a) 1 H 		(b)250uH 	(c)10uH 	(d) 0.0005 H

(a) 1H = 1 * 1000 = 1000mH

(b) 250uH = (2.5 * 10^-4) *1000 = 0.25mH

(c) 10uH = 10^-5 * 1000 = 0.01mH

(d) 0.0005H = 0.0005 * 1000 = 0.5mH

3. ¿Cuál es el voltaje en una bobina cuando di/dt = 10 mA/us y L = 5 mH?

V = L(di/dt)

5mH = 5 * 10^-3 H

10mA/us = 10,000A/s

V = (5 * 10^-3) * 10,000

V = 50mV

5. La corriente a través de una bobina de 100 mH cambia a razón de 200 mA/s. ¿Cuánto voltaje se induce en la bobina?

V = L(di/dt)

100mH = 100 * 10^-3 H

200mA/s = 2 *10^-1 A/s

V = (100 * 10^-3)( 2 *10^-1)

V = 0.02 V = 20 mV

7. ¿Qué cantidad de energía se guarda en un inductor de 4,7 mH cuando la corriente es de 20 mA?

W = ½ LI^2

W = ½ (4.7 * 10^-3)(20 * 10^-3)^2

W = 9.4 * 10^-7 J = 0.94 uJ

9. Compare la inductancia de dos inductores idénticos excepto que el inductor 2 está enrollado sobre un núcleo de hierro (permeabilidad relativa = 150) y el inductor 1 está enrollado sobre un núcleo de acero al bajo carbono (permeabilidad relativa = 200)

Inductor 1: enrollado sobre núcleo de hierro, permeabilidad relativa de 150

Inductor 2: enrollado sobre núcleo de acero al bajo carbono, permeabilidad relativa de 200

-	El inductor 2 tiene tres cuartos de la inductancia del inductor 1.

Inductores en serie y en paralelo

11. Se conectan cinco inductores en serie. El valor más bajo es de 5 mH. Si el valor de cada inductor es el doble del valor precedente, y si los inductores se conectan en orden de valores ascendentes, ¿cuál es la inductancia total?

5 Inductores:

L1 = 5mH

L2 = 10mH

L3 = 20mH

L4 = 40mH

L5 = 80mH

LT = 5 + 10 + 20 + 40 + 80

LT = 155mH

13. Determine la inductancia total en la figura.

![image](https://user-images.githubusercontent.com/94182617/153255820-4c133f1b-96ba-4eab-a706-f816400120fb.png)

LT = 50 + 0.5 + 0.01

LT = 50.51mH

15. Determine la inductancia total en paralelo para las siguientes bobinas dispuestas en paralelo: 75 mH, 50 mH, 25 mH, y 15 mH.

LT = 1/(1/L1 + 1/L2 + 1/L3 + 1/L4)

LT = 1/(1/75 + 1/50 + 1/25 + 1/15)

LT = 7.14uH

17. Determine la inductancia total de cada circuito mostrado en la figura.

![image](https://user-images.githubusercontent.com/94182617/153255879-2b1e774f-d70d-49c9-80ef-18dd53a488dc.png)

(a) 

LT = L2||L3 + L1
LT = (10)(5)/(10 + 5) + 1
LT = 4.33H

(b)

LT = L2+L3||L1
LT = 100/2
LT = 50mH

(c)

LT = L1||L2||L3
LT = 1/(1/100 + 1/200 + 1/400)
LT = 57.1uH

Inductores en circuitos de cd
19. Determine la constante de tiempo para cada una de las siguientes combinaciones RL dispuestas en serie:

(a)R=100ohm, L=100uH		(b)R=4.7kohm, L=10mH		(c)R=1.5Mohm, L=3H

t = L/R

(a)

t = (1 * 10^-4)/(100)
t = 0.000001 s = 1us

(b) 

t = (0.01)/(4700)
t = 2.13 * 10^-6 = 2.13 us

(c)

t = (3)/(1,500,000)
t = 2 * 10^-6 = 2us

21. En el circuito de la figura, al inicio no hay corriente. Determine el voltaje en el inductor en los siguientes instantes tras de que se cierra el interruptor: 

(a)10us		 (b)20us	 (c)30us		 (d)40us	 (e)50us 

![image](https://user-images.githubusercontent.com/94182617/153255946-f639fb04-99a2-4e11-b303-52aba35ea8a5.png)

T = L/R
T = 10mH/1kohm
T = 10s

If = Vs/R
If = 15V/1kohm
If = 15mA

iL = If(1-e^-Rt/L)

(a)
iL = 15mA(1-0.37) = 9.45mA

(b)
iL = 15mA(1-0.14) = 12.9mA

(c)
iL = 15mA(1-0.05) = 14.25mA

(d)
iL = 15mA(1-0.018) = 14.73mA

(e)
iL = 15mA(1-0.007) = 14.9mA


23.Repita el problema 21 para los siguientes instantes:

Determine el voltaje en el inductor en los siguientes instantes tras de que se cierra el interruptor:

![image](https://user-images.githubusercontent.com/94098157/152918065-8978a3ec-ff3d-49f6-b726-4eb13f56963a.png)

a) 2µs
b) 5µs
c) 15µs


25. En la figura 13-48, ¿en qué momento luego de que se cierra el interruptor el voltaje llega a 5 V?

27.Determine la constante de tiempo para el circuito de la figura 13-50.

![image](https://user-images.githubusercontent.com/94098157/152901430-7d7f8cf0-03fe-422d-9c97-5b5d40513489.png)

29.Para el circuito de la figura 13-50, suponga que el interruptor estuvo cerrado por más de 5τ y se abre.¿Cuál es la corriente en el inductor 1.0 ms después de que se abre el interruptor?

![image](https://user-images.githubusercontent.com/94098157/152901430-7d7f8cf0-03fe-422d-9c97-5b5d40513489.png)

31.Determine la reactancia total para cada circuito de la figura 13-47 cuando se aplica voltaje a una frecuencia
de 400 Hz.
![image](https://user-images.githubusercontent.com/94098157/152903825-51e31f24-8907-4ea5-a141-2b83879448bc.png)
![image](https://user-images.githubusercontent.com/94098157/152906026-24a0bf02-aab4-4ba6-a454-450de3de06f7.png)
![image](https://user-images.githubusercontent.com/94098157/152906520-f0916dce-4fba-4283-b2f8-66f0591fd698.png)
![image](https://user-images.githubusercontent.com/94098157/152906539-7b73bfc3-c5d0-4fa3-9b1d-b8ce7a8a0e20.png)

![image](https://user-images.githubusercontent.com/94098157/152906624-6d332b84-4a32-4a3c-a2d5-7508de7e0bdf.png)
![image](https://user-images.githubusercontent.com/94098157/152909596-5af3fa1c-9033-4fc2-ab63-c9d20c0ebaa9.png)

33.¿Qué frecuencia producirá una corriente rms total de 500 mA en cada circuito de la figura 13-47 con
un voltaje de entrada rms de 10 V?

![image](https://user-images.githubusercontent.com/94098157/152911986-d7408bad-768f-4474-9171-a85e6287436d.png)

![image](https://user-images.githubusercontent.com/94098157/152903825-51e31f24-8907-4ea5-a141-2b83879448bc.png)
![image](https://user-images.githubusercontent.com/94098157/152912798-710575d8-9ab9-4cba-bde1-c9db4a045dc4.png)

![image](https://user-images.githubusercontent.com/94098157/152906520-f0916dce-4fba-4283-b2f8-66f0591fd698.png)
![image](https://user-images.githubusercontent.com/94098157/152912846-59e4304f-88b7-4571-987a-fb996d52722d.png)

![image](https://user-images.githubusercontent.com/94098157/152906624-6d332b84-4a32-4a3c-a2d5-7508de7e0bdf.png)
![image](https://user-images.githubusercontent.com/94098157/152913041-d598907a-de32-43b1-9e65-4ad0d65bad23.png)

35.Determine IL2 en la figura 13-52.

![image](https://user-images.githubusercontent.com/94098157/152913834-7039b89d-8c05-4317-a881-75f00272e3a9.png)
![image](https://user-images.githubusercontent.com/94098157/152916975-251a2fd6-6c69-4241-96a8-8d3b981ca58f.png)

***CAPITULO N° 14***

1.¿Cuál es la inductancia mutua cuando k = 0,75 , L1 =1 µH, y L2 = 4 µH?

![image](https://user-images.githubusercontent.com/94098157/152922036-fa646834-0268-4bd5-8ee8-507878b8641d.png)

3.¿Cuál es la relación de vueltas de un transformador con 250 vueltas en el primario y 1000 en el secundario? ¿Cuál es la relación de vueltas cuando el devanado primario tiene 400 vueltas y el secundario 100?

![image](https://user-images.githubusercontent.com/94098157/152922853-a7066de2-6c3b-4d17-be45-32dd80f3062f.png)

5.Para cada transformador de la figura 14-42, trace el voltaje secundario que muestre su relación con el
voltaje primario. Indique también la amplitud.

![image](https://user-images.githubusercontent.com/94098157/152923103-0bfcf915-9528-44ea-881c-d55686973950.png)

![image](https://user-images.githubusercontent.com/94098157/152925334-f1684640-150a-41b5-91a8-81f1001b8f4a.png)

7.El devanado primario de un transformador tiene 120 V de ca a través de él. ¿Cuál es el voltaje secundario si la relación de vueltas es de 5?

![image](https://user-images.githubusercontent.com/94098157/152923860-e3f5ad3e-9cdd-4704-a60c-83d7ee252db3.png)

9.Para reducir 120 V a 30 V, ¿cuál debe ser la relación de vueltas?

![image](https://user-images.githubusercontent.com/94098157/152924404-1c79c307-275d-4591-b2da-3021e2d1a249.png)

Jefferson (12 ultimos)

**3.VIDEO**

**4.CONCLUSIONES**

**5.BIBLIOGRAFÍA**
