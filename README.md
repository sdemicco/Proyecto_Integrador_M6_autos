# Proyecto_Integrador_M6_autos
Modelo de Regresión lineal y modelo de clasificación para predicción de precios de autos.
Este proyecto lo realice en el marco de poryecto integrador de HENRY

### **Planteamiento de la problemática**
​A partir de datos de caracteristicas de autos (features), se busca predecir con un modelo de ML:
* Precio del auto 
* Gama del auto
  
### **Descripcion del dataset**
> ML_cars.csv

#### A continuacion explico los pasos realiados en laa notebook proyecto_integrador_6cars.ipynb:
* Analisis exploratorio de datos ( cantidad de datos, tipo de datos, analisis de nulos, duplicados)
* Analisis descriptivo de variables numéricas (histogramos y boxplot de features, identificación de colinealidades entre features, correlacion entre features y target)
* Analisis descriptivo de variables numéricas (violinplot, distribucion de variables categoricas y relacion con traget (precio)
* Preparación de datos (Genración de dummies, estc)
* Modelo de Regresión lienal para predicción de precio del auto ( modelo de regresion lineal multiple y modelo con regularizacion Ridge)
* Modelo de Clasificacación: Se analizaron 3 modelos diferentes, regresión logistica, vecinos cercanos (knn) y arbol de decisión. Se utilizo gridsearch para optimización de hiperparametros.Se compararon los modelos utilizando las metricas de Accurancy, curva ROC y Auc. Tambien se analizaron las matrices de confusión para cada modelo. 
  








