# Simón dice

# Integrantes del proyecto

* Diego Recalde.
* Juan Pablo Rendicz.
* Mauro Benegas.
* Santino Machado.
* Sebastián Pérez Cafferata.

# Componentes

Para este Simón dice requeriremos de:
+ 1 placa arduino uno, 
+ 1 protoboard,
+ 4 leds (1 led rojo, 1 led verde, 1 led azul y 1 led amarillo), 
+ 4 botones, 
+ 1 buzzer,
+ 5 resistencias 1 kΩ,
+ 4 resistencias 220 Ω.

# Explicación del juego

El juego de simón dice consiste de 4 leds que se encienden en una secuencia aleatoria (cada led emite un sonido diferente cuando se enciende), y el jugador tiene que repetir esa secuencia apretando los botones correspondientes a cada led (cada botón emite el mismo sonido que su led correspondiente).<br>
<br>
A medida que se avanza en el juego este se va complicando, puesto que el delay existente entre el encendido de un led y otro disminuye y, a su vez, aumenta la secuencia. Esto sucede cada 1 nivel completado correctamente, es decir que en cada secuencia repetida por el jugador, esta aumenta de velocidad, pero si el jugador se equivoca el juego se reinicia, lo que implica que la velocidad de las secuencias vuelve a su valor base. En general, el juego consistirá de 100 niveles, empezando en el nivel 1 donde tan solo se enciende 1 led.<br>
* Nivel 1 → secuencia de leds: 1
* Nivel 2 → secuencia de leds: 2
* Nivel 3 → secuencia de leds: 3
* Nivel 4 → secuencia de leds: 4
* Nivel 5 → secuencia de leds: 5<br>
…
<br>
<br>
El simón dice cuenta de una secuencia de leds para indicar que comienza el juego<br>
*Insertar gif de esa secuencia*"<br>
	Y otra secuencia para indicar que hubo un error<br>
*Insertar gif de esa secuencia*"<br>