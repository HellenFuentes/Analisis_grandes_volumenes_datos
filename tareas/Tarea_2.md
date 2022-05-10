
Universidad de Costa Rica  <br>
Escuela de Ciencias de la Computación e Informática <br>
CI-0163 - Análisis de Grandes Volúmenes de Datos <br>
Ciclo: I-2022 <br>
Docente: Allan Berrocal Rojas

---

# Tarea 2


## Preliminares

Para esta tarea puede utilizar ya sea la herramienta [`Jupyter Lab`](https://jupyter.org/index.html) que se ha usado en clases, o también el servicio de `Google Cloud` llamado [Colab](https://colab.research.google.com/github/tensorflow/examples/blob/master/courses/udacity_intro_to_tensorflow_for_deep_learning/l01c01_introduction_to_colab_and_python.ipynb#scrollTo=YHI3vyhv5p85)

## Contexto

Esta tarea gira en torno a los conceptos de algoritmos de aprendizaje de máquina basados en algoritmos de aprendizaje de máquina de los estudiados en clase hasta el momento (*DecisionTree*, *RandomForest*, *Extreme Gradient Boosting*, *Extra Trees*, o *Support Vector Machines*).


## Asignación

1. Proponga un problema original de clasificación (binaria o multiclase), o un bien un problema de regresión e implemente un modelo para resolver dicho problema usando **al menos dos** algoritmos de aprendizaje de máquina de los listados arriba. 

1. Busque un *data set* público (libre elección) para utilizarlo en el problema planteado. Si el problema es de clasificación, su *data set* debe estar etiquetado. El *data set* no debe ser gigantesco pero sí grande dentro de lo que sea posible para su ambiente de trabajo. La riqueza de un *data set* no depende únicamente de su tamaño sino también de las características de los datos. Sin embargo, aara sacar mejor provecho de los algoritmos vistos a utilizar, procure conseguir un *data set* con no menos de 10 mil observaciones.  

1. Como sugerencia utilice las herramientas disponibles en la biblioteca de `scikit-learn`, pero no se limite a ellas. Si desea utilizar otras herramientas de su preferencia lo puede hacer. 

## Evaluación

Su solución debe incluir al menos los siguientes elementos:

 1. [5%] Una breve descripción del problema planteado y una justificación del enfoque a utilizar.
 2. [10%] Un apartado que muestre el uso de al menos dos técnicas de exploración de datos y su interpretación sobre las características del *data set* elegido.
 3. [10%] Un apartado que muestre la justificación y uso de al menos dos técnicas de preprocesamiento y limpieza de datos y su interpretación sobre el resultado obtenido al aplicar dichas técnicas. 
 4. [10%] Un apartado que muestre la justificación y uso de al menos dos técnicas de transformación de datos, selección y extracción de atributos y su interpretación sobre el resultado obtenido al aplicar dichas técnicas.
 5. [35%] Un apartado que muestre el uso y los resultados de aplicar al menos dos algoritmos de aprendizaje de máquina para resolver el problema planteado. Compare los resultados obtenidos por cada modelo y argumente objetivamente sobre la calidad de los resultados obtenidos y la capacidad de generalización de sus modelos. 
 6. [10%] Un apartado que muestre la justificación y el uso de al menos dos técnicas de evaluación de modelos (e.g. *k-fold cross validation*, selección de hiper-parámetros del modelo, *nested cross validation*, algoritmos genéticos, etc.) **NOTA**: No intente hacer una búsqueda exhaustiva de parámetros. Pero sí debe probar con varios parámetros y guardar los resultados parciales para justificar la elección de los parámetros que le general un mejor desempeño.
 7. [10%] Un apartado que muestre los resultados obtenidos incluyendo al menos dos gráficas y al menos una tabla con comparaciones numéricas y su interpretación sobre los resultados obtenidos. 
 8. [10%] Identifique y describa al menos tres de los atributos o variables de mayor importancia en los modelos resultantes. 



## Entregables 

En su repositorio personal para este curso, cree un directorio que se llame `/tareas/tarea_2` y agregue al menos los siguientes archivos:

1. Un `notebook` (extensión `.ipynb`) de `Jupyter` donde se muestren las celdas ejecutadas (tablas, gráficos, etc.).
2. El *data set*  que utilizaron (pero, si está disponible públicamente, favor solo agregar un enlace en una celda para ello identificada dentro del `notebook`).
3. El `notebook` debe contener celdas en formato `Markdown` que identifiquen claramente los apartados que se le solicitaron anteriormente. 
4. El `notebook` debe contener celdas en formato `Markdown` donde aparezcan los elementos escritos que se le solicitaron como justificaciones e interpretaciones del trabajo realizado.
5. El código fuente de su solución debe mostrar buenas prácticas de programación aprendidas durante la carrera. Por ejemplo (pero no limitado a), orden, uso de nombres significativos, modularización del código fuente, documentación del código fuente (no exhaustiva), ausencia de números mágicos, referencias a material desarrollado por alguien más, entre otras. 
4. En caso de que necesite proveer algún material adicional, cree un directorio `tareas/tarea2/material_supplementario` y agréguelo ahí. Para ello puede usar documentos en formato [`Markdown`](https://www.markdownguide.org/), archivos con extensión `PDF`, `csv` o imágenes. **Nota**: No entregar archivos con formato de la familia *Office* (e.g. *MS Word*, *Open Office*, *Pages*, etc.)



