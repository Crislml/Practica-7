# Práctica 7
# *CARACTERÍSTICA DE LA ONDA SENOIDAL*
## *PLANTEAMIENTO DEL PROBLEMA*

Al empezar a trabajar con fuentes de voltaje alterna, sabemos que ésta, está representada por una gráfica en forma de la función seno, por lo cual debemos saber las características de dicha señal, y como funciona la onda que representará el voltaje o corriente que usaremos como fuente. Para ello deberemos tener claro los conceptos sobre la función seno, como también los conceptos de fuentes alternas, y su diferencia con fuentes continuas, como también será importante saber el funcionamiento y como interpretar el osciloscopio.

## *OBJETIVOS*
# Objetivo general
- Determinar con simulaciones las características de las señales senoidales.

# Objetivos específico
- Comprender la importancia sobre las gráficas senoidales en los análisis de los circuitos.
- Analizar el funcionamiento de un osciloscopio en esta práctica.
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

![alt text](https://github.com/Crislml/Practica-7/blob/master/Imagenes/Circuito%20en%20sentido%20positivo.png)

Fig 1. Circuito en sentido positivo

Este al viajar, va a tomar una segunda dirección, obteniendo dos direcciones distintas, alternando sus polaridades:

![alt text](https://github.com/Crislml/Practica-7/blob/master/Imagenes/Circuito%20en%20sentido%20negativo.png)

Fig 2. Circuito en sentido negativo

Donde gráficamente el signo positivo se refiere a la cresta positiva y el negativo en la cresta negativa consecuentemente. 

Las ondas senoidales tienen un movimiento periódico que tambien se puede decir que es un patrón. estas matemáticamente son modeladas con funciones trigonométricas, entre esas están el seno y coseno, tiene muchas aplicaciones en agulnos fenómenos físicos, pero en específico sobre los voltajes generados por centrales eléctricas y utilizado en hogares.

En los elementos eléctricos como resitencias, condensadores e inductancias, que estan conectadas en dicho voltaje, un ejemplo gráfico de como son estas ondas senoidales.

![alt text](https://github.com/Crislml/Practica-7/blob/master/Imagenes/Onda%20senoidal.png)

Fig 3. Onda Senoidal.

Estas estan denotadas tanto como en seno y coseno, son iguales estas ondas pero con una pequeña diferencia, una esta adelantada de la otra, obteniendo la siguiente relación:
Cos(x)=Sen(x+π/2), aquí veremos gráficamente de como se ven ya desplazadas:

![alt text](https://github.com/Crislml/Practica-7/blob/master/Imagenes/Onda%2C%20seno%20y%20coseno.png)

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
 
 ![alt text](https://github.com/Crislml/Practica-7/blob/master/Imagenes/diagrama.png)
 
 Fig 5.   Circuito a ser simulado.

2.-Ajuste el generador de funciones, para que proporcione una señal de 20 Vpp a una frecuencia de 2.5 Khz.

3.-Conecte el osciloscopio al resistor de carga RL. Observe la señal que aparece en el osciloscopio.

## *Ecuaciones*

Las ecuaciones en esta sección serán exclusivamente de la interpretación gráfica senoidal, obteniendo las siguientes formulas:

Frecuencia angular (W)

W=2πf

Frecuencia (f)

f=1/T

Ecuación de la onda:

V(t)=VpSen(wt+θ)

La amplitud vendría a ser el valor pico que alcanza la onda (Vp)

Fase:

Vendría a ser lo que se desplaza la onda en θ y sus unidades (radianes)

Pero si queremos la ecuación en forma de coseno tenemos:

V(t)=VpCos(Wt+θ+π/2).

Ecuación para determinar el voltaje o período a partir del número de divisiones y la escala.

![alt text](https://github.com/Crislml/Practica-7/blob/master/Imagenes/Ecuaci%C3%B3n.png)

## *DIAGRAMA*

![alt text](https://github.com/Crislml/Practica-7/blob/master/Imagenes/Circuito_osciloscopio.png)

Figura 6. Circuito implementado con osciloscopio.

 **EXPLICACIÓN DEL CIRCUITO**



## *PREGUNTAS*

1. **¿Cuántas divisiones por cuadro abarca la amplitud pico de la señal de salida?**

	La amplitud pico abarca aproximadamente 2.3 divisiones por cuadro. De manera que de pico a pico se hay un total de 4.6 divisiones por cuadro.


2. **¿En qué valor está posicionada la perilla VOLTS/DIV?**

	La perilla se ubicó en 3, lo cual nos indica que la escala corresponde a 3 voltios por división.

3. **¿Cuántas divisiones por cuadro abarca un ciclo completo de la señal de salida?**

	Existen 0.8 divisiones en un ciclo que recorre nuestra onda, contando en el eje horizontal, es decir el eje del tiempo.

4. **¿En qué valor está posicionada la perilla TIME/DIV?**

	La perilla se ubicó en 0.5, lo cual nos indica que la escala corresponde a 0.5 milisegundos por cada división.

5. **¿Cuál es la amplitud de voltaje y el periodo de la señal que aparece en la pantalla del osciloscopio?**

-	Amplitud de voltaje: 6.82 V 

-	Período: 0.0004 s

	El período fue determinado a partir de observaciones del osciloscopio. (Véase en anexos)

6. **Determine la frecuencia natural (Hz) y la frecuencia angular (rad/s) de la señal de salida.**

	Aplicamos las fórmulas vistas anteriormente y realizamos el cálculo. (Véase en anexos)
	
	f: 2500 (Hz) 

	ω: 15707.96 (rad/s) 
	
	

7. **Con el multímetro digital mida el voltaje de salida en RL:**

	
	![alt text](https://github.com/Crislml/Practica-7/blob/master/Imagenes/Circuito_mult%C3%ADmetro.png)
	
	Fig. 7. Medición del voltaje en la resistencia RL.
	
	En la resistencia RL se obtiene un voltaje con un valor de 4.865 V.

8. **Compare el voltaje medido en el punto 7.5.5. y el obtenido en el punto 7.5.7. ¿Coinciden?¿Por qué?**

	Estos valores no coinciden porque el voltaje que hemos obtenido del osciloscopio corresponde al Voltaje pico = 6.82 V, mientras que el voltaje que nos da el multímetro 	es el Voltaje rms = 4.865 V. Para que estos valores coincidan tendremos que convertir el Voltaje pico en rms diviéndolo para raíz de 2, con lo que se obtiene un valor de 	 4.8225 V que es un valor aproximado al obtenido en la medición del multímetro.






## *ANÁLISIS DE RESULTADOS*
En general los resultados de las mediciones nunca serán exactas, a pesar del máximo cuidado que se tenga en el momento de realizar cada una de ellas, no es posible expresar el reultado como exacto, es por esto que a continuación se ha realizado el cálculo del error relativo del voltaje obtenido del osciloscopio con respecto al valor resultante de la medición del multímetro de voltaje en la resistencia RL. En nuestro caso consideraremos el resultado del multímetro como el valor teórico.

| V. osciloscopio | V. multímetro |
| ------------- | ------------- |
|4.8225  V | 4.865 V  |

Error relativo = |(Valor teórico - Valor experimental)/ Valor teórico | x 100%

Error relativo = |(4.865 - 4.8225)/ 4.865 | x 100%

Error relativo = 0.87 %



## *CONCLUSIONES*
1.- Al final se pudo comprender como se relaciona estas gráficas senoidales con el voltaje obtenido en el circuito utilizando el osciloscopio.

2.- En el momento de obtener los datos sobre los voltajes, no hay que confundir el  voltaje rms con el voltaje Pico.


## *RECOMENDACIONES*
1.- Para realizar una práctica exitosa se debe tener conocimiento previo adquirido, principalmente entender perfectamente como es una onda senoidal.

2.- Tener cuidado al momento de aproximar los valores que calculamos teóricamente ya que si lo hacemos mal , nos dará un porcentaje de error más alto de lo esperado.

3.- Realizar paso a paso la práctica, siguiendo en orden el prodecimiento ya establecido en las guías de laboratorio, para así no cometer errores. 


## *CRONOGRAMA*

![alt text]()

## *BIBLIOGRAFÍA*

Charles K. Alexander, Matthew N. O. Sadiku, Fundamentos de circuitos eléctricos. Tercera edición. México: McGrawHill, 2004.

Lifeder, Onda senoidal recuperado de https://www.lifeder.com/onda-senoidal/

## *ANEXOS*

![alt text](https://github.com/Crislml/Practica-7/blob/master/Imagenes/Hoja%20de%20c%C3%A1lculos.jpg)

Figura 5.  Calculos de distintos parámetros eléctricos.
