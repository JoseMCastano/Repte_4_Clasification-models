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

Hemos construído el modelo utilizando el AdaBoost Classifier. Hemos validado los resultados mediante cross validation y finalmente hemos ajustado los hiperparámetros con GridSearch.

Modelo 	             Accuracy 	Precision 	Recall 	F1 	      Roc_Auc     
AdaBoostClassifier  	0.967033 	0.96875 	0.939394 	0.953846 	0.961076
AdaBoost Optimizado 	0.978022 	0.96875 	0.968750 	0.968750 	0.975900
