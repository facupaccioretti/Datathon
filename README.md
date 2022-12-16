# **PROYECTO INDIVIDUAL 2 | DATATHON**
​

### **Introduccion:**
El segundo proyecto individual de nuestro cursado en henry se trata sobre predicciones con un modelo de machine learning y a continuacion explicaremos resumidamente el trabajo realizado.
​
### **Ingesta y herramientas:**
​
Utilizamos python y pandas para la ingesta, analisis exploratorio de datos y la transformacion de los datos. Luego utilizamos scikit-learn para realizar el modelo predictivo.
​
### **Descripción del problema:**

Un centro de salud nos pide predecir si un paciente hospitalizado tendra una estadía larga en el hospital o mas bien corta. Nos brindan un dataset con informacion de hospitalizaciones previas.

### ​**Preprocesamiento de datos:**

​El preprocesamiento es uno de los estadios más importantes en el flujo de trabajo de un data scientist. a distinción entre un buen y un mal modelo de Machine Learning, antes que por la elección de un algoritmo específico, estará dada por un correcto preprocesamiento de datos.
En este caso no teniamos valores faltantes en nuestro dataset, y a la hora de la normalizacion solo cambiamos el idioma de nuestro dataset para no tener confusiones a la hora de trabajarlo. 
Utilizamos distintas formas de codificion para las variables categoricas, como one hot encoding o ordinal encoding.
Luego para finalizar eliminamos las columnas que no fueran relevantes para nuestro modelo.

### **Modelo de prediccion:**

Utilizamos scikit-learn (libreria de python) ya que esta cuenta con funciones que crean una regresion logistica.

Elegimos regresion logistica ya que esta es un tipo de análisis de regresión utilizado para predecir el resultado de una variable categórica (una variable que puede adoptar un número limitado de categorías, en este caso estadia larga o corta) en función de las variables independientes o predictoras.








