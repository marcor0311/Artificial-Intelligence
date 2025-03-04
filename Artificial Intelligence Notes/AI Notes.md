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

