# Clasificación para el demartamenteo de RRHH
**Disponemos del Dataset proporcionado por el departamento de recursos humanos de una empresa. El fichero contiene un histórico de todos los empleados que ha tenido la empresa con multitud de campos. Se pretende crear un sistema capaz de predecir que empleados se marcharán de la empresa, y cuales permanecerán en ella.** 
## Desarrollo

Para la realización del clasificador se ha utilizado el lenguaje de programación **Python** junto a las librerias **Pandas**, **NumPy**, **Seaborn**, **Matplotlib**, **Sklearn** y **TensorFlow**.

El entorno de desarrollo utilizado ha sido **Google Colab**.

Dataset: https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset 

## Clasificadores utilizados

**Regresión Logística**

**Random Forest**

**Deep Learning**

## Metodología utilizada

Para el diseño de los clasificadores se ha realizado un primer estudio de los datos utilizando diferentes gráficas para ver el comportamiento de las características (Histogramas, Matriz de correlación, Mapas de calor, Mapas de densidad y Diagrama de cajas) 

Se ha dividido el dataset en Train/Test con una proporcion de 75% para el train y el 25% para el test.

Se ha diseñado y entrenado los clasificadores, obteniendo diferentes métricas para cada uno de ellos.

### Cuaderno Departamento_de_Recursos_Humanos.ipynb
https://github.com/PabloCaceresRamos/Clasificacion-para-el-demartamenteo-de-RRHH/blob/06ade3294709d3efdae1c7f5dbd835961c2e0d9a/Departamento_de_Recursos_Humanos.ipynb

Se entreno los clasificadores con todas las características, obteniendo los siguientes resultados:

F1 Regresión Logística: 0.87

F1 Random Forest: 0.84

F1 Deep Learning: 0.83

### Cuaderno Departamento_de_Recursos_Humanos_Mejora.ipynb

Se ha realizado un estudio más profundo de los datos, y se han utilizado las catacteristicas más relevantes para la clasificación. Los resultados obtenidos son:

F1 Regresión Logística: 1.00

F1 Random Forest: 1.00

F1 Deep Learning: 1.00
