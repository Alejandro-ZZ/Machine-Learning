# TP-6: Regresores y reducción de dimensionalidad

## *6_Regressors_Boston_Housing.ipynb*

Implementación de **modelos de regresión** para predecir los precios de venta de propiedades en la ciudad de Boston. El dataset usado (*Boston Housing*) 
contiene 506 observaciones con 14 variables. Los datos se obtienen de [Kaggle | Boston Housing dataset](https://www.kaggle.com/altavish/boston-housing-dataset).

Adicional, se realiza un proceso de **selección de atributos** para evaluar si esto permite mejorar el comportamiento de los regresores y disminuir los features 
con los que se entrena cada modelo. Dentro de las técnicas implementadas se encuentran:

- Análisis univariado ([SelectKBest de Sklearn](https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.SelectKBest.html))
- Selección secuencial de atributos: forward y backward ([SequentialFeatureSelector de Sklearn](https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.SequentialFeatureSelector.html))
- Eliminación recursiva de atributos ([RFE de Sklearn](https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.RFE.html))
- Análisis de componentes principales ([PCA con Sklearn](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html))
