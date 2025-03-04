# Artificial Intelligence Notes  

> [!NOTE] 
> These are my personal notes and not an official assignment. They only reflect my study process for different tests throughout the course.  


These notes summarize concepts, problem-solving algorithms and perspectives I gathered throught the semester. 
They serve as a structured reference to understand fundamental AI topics to consolidate knowledge in a clear and practical way for future reference.  

# Index  
1. **Introduction to Artificial Intelligence**  
2. **Search Algorithms**

# Introduction to Artificial Intelligence 

## Conceptos generales

El campo de la IA se enfoca en el entendimiento y construcción de **entidades inteligentes**.

### Diferentes **niveles** de IA.

- Inteligencia débil (soluciones de propósito específico).
Estos sistemas son capaces de resolver problemas de un contexto o dominio específico.
Estos se pueden combinar con otros sistemas para asemejar un nivel de inteligencia
mayor.

- Inteligencia general (soluciones humanas).
Este tipo de inteligencia es más parecida a la inteligencia humana. En dónde se es capaz
de aprender de experiencias previas para aplicarlas de un problema a otro.

- Superinteligencia (ficción).
Más cercano al tipo de inteligencia absoluta ilustrada mayormente en producción ficticias.

### Prueba de Alan Turing
En 1950 se propuso una prueba para responder a "¿Una máquina puede pensar?” 

La prueba se basa en un interrogador humano realiza preguntas a dos individuos y al analizar respuestas no puede determinar si se trata de una máquina o no.

Capacidades de la máquina:
- Procesamiento de lenguaje natural. Saber comunicarse.
- Representación de conocimiento. Saber retener lo que sabe o percibe.
- Razonamiento automatizado. Responder preguntas o determinar nuevas conclusiones.
- Aprendizaje automático. Adaptarse a nuevas circunstancias y extrapolar patrones.

La prueba total de Turing debe incluir además la capacidad de interactúar con objetos y personas del mundo real:

- Visión computacional y reconocimiento de voz, para percibir el mundo.
- Robótica. Manipular y moverse.

> [!NOTE] 
> Estas capacidades componen gran parte de lo que es IA hasta la fecha actual.

### Qué problemas resuelve la IA?

Los algoritmos de IA no pueden resolver cualquier problema. Son parte de un contexto y un objetivo que se desea alcanzar. Apartir de esto se pueden
definir distintos paradigmas. 

----

- Problemas de búsqueda. Problemas con varias posibles soluciones.  
- Problemas optimización. Muchas soluciones válidas pero la solución óptima es la más difícil de encontrar.
- Problemas de predicción. Encontrar y usar patrones de datos para predecir comportamiento o estructura.
- Problemas de clasificación. Encontrar patrones para clasificar conjuntos de datos.
- Problemas de clustering. Agrupación de datos por similitud de atributos o elementos.

### Espacios de búsqueda. 
Es el conjunto de todos los posibles estados de un sistema. Mayormente por limitaciones computacionales, no siempre se pueden calcular todos los estados. 
- 🔹Todos los posibles movimientos en un tablero de ajedrez o todos los posibles movimientos en un juego de gato.

### Algoritmos de búsqueda. 
Se evalúan futuros estados y se intenta encontrar la solución óptima al problema. Provee una forma inteligente de evaluar espacios de búsqueda.
- 🔹 Utilizados en motores de búsqueda, aplicaciones de geolocalización y videojuegos.

### Algoritmos inspirados en biología
Entre estos están:
- Algoritmos evolutivos o genéticos. Por ejemplo, las evoluciones en Flappy Bird con diferentes generaciones.
- Algoritmos “swarm”. Por ejemplo, el algoritmo de enjambre de partículas. Permite optimizar un problema a partir de soluciones
candidatas.

### Algoritmos de aprendizaje automático (Machine Learning)
Estos algoritmos hacen uso de un enfoque estadístico para el procesamiento de datos. Estos
se pueden clasificar en:
- Aprendizaje supervisado.
- Aprendizaje no supervisado.
- Aprendizaje reforzado.

### Algoritmos de aprendizaje profundo (Deep Learning)
Este se deriva del aprendizaje automático. Son utilizados para alcanzar la inteligencia débil y esforzarse por alcanzar la inteligencia general.
Enfocado en problemas de ámbito general y de igual forma tiene enfoques de aprendizaje supervisado, no supervisado y reforzado.
Hace uso de varias capas de redes neuronales, cada capa funciona como un componente inteligente que resuelve un problema específico/especializado.

### Algunas aplicaciones de la IA
- Detección de fraude en sistemas bancarios.
- Ciberseguridad. Detección de ataques potenciales a servidores, comportamiento inusual de transacciones, bloqueo de tráfico malicioso (DDoS), etc.
- Diagnósticos médicos.
- Telecomunicaciones.
- Agentes de IA en juegos.

## Historia de la IA
### Incepción de la IA (1943-1956)
Se propuso un modelo de “neuronas artificiales”. Estas neuronas podían tener un espacio de encendido o apagado.

Se demostró que cualquier función computable podría ser construida haciendo uso de neuronas interconectadas mediante conectivas lógicas (AND, OR, NOT, etc.).

En 1950 se construyó la primera red neuronal computacional (The SNARC).

En el artículo Computing Machinery and Intelligence, Alan Turing introdujo el Turing Test, aprendizaje automático, algoritmos genéticos y aprendizaje reforzado.

