# Proyecto_Integrador_M6_autos
Modelo de Regresión lineal y modelo de clasificación para predicción de precios de autos.
Este trabajo lo realicé en el marco de poryecto integrador de HENRY

### **Planteamiento de la problemática**
A partir de datos de características de autos (features), se busca predecir con un modelo de ML:
* Precio del auto 
* Gama del auto
  
### **Descripción del dataset**
> ML_cars.csv
![página1](airbnb_1.png)

#### A continuación explico los pasos realizados en la notebook 'proyecto_integrador_6cars.ipynb':
* Análisis exploratorio de datos (cantidad de datos, tipo de datos, análisis de nulos, duplicados)
* Análisis descriptivo de variables numéricas (histogramas y boxplot de features, identificación de co-linealidades entre features, correlación entre features y target)
* Análisis descriptivo de variables numéricas (violinplot, distribución de variables categóricas y relación con traget (precio)
* Preparación de datos (Generación de dummies, estc)
* Modelo de Regresión lineal para predicción de precio del auto (modelo de regresión lineal múltiple y modelo con regularización Ridge)
* Modelo de Clasificación: Se analizaron 3 modelos diferentes, regresión logística, vecinos cercanos (knn) y árbol de decisión. Se utilizó gridsearch para optimización de hiperparametros. Se compararon los modelos utilizando las métricas de Accurancy, curva ROC y Auc. También se analizaron las matrices de confusión para cada modelo.

  








