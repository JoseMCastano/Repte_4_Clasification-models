# Repte_4_Clasification-models

## Modelo predictivo de tumores de mama

El objetivo del ejercicio es el desarrollo de un modelo predictivo de clasificación, que permita a partir de unas variables asociadas a un tumor de mama, predecir si se trata de un tumor benigno o maligno.

El resultado con las predicciones se adjunta en este mismo repositorio en el archivo 'resultados', en formato csv.

El ejercicio corresponde a un reto propuesto por nuwe.ie (https://nuwe.io/challenge/repte-4-models-de-classificacio)

## Explicación del Dataset

El dataset contiene:
- 30 variables numéricas relativas a dimensiones y formas del tumor
- 1 columna objetivo con la diagnosis: 0 si es benigno y 1 si es maligno.

## Resultados

Hemos construído el modelo utilizando el AdaBoost Classifier. Hemos validado los resultados mediante cross validation y finalmente hemos ajustado los hiperparámetros con GridSearch. Los resultados obtenidos con el dataset de train son:
- Accuracy:  0.978
- Precision: 0.968
- Recall:    0.9687
- Roc_Auc:   0.976

## Requisitos

Este notebook requiere Python 3.6 o versiones superiores

Necesitas tener instaladas las siguientes librerías:
 pip install pandas
 pip install numpy
 pip install matplotlib
 pip install seaborn
 pip install scipy
 pip install -U scikit-learn
