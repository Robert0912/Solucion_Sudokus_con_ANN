# Solucion_Sudokus_con_ANN
## Integrantes: 
  - Luis Carlos David Baron Mosquera
  - Sergio Andrés Rojas Moreno
  - Robert Alexis Urbina Mojica

## Descripción
La solución tradicional de Sudokus, se realiza basada en algoritmos lógicos, probabilísticos y algunos casos a fuerza bruta. En este documento se busca explorar la solución de Sudokus por medio de redes neuronales artificiales, para lo cual se plantean dos modelos de perceptrón multicapa que reciben el planteamiento de un Sudoku tradicional y devuelven su solución. Para cada modelo se muestra su proceso de desarrollo, construcción y los resultados en el rendimiento de los dos modelos planteados.

## Requerimientos
python3
keras - 2.4.0
tensorflow - 2.3.0
pandas - 1.1.4
numpy - 1.18.5

## Contenido del proyecto
| Archivo                              | Descripción                                                   |
| ------------------------------------ |:-------------------------------------------------------------:|
| Sudokus_Version2_ImpModel.ipynb      | Propuesta 2 de red neuronal leyendo el modelo entrenado       |
| Sudokus_Version2_Training.ipynb      | Propuesta 2 de red neuronal entrenando el modelo de propuesta |
| Sudokus_training100k.ipynb           | Propuesta 1 de red neuronal con 100 mil datos                 |
| Sudokus_training100k.ipynb           | Propuesta 1 de red neuronal con 100 mil datos                 |
| Sudokus_training10k.ipynb            | Propuesta 1 de red neuronal con 10 mil datos                  |
| Solucion_De_Sudokus_con_ANN.pdf      | Informe sobre los resultados de la red                        |
| LICENSE                              | Licencia                                                      |

## Estructuras de red neuronal propuestas

Estructura para red neuronal 1:
![alt text](https://github.com/Robert0912/Solucion_Sudokus_con_ANN/blob/main/Imagenes/Modelo_ANN_1.png "Estructura para red neuronal 1")

Estructura para red neuronal 2: 
![alt text](https://github.com/Robert0912/Solucion_Sudokus_con_ANN/blob/main/Imagenes/Modelo_ANN_2.png "Estructura para red neuronal 2")

## Rendimiento y exactitud

![alt text](https://github.com/Robert0912/Solucion_Sudokus_con_ANN/blob/main/Imagenes/img1.PNG "Resultados")

## Referencias

Para consultar el dataset puede ir a https://www.kaggle.com/bryanpark/sudoku
