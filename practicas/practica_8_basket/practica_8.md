
Universidad de Costa Rica  <br>
Escuela de Ciencias de la Computación e Informática <br>
CI-0163 - Análisis de Grandes Volúmenes de Datos <br>
Ciclo: I-2022 <br>
Docente: Allan Berrocal Rojas

---

# Práctica 8 - Análisis de Asociación


revisar https://pbpython.com/market-basket-analysis.html

revisar
https://rasbt.github.io/mlxtend/user_guide/frequent_patterns/apriori/

## Preliminares

En esta práctica se utiliza la herramienta [`Jupyter Lab`](https://jupyter.org/index.html) que se mostró en clases. Alternativamente, usted puede hacer la práctica usando el servicio de `Google Cloud` llamado [Colab](https://colab.research.google.com/github/tensorflow/examples/blob/master/courses/udacity_intro_to_tensorflow_for_deep_learning/l01c01_introduction_to_colab_and_python.ipynb#scrollTo=YHI3vyhv5p85)

Para esta práctica los materiales se encuentran en los links que se mencionan más adelante. 

## Contexto

Esta práctica gira en torno a conceptos de Análisis de Asociación o _Market Basket Analysis_.

## Asignación

La práctica consiste en seguir un tutorial sobre el análisis de asociación y al mismo tiempo experimentar con una herramienta que le permite implementar dicho análisis. En esta práctica podrá aplicar algunos aspectos importantes a tener en cuenta para realizar su propio análisis de asociación. 

1. Cree un `Notebook` con el nombre `reporte_tutorial.ipynb` que utilizará a continuación. 
1. [40%] Primero abra el tutorial [Introduction to Market Basket Analysis in Python](https://pbpython.com/market-basket-analysis.html) escrito por Chris Moffitt. Luego, agregue una sección al notebook con título __Tutorial__ y transcriba ahí el código ejecutable del tutorial para que pueda estudiarlo, modificarlo y cambiarlo como parte de la práctica para facilitar su comprensión de los conceptos. 
1. [40%] Ahora, abra la página de la biblioteca `MLxtend` que describe el uso del algoritmo `apriori` ([Agrawal et al, 1994](https://www.it.uu.se/edu/course/homepage/infoutv/ht08/vldb94_rj.pdf)) para la creación de los _item sets_ así como el algoritmo `association_rules` para la creación de reglas de asociación como producto del análisis. Agregue una sección al notebook con título __MLextend Apriori__ y transcriba ahí el código ejecutable para que pueda estudiarlo, modificarlo y cambiarlo como parte de la práctica para facilitar su comprensión de los conceptos. 
1. [20%] Agregue una sección al notebook con título __Comentarios del ejercicio__ y escriba ahí un breve reporte (máximo 300 palabras) resumiendo lo que ha aprendido y el posible uso que le dará a esta materia como profesional. Incluya comentarios sobre aspectos que haya aprendido en el ejercicio, aspectos que no le quedan claros, o que quisiera conocer mejor.


## Otros recursos

Cuando el dataset es muy grande, el algoritmo apriori requiere mucho procesamiento y se torna ineficiente. Si le interesa el tema, revise otras implementaciones propuestas y realice los ejercicios de medición comparando los algoritmos.

- [FP-Growth](https://rasbt.github.io/mlxtend/user_guide/frequent_patterns/fpgrowth/) ([Han et al, 2004](https://link.springer.com/article/10.1023/B:DAMI.0000005258.31418.83?noAccess=true))
- [FP-Max](https://rasbt.github.io/mlxtend/user_guide/frequent_patterns/fpmax/) ([Grahne & Zhu, 2003](https://www.semanticscholar.org/paper/Efficiently-Using-Prefix-trees-in-Mining-Frequent-Grahne-Zhu/99e3735b2152e13543ae5ed1480daa7e87ea1b1d))


## Entregables 

En su repositorio personal para este curso, cree un directorio que se llame `/practicas/practica_8` y agregue ahí el archivo `reporte_tutorial.ipynb` 

<br>**Nota**: No entregar el reporte en archivos con formato de la familia *Office* (e.g. *MS Word*, *Open Office*, *Pages*, etc.)


 

