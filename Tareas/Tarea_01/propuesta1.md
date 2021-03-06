---
output:
  pdf_document: default
  html_document: default
---
Propuesta 1
===================================

# 1. Reconocimiento del problema.
En ciertas comunidades rurales se observan altas tasas de absentismo escolar. Se sabe que son diversas las causas de este problema, entre ellas destacan las siguientes: contexto social violento o frágil, dificultades de acceso a la escuela, desnutrición y enfermedades digestivas contagiosas. Por ello, un grupo de investigación se pregunta si la acción de dos tratamientos (uno contra la desnutrición y otro contra las enfermedades digestivas contagiosas) o su interacción pueden tener efectos de disminución sobre el absentismo escolar.

<!--
## Preguntas
-->

# 2. Definir factores o niveles
Se definen dos factores: una nueva formula de nutrientes (factor 1) y un medicamento para ciertos parásitos (factor 2) que se incorpora al desayuno escolar. Por lo tanto, tenemos cuatro tratamientos: 1) desayuno escolar fortificado nutricionalmente y con medicamento añadido, 2) desayuno escolar con nueva fórmula nutritiva pero sin medicamento, 3) desayuno escolar usual con medicamento y 4) desayuno ordinario (tratamiento de control).

<!--	
## Preguntas
- 2019-02-13 (Víctor) ¿Entonces en este experimento lo que queremos medir es la parte de "desnutrición y enfermedades digestivas"? Es decir, ¿las demás variables; contexto social violeto o fragil, pobreza familiar y dificultades de acceso a la escuela serían aleatorizadas?

+ _2019-02-15 (Georgina) Más bien lo que se intenta medir con este experimento es el absentismo escolar originado por desnutrición y enfermedades digestivas. En relación con la segunda pregunta, estaba pensando en esas varibles como variables de control que nos permitan tener menos sesgos en la comparación de las escuelas. La aleatorización vendría dada en la asignación de los tratamientos. La aleatorización de las demás variables también sería necesaria pero en los estudios de este corte rara vez suele hacerse por cuestiones de logística, control y costos. De cualquier modo podemos ponerlas sólo habría que redactar el punto 6 considerando esto._
-->
# 3. Unidad experimental
La unidad experimental es el alumnado agregado de cada una de las escuelas. Mientras que las submuestras son los alumnos individualmente (unidades observacionales más elementales). En este caso el efecto del tratamiento de un alumno ante enfermedades digestivas puede tener externalidades positivas en el resto de la escuela (por ello, definimos la unidad experimental como la escuela o alumnado agregado).

<!--
## Preguntas
- 2019-02-13 (Víctor)  ¿Entonces tenemos que aleatorizar las escuelas de tal forma que en cada factor se tengan escuelas de todo tipo?

+ _2019-02-15 (Georgina) Creo que se contesta con lo que puse en la anterior._
-->

# 4. Variable de respuesta
Tasa de absentismo escolar diaria. Suponiendo que no tenemos limitaciones logísticas ni de recursos, podríamos recopilar la información diaria de absentismo en cada escuela y comparar posteriormente diferentes medidas (por ejemplo, media y varianza mensual de absentismo en cada escuela) y tendencia de los distintos tratamientos (esto podría realizarse durante algunos meses o años).

<!--
## Preguntas
- 2019-02-13 (Víctor)  ¿Serían observaciones mensuales para logarar 24 observaciones y despues promediar la tasa de absentismo? o ¿Calcularíamos la tasa de absentismo escolar media cada mes y evaluariamos la evolución de dicha tasa a lo largo de 24 meses?

+ _2019-02-15 (Georgina) Ambas opciones me parecen viables. Sin embargo, idealmente por cuestiones de costo la primera parecería mejor pero dado que es un ejemplo hipotético me parece que podríamos poner la segunda y justificar que la información medida a lo largo del tiempo puede tener menos probabilidades de errores por factores exógenos que una única medida cada mes._
-->
# 5. Elección del diseño experimental
En localidades equiparables, se identifican distintos _bloques_ de escuelas con ciertas características similares: nivel de violencia, nivel promedio de estatus económico de los alumnos, tiempos promedio de traslado a la escuela y medio de transporte equiparables (facilidad de acceso). Entre cada uno de estos grupos se aplican aleatoriamente los distintos tratamientos.
Además, se tiene como variable de control a la matrícula por grupo (pues se señalaba previamente que la interacción del tratamiento en las submuestras también puede afectar el efecto de estas individualmente y, en consecuencia, en el agregado) y tasa inicial de absentismo (previa al tratamiento). 

# 6. Determinación del número de repeticiones
_ **(A DISCUSIÓN)** No puse nada acá pues generalmente en este tipo de experimentos es dificil encontrar unidades experimentales equiparables de control (más aún para repeticiones). No obstante, dado que es un experimento ficticio, creo que podríamos poner algo no tan realista en este punto_.

# Comentarios generales:
- 2019-02-13 (Víctor) Por mi parte me parece un buen planteamiento, creo que podemos trabajar con esta propuesta para la primer tarea. Pero si sería necesario que platicaramos un poco más los puntos para ir afinando cada detalle y luego procedemos para plantearlo

- 2019-02-15 (Georgina) Desarrollé originalmente hasta el lineamiento 5 de las notas pero si todos están conformes con la propuesta creo que faltaría del 6 al 9 (principalmente el punto 6).

# Dudas:

- 2019-02-15 (Georgina) ¿Alguien sabe cómo puedo agregar bibliografía directamente en este archivo? Si les parece bien esta propuesta, puedo poner algún par de referencias que han hecho experimentos similares.  