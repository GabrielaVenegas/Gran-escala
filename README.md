#T01-Estimación del valor de una propiedad de bienes raíces

Modelo de regressión Lasso para la estimación de una propiedad de bienes raices
Datos fuente: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

Funcionamiento del programa
Opc1 "Usando todas las variables"
  Modificar el archivo de "test.csv" de la carpeta de "house-prices-advanced-regression-techniques", con los datos deseados a estimar
    Pueden modificarse y predecir más de una línea a la vez
    El diccionario de variables se encuentra en la carpeta "house-prices-advanced-regression-techniques"
  Correr hasta la línea "línea_a_predecir" el código python "modelo.ipynb"
  Modificar el número de línea a predecir, el 0 está reservado al encabezado del archivo ".csv"
  Al correr este último modulo de código se obtendra la predicción 
  RMSE=.118582
  
Opc2 "Predicción usando regresión Lasso cón top 5 variables, sin ingeniería de variables" 
Del código de python "modelo.ipynb"
  Modificar las siguientes 5 variables del inmueble que se desea predecir
    GrLivArea=896 #Above grade (ground) living area square feet
    OverallQual=5 #Rates the overall material and finish of the house 1-10, 10 Very excellent 
    OverallCond=6 #Rates the overall condition of the house 1-10, 10 Very excellent 
    GarageCars=1 #Size of garage in car capacity
    YearBuilt=1961 #Original construction date
Al correr este último modulo de código se obtendra la predicción


  
