# predictive_bank_churn_modeling
Creación de modelos de machine learning para predecir la cancelación de cuentas bancarias. 
***Proyecto desarrollado como evaluación final del Sprint Aprendizaje supervisado del Bootcamp de Data Scientist de TripleTen.***

## Contexto del proyecto
Los clientes de Beta Bank se están yendo, cada mes, poco a poco. Los banqueros descubrieron que es más barato salvar a los clientes existentes que atraer nuevos.

Necesitamos predecir si un cliente dejará el banco pronto. Se tienen los datos sobre el comportamiento pasado de los clientes y la terminación de contratos con el banco.

## Objetivo del proyecto
1. Crear un modelo con el máximo valor F1 posible (al menos 0.59).

    1.1. Verificar F1 para el conjunto de prueba. 

2. Medir la métrica AUC-ROC

    2.1. Compararla con el valor F1.

## Modelos de machine learning creados
- Logistic Regression
- Random Forest Classifier
- Tree Decission Classifier 

## Librerías principales utilizadas
- pandas
- matplotlib
- seaborn
- numpy
- sklearn
- warnings

## Resultados
- En este proyecto se demuestra el impacto que tiene el tratamiento del balance de clases para la optimización de los modelos.
- El mejor modelo entrenado fue un bosque aleatorio, consiguiendo un score f1 de 0.62, superando el score mínimo requerido.
- La capacidad predictiva del modelo es buena, consiguiendo un valor de ROC AUC de 0.84.
- En el archivo "proyecto_9" se pueden revisar cada paso del proyecto, desde el EDA hasta la selección de los modelos.