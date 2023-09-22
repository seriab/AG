# Practicas 

Esta carpeta contiene Jupyter notebooks de diferentes pruebas.


## One-Max

A continuación algunas soluciones:

- **[Algoritmo Genetico - OneMax](01Algoritmo_Genetico_OneMax.ipynb):** Este algoritmo se utiliza para abordar el problema OneMax sin utilizar ningun framework.
- **[Algoritmo Genetico - OneMax con Deap](02Algoritmo_Genetico_OneMax_Deap.ipynb):** Este algoritmo se utiliza para abordar el problema OneMax utilizando el framework Deap.
  
## Problema de la Mochila
A continuación algunas soluciones:

- **[Nsga2 - Problema de la mochila](03Problema_de_la_mochila_real.ipynb):** Este algoritmo se utiliza para abordar el problema de la mochila sin utilizar ningun framework.
- **[Nsga2 - Problema de la mochila con Deap](04Problema_de_la_mochila_con_nsga2_Deap.ipynb):** Este algoritmo se utiliza para abordar el problema de la mochila utilizando el framework Deap.
- **[Nsga2 - Problema de la mochila con Platypus](05Problema_de_la_mochila_con_nsga2_Platypus.ipynb):** Este algoritmo se utiliza para abordar el problema de la mochila utilizando el framework Platypus.
- **[Nsga2 - Problema de la mochila con Inspyred](06Problema_de_la_mochila_con_nsga2_Inspyred.ipynb):** Este Este algoritmo se utiliza para abordar el problema de la mochila utilizando el Inspyred.
- **[Nsga2 - Problema de la mochila con Evotorch](06Problema_de_la_mochila_con_nsga2_Inspyred.ipynb):** Este Este algoritmo se utiliza para abordar el problema de la mochila utilizando el Evotorch.
- **[Nsga2 - Problema de la mochila utilizando realizando el calculo de la función del fitness en Pytorch]
- **[Nsga2 - Problema de la mochila utilizando realizando el calculo de la función del fitness en Tensorflow]

## Frameworks de aprendizaje profundo
- **[Pytorch]**
- **[Tensorflow]**

## Tablas comparativas 

| Programación sin Framework  |Programación con Framework|
|--------------|--------------|
|No se requiere dependencias de terceros y posee mayor flexibilidad al escribir código y nos obliga a tener una mejor compresión de los algoritmos genéticos para poder implementarlo, en contrapartida se requiere mayor cantidad de tiempo.    | Facilita el desarrollo ofreciendo funciones predefinidas para implementar los algoritmos geneticos y de esa manera ahorrar tiempo en la implementación y enfocar asi el esfuerzo en el problema específico a resolver. También ayuda utilizar las funciones aplicando las mejores prácticas y así evitar errores comunes, además la mayoría poseen documentación para facilitar la compresión del framework.   |

Comparación entre trabajar sin Framework y con Framework


| Framework  | Versión  | Tipo de licencia   | Procesamiento Paralelo  | Facilidad de uso       | Parametrizaciones nativas | Documentación  | Algorithms   |
|------------|----------|--------------------|--------------------------|-------------------------|---------------------------|----------------|--------------|
| Deap       | 1.4.2    | LGPL-3.0 license   | Paralelizacion en CPU   | Uso sencillo con muchas opciones | SI            | Muy completa    | - Genetic programming using prefix trees
                                                                                                                      Loosely typed, Strongly typed
                                                                                                                      Automatically defined functions
                                                                                                                      - Evolution strategies (including CMA-ES)
                                                                                                                      - Multi-objective optimisation (NSGA-II, NSGA-III, SPEA2, MO-CMA-ES) |
| Platypus   | 1.1.0    | GPL-3.0 license    | Paralelizacion en CPU   | Uso simplificado        | SI            | Basica         | CMA-ES, NSGA-II, NSGA-III, GDE3, IBEA, MOEA/D, OMOPSO, EpsMOEA, SPEA2 |
| Inspyred   | 1.0.1    | MIT license        |                         | Uso complejo             | Si pero complicada de utilizar | Amplia        | GA, ES, PSO, ACO, SA, PAES, NSGA-II |
| Evotorch   | 0.4.1    | Apache-2.0 license | Paralelizacion en GPU   |                         | Basica        |                |                |