### La era del entusiasmo (1952-1969)
Se dieron hallazgos importantes en el campo de la IA, algunos de ellos son:
- General Problem Solver (GPS). Primer intento de imitar el raciocinio general humano.
- Geometry Theorem Prover. Programa capaz de probar teoremas matemáticos complejos.
- Juego de damas con IA. Primeros acercamientos de aprendizaje reforzado.
- Lenguaje de programación LISP. Lenguaje de alto nivel que predominó el campo de IA durante los siguientes 30 años.

### Sistemas expertos (1969-1986)
Los primeros años de IA, la resolución de problemas estaba basado en ámbitos de propósito general. Estos métodos se llamaban métodos débiles debido a que, a pesar de ser generales, las soluciones no pueden escalar a instancias más complejas o grandes del problema.

El enfoque pasó completamente al diseño de sistemas expertos, en lugar de abarcar una amplia generalidad de problemas. Se enfocaron los sistemas en ámbitos más específicos.

La idea principal era simular los conocimientos de los expertos en distintos ámbitos (medicina, economía, etc.).

### Retorno de las redes neuronales (1986-Actualidad)
En la década de 1980, se redescubrió el algoritmo de retro propagación, aplicado a problemas de aprendizaje en ciencias de la computación y psicología.

Estos modelos “conexionistas” fueron vistos como competidores de los enfoques simbólicos y lógicos de la IA.

Los modelos de conexionistas ofrecen una forma más fluida e imprecisa de procesar y desarrollar conceptos en el mundo real.

Los modelos de conexionistas tienen la capacidad de aprender de ejemplos y ajustar sus parámetros para mejorar su rendimiento en futuros casos.

### Probabilidades y aprendizaje automático (1987-Actualidad)
La Inteligencia Artificial (IA) ha evolucionado de sistemas expertos frágiles a un enfoque basado en probabilidad y aprendizaje automático.

En 1988, se estableció una conexión importante entre la IA y otros campos, como la estadística y la teoría de decisiones, a través de las redes bayesianas y el aprendizaje por refuerzo.

Se utilizan conjuntos de problemas de referencia para demostrar el progreso en IA. (Reconocimiento de imágenes, traducción, etc.)

### Big Data (2001-Actualidad)
Los avances en la capacidad de cómputo y la creación de la World Wide Web han facilitado la creación de grandes conjuntos de datos, conocidos como "big data".

Estos grandes conjuntos de datos, que incluyen textos, imágenes, horas de voz y video, entre otros, han llevado al desarrollo de algoritmos de aprendizaje diseñados para aprovecharlos.

Aumentar el tamaño del conjunto de datos puede ser más beneficioso para mejorar el rendimiento del algoritmo que realizar pequeños ajustes al mismo.

La disponibilidad de "big data" y el cambio hacia el aprendizaje automático ayudaron a que la IA recuperara su atractivo comercial.

### Aprendizaje profundo (2011-Actualidad)

El aprendizaje profundo se refiere a aprendizaje automático que utiliza múltiples capas de elementos de cálculo simples y ajustables.

La característica de “profundo” no es alusiva al nivel de “comprensión” de la máquina. Simplemente hace referencia a la cantidad de capas que utilice, siguiendo la idea de que, a mayor cantidad de capaz, esta estructura es más profunda.

Los fundamentos del Deep Learning se dieron a conocer desde los años 70’s pero su apogeo llegó hasta el 2011. Debido más que todo a la evolución del hardware y a la gran cantidad de datos a disposición.

## Representaciones del conocimiento

### Sistemas basados en reglas

También denominados sistemas expertos, fueron el primer atractivo comercial exitoso del área de la Inteligencia Artificial.

IF (condición) THEN (acción)

Se usan reglas para guardar conocimientos.
Las reglas eran obtenidas por expertos en el respectivo campo.

### Redes semánticas
Se enfoca en la relación entre los objetos. Comúnmente representados como grafos dirigidos.

![Semantic Net](https://miro.medium.com/v2/resize:fit:549/1*nKuAX4Hbxzt45WZPIr8PSw.png)

### Árboles de búsqueda
La IA gira entorno a algoritmos. Usualmente es práctico construir un algoritmo complejo con algoritmos más sencillos que ayuden a alcanzar el objetivo principal.

### Redes neuronales artificiales (ANN)
Intenta simular las redes neuronales del cerebro humano.

Estas están estructuradas con neuronas artificiales conectadas entre sí. Cada neurona puede recibir y mandar señales a otras neuronas.

Estas neuronas pueden tener múltiples entradas y una sola salida.

## Agentes

Un agente es cualquier cosa que puede ser vista percibiendo su ambiente a través de sensores y realizando acciones en dicho ambiente mediante
actuadores.

Un ambiente puede ser cualquier lugar, es un espacio que definamos.

El término percepción hace alusión al contenido que fue “captado” por un agente a través de sus sensores. La secuencia perceptiva es el historial
de todo lo que el agente ha percibido.

Las acciones de un agente pueden depender de su conocimiento incorporado o de su secuencia perceptiva hasta el momento de realizada la acción.

El comportamiento de un agente está definido por su función de agente, que asigna cada secuencia perceptiva a una determinada acción.

### Agente racional

Se debe evaluar el comportamiento de un agente mediante pruebas de rendimiento que evalúa cualquier secuencia de estados.

Las pruebas de rendimiento es más efectivo basarse en lo que se desea lograr en el entorno en el que opera el agente, en lugar de centrarse 
en cómo se supone que el agente debe comportarse.

Se deben construir agentes que reflejen cierta incertidumbre de forma inicial sobre el rendimiento ideal que deben alcanzar y que
lo aprendan a través del tiempo 

![AI Teaches Itself to Walk](https://cdn.80.lv/api/upload/content/49/64524e233f064.jpg)
