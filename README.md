# iris_regresion
# Modelo de aprendizaje supervisado: Clasificador de iris

Se hace repositorio para ejemplificar el modelo de ML de regresion logisitica multinominal
S se enfonca en la clasificacion de la flores iris,
tomando en cuenta ciertas condiciones, desde el tamaño del pétalo y del sépalo, tanto a lo largo como a lo ancho

Para esto se utilizaron las siguientes herramientas

Python
-Pandas
-Numpy
-Matplotlib
-Google 
-Sklearn
-Kaggle

## Fuente de datos:
https://www.kaggle.com/datasets/uciml/iris

## Objetivo:
EL fin de este proyecto es realizar un modelo de clasificacion supervisado con el dataset
de iris el cual contiene distintas caracterisitcas entre largo y ancho de pétalo y sépalo para distindas especies de flores

## Proceso

El proyecto se realizó en un colab de google, los primeros pasos que se realizaron fue la carga del dataset y verificar su información, si venia con datos nulls o ceros que nos afectaran
en el entrenamiento del modelo, al verificar que todo estuviera bien, por lo tanto no se hizo un tratamiento de los datos, 
tomamos nuetra columna target que fue la especie y la cual la convertimos en datos tipo enteros, esto para pasarlo a nuestro modelo
es un modelo de Regresión logistica, el cual el 25% de datos fue para entrenamiento y 35 datos de prueba aleatorios, 
se usaron estos valores debido a la cantidad de registros que se tiene en el dataset
al entrenarlo fue una clase multinomial debido a la cantidad de datos distintos en nuestra columna target

## Resultados
Se entrenó el modelo y nuestro score obtuvo un 94.73684 de efectividad
al igual se obtuvo una matriz de confusión el cual nos da buenos resultados en los valores verdaderos 

[[14  0  0]

 [ 0 11  1]

 [ 0  1 11]]

 ### Autor
 Luis Fernando Castillo
 https://github.com/Luisinho-31
 
 
   



