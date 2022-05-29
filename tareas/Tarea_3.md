
Universidad de Costa Rica  <br>
Escuela de Ciencias de la Computación e Informática <br>
CI-0163 - Análisis de Grandes Volúmenes de Datos <br>
Ciclo: I-2022 <br>
Docente: Allan Berrocal Rojas

---

# Tarea 3


## Preliminares

En esta tarea se utiliza la herramienta [`Jupyter Lab`](https://jupyter.org/index.html) que se mostró en clases. Alternativamente, usted puede hacer la tarea usando el servicio de `Google Cloud` llamado [Colab](https://colab.research.google.com/github/tensorflow/examples/blob/master/courses/udacity_intro_to_tensorflow_for_deep_learning/l01c01_introduction_to_colab_and_python.ipynb#scrollTo=YHI3vyhv5p85)

## Contexto

Esta tarea gira en torno a los conceptos de Redes Neuronales y Redes Neuronales Profundas (*Perceptron*, *Multilayer Perceptron (MLP)*, *Sequential Model* en `keras`)


## Asignación

1. Utilice el mismo *data set* de la Tarea 2. Asegúrese de que este cumpla con las características que se solicitaron para la Tarea 2. 

1. Trabaje nuevamente con el problema de clasificación o regresión que planteó en la Tarea 2. En esta tarea debe implementar un modelo para resolver dicho problema usando una Red Neuronal como lo ha hecho en la Práctica #6. Para ello utilice un *Sequential Model* disponible en la biblioteca de `keras`.  

1. Utilice las herramientas disponibles en la biblioteca de `scikit-learn` como preferencia tal y como lo ha hecho en las prácticas. 


## Evaluación 

Su solución debe incluir al menos los siguientes elementos:

 1. [5%] Una breve descripción del problema planteado y una justificación del enfoque a utilizar.
 1. [5%] Un apartado que muestre el uso de al menos dos técnicas de exploración de datos y su interpretación sobre las características del *data set* elegido. Esto puede ser similar a la Tarea 2, debe agregar al menos un aspecto nuevo en esta ocasión. 
 1. [10%] Un apartado que muestre la justificación y uso de al menos dos técnicas de transformación de datos, selección y extracción de atributos y su interpretación sobre el resultado obtenido al aplicar dichas técnicas. Esto puede ser similar a la Tarea 2, debe agregar al menos un aspecto nuevo en esta ocasión. 
 1. [65%] Un apartado que muestre el uso y los resultados de aplicar arquitecturas de redes neuronales para resolver el problema planteado.
   
    a. [45%] Experimente con al menos tres propuestas de arquitecturas de redes neuronales.
    
    b. [15%] Utilice una técnica de validación cruzada para evaluar el resultado de sus modelos exploratorios de arquitecturas. Explique brevemente la lógica que siguió para elegir la técnica de validación cruzada. También justifique la métrica de evaluación que seleccionó para el procedimiento de validación cruzada.

    c. [5%] Seleccione el modelo con el mejor desempeño obtenido. Argumente brevemente sobre la razón por la cual usted cree que este modelo obtubo el mejor desempeño entre los tres o más modelos con los cuales experimentó. 
 1. [15%] Un apartado que compare el resultado objetivo por el mejor modelo de esta tarea, y los  dos modelos que obtuvo en la tarea 2. Muestre los resultados obtenidos mediane una gráfica e incluya una pequeña discusión sobre su interpretación de estos resultados. ¿Cuál modelo le parece más ventajoso y porqué? Si tuviera que hacer una recomendación para un problema real en una organización ¿Cuál de estos modelos recomendaría utilizar y porqué?


## Entregables 

En su repositorio personal para este curso, cree un directorio que se llame `/tareas/tarea_3` y agregue al menos los siguientes archivos:


1. Un `notebook` (extensión `.ipynb`) de `Jupyter` donde se muestren las celdas ejecutadas (tablas, gráficos, etc.).
2. El *data set* inicial que utilizaron (pero, si está disponible públicamente, favor solo agregar un enlace en una celda para ello identificada dentro del `notebook`).
3. El `notebook` debe contener celdas en formato `Markdown` que identifiquen los apartados que se le solicitaron para facilitar la revisión del docente. 
4. El `notebook` debe contener celdas en formato `Markdown` donde aparezcan los elementos escritos que se le solicitaron como justificaciones e interpretaciones del trabajo realizado.
5. El código fuente de su solución debe mostrar buenas prácticas de programación aprendidas durante la carrera. Por ejemplo (pero no limitado a), uso de nombres significativos, modularización del código fuente, documentación del código fuente (no exhaustiva), ausencia de números mágicos, entre otras. 
4. En caso de que necesite proveer algún material adicional, cree un directorio `tareas/tarea3/material_supplementario` y agréguelo ahí. Para ello puede usar documentos en formato [`Markdown`](https://www.markdownguide.org/), archivos con extensión `PDF`, `csv` o imágenes. **Nota**: No entregar archivos con formato de la familia *Office* (e.g. *MS Word*, *Open Office*, *Pages*, etc.)





