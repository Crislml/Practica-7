# Práctica 7
# *CARACTERÍSTICA DE LA ONDA SENOIDAL*
## *PLANTEAMIENTO DEL PROBLEMA*


## *OBJETIVOS*
# Objetivo general
- 

# Objetivos específico
- Comprender la metodología del teorema de la máxima transferencia de potencia para reafirmar los conocimientos previamente adquiridos.
- Encontrar la resistencia aproximada en la cual se obtiene la mayor transferencia de potencia.
- Analizar los resultados teóricos con los prácticos mediante la comparación de los mismos para la obtención de porcentajes de error respectivos.


## *LISTA DE MATERIALES*


| Cantidad | Material de Equipo |
| ------------- | ------------- |
| 1  | Generador de Funciones |
|  1 | Osciloscopio  |
| 1  | Multímetro digital |
|  1 | Resistor de 1k  |
|   1 | Resistor  de 2.2k     |
|  1  | Protoboard      |

Tabla 1. Materiales
## *MARCO TEÓRICO*
El análisis de la señal senoidal, donde quiere decir que en la señal alterna el circuito adquiere dos polaridades (Por donde pasa la corriente) y este circuito es representado:

![alt text(https://github.com/Crislml/Practica-7/blob/master/Imagenes/Circuito%20en%20sentido%20positivo.png)

Fig 1. Circuito en sentido positivo

Este al viajar, va a tomar una segunda dirección, obteniendo dos direcciones distintas, alternando sus polaridades:

![alt text(https://github.com/Crislml/Practica-7/blob/master/Imagenes/Circuito%20en%20sentido%20negativo.png)

Fig 2. Circuito en sentido negativo

Donde gráficamente el signo positivo se refiere a la cresta positiva y el negativo en la cresta negativa consecuentemente. 

Las ondas senoidales tienen un movimiento periódico que tambien se puede decir que es un patrón. estas matemáticamente son modeladas con funciones trigonométricas, entre esas están el seno y coseno, tiene muchas aplicaciones en agulnos fenómenos físicos, pero en específico sobre los voltajes generados por centrales eléctricas y utilizado en hogares.

En los elementos eléctricos como resitencias, condensadores e inductancias, que estan conectadas en dicho voltaje, un ejemplo gráfico de como son estas ondas senoidales.

![alt text(https://github.com/Crislml/Practica-7/blob/master/Imagenes/Onda%20senoidal.png)

Fig 3. Onda Senoidal.

Estas estan denotadas tanto como en seno y coseno, son iguales estas ondas pero con una pequeña diferencia, una esta adelantada de la otra, obteniendo la siguiente relación:
Cos(x)=Sen(x+π/2), aquí veremos gráficamente de como se ven ya desplazadas:

![alt text(https://github.com/Crislml/Practica-7/blob/master/Imagenes/Onda%2C%20seno%20y%20coseno.png)

Fig 4. Onda seno y coseno.

Entonces en términos del volataje, la ecuación es la siguiente:

V(t)=VpSen(wt+θ)

Donde el Vp, es la amplitud máxima que alcanza dicha onda, W su frecuencia angular y θ su desplazamiento, donde se los detallara a continuación:

*El periodo*

Es el tiempo que tarda en repetirse una fase de la misma y esta se mide en segundos.

*Amplitud*

Este valor máximo es justamente la amplitud de la onda, también conocida como amplitud pico.

*Ciclo*

Es una parte de la onda contenida en un período, pero puede comenzar a medirse desde otros puntos de la onda, mientras estén limitados por un período.

*Frecuencia*

La frecuencia es la cantidad inversa del período y está relacionada con la frecuencia angular ω, donde esta tiene como unidades (rad/s).



## *PROCEDIMIENTO*

1.-Arme el circuito que se muestra en la figura.
 
 ![alt text](https://github.com/Kevi7k/Practica6/blob/master/Imagenes/diagrama%204.png)
 
 Fig 5.   Circuito a ser simulado.

2.- Mida el voltaje y la corriente para cada valor de RL que se indica en la fig 5, anote los resultados medidos.

3.- Calcule las potencia consumida por RL, para cada valor dado y anote los resultados en la tabla 2.


## *TABULACIÓN DE DATOS*





## *Ecuaciones*


Donde In vendría ser la intensidad de donde quitamos la resistencia , cumpliendose Ley de Ohm y las unidades son las mismas.

Intensidad=Amperio (A)

Voltaje=Voltio (V)

Resistencia= Ohmio (omega)

Para encontrar las corrientes necesarias para el calculo de voltajes, tanto en el circuito original como en el circuito de Thévenin será necesario hacer uso de las leyes de Kirchoff. De manera que:

V1+V2+V3+V4+...Vn=0

Esta ecuación se cumple siempre y cuando sea de solamente una malla, es decir la sumatoria de voltajes dentro de una malla es igual a cero, afirmando esto, se cumple otra ley que nos habla sobres las corrientes. Es muy útil si para el cálculo realizaramos un análisis nodal

I(salida)=I(entrada)

## *PREGUNTAS*

1.- ¿Se cumple el Teorema de la Máxima Transferencia de Potencia? Argumente su respuesta

El teorema de la máxima transferencia de potencia  estuvo a poco de cumplirse ya que hay dos resistencias muy cercanas a la resistencia de thevenin , pero no iguales por lo que en esta práctica no se pudo comprobar el teorema de la máxima transferencia de potencia. 


## *DIAGRAMA*

![alt text]()

Figura 6. 

## *EXPLICACIÓN DEL CIRCUITO*




## *ANÁLISIS DE RESULTADOS*
En general los resultados de las mediciones nunca serán exactas, a pesar del máximo cuidado que se tenga en el momento de realizar cada una de ellas, no es posible expresar el reultado como exacto, es por esto que a continuación se ralizará una tabla donde se muestre  el error relativo de cada valor obtenido:




## *CONCLUSIONES*



## *RECOMENDACIONES*
1.- Para realizar una práctica exitosa se debe tener conocimiento previo adquirido, principalmente el teorema de Thévenin, para poder relacionar la teoría aprendida con la simulación.

2.- Tener en cuenta que en esta práctica el dato teórico con el que comparamos nuestros resultados es calculado a partir de otras mediciones, a menos que se utilice un simulador de laboratorio que pueda medir potencia.

3.- Tener cuidado al momento de aproximar los valores que calculamos teóricamente ya que si lo hacemos mal , nos dará un porcentaje de error más alto de lo esperado.

4.- Realizar paso a paso la práctica, siguiendo en orden el prodecimiento ya establecido en las guías de laboratorio, para así no cometer errores. 


## *CRONOGRAMA*

![alt text]()

## *BIBLIOGRAFÍA*

Charles K. Alexander, Matthew N. O. Sadiku, Fundamentos de circuitos eléctricos. Tercera edición. México: McGrawHill, 2004.

## *ANEXOS*

![alt text]()

Figura 5. 
