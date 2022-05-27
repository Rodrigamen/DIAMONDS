# DIAMONDS

Objetivo del proyecto
El objetivo de este proyecto es entrenar el mejor modelo de predicción posible para predecir el precio de los diamantes dadas sus características y participar en la competición de kaggle aunque no vaya a ganarla.

Metodología:

1) Análisis del dataset de train y adaptación de los datos

2) Entrenamiento del modelo predictivo, testeo y validación del mismo

3) Predicción en los datos reales

Organización del proyecto

Carpeta src donde se encuentran las funciones aplicadas y separadas por la dedicación que se les da.

Carpeta notebooks donde se encuentran los .ipynb donde analizo y limpio datos, entreno modelo y predigo el precio en el archivo test

Carpeta data donde se encuentran los archivos donde se almacenan los test, train y el escalar resultantes del mejor modelo

Carpeta presentación donde se muestra las diapositivas a presentar en clase

Conclusiones
Tras ejecutar hasta cinco pipelines, encuentro que el mejor modelo es un Gradient Boost. A recalcar que no hay real diferencia tras varios análisis entre las predicciones quitando y sin quitar outliers, lo cual no me deja de parecer curioso.

Enlaces de interés
NumPy - https://numpy.org/doc/stable/

sklearn - https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.ExtraTreesRegressor.html

Pandas - https://pandas.pydata.org/docs/

MatPlotLib - https://matplotlib.org/3.3.1/contents.html

Seaborn - https://seaborn.pydata.org

Math - https://docs.python.org/3/library/math.html

Pickle - https://docs.python.org/3/library/pickle.html

Info sobre diamantes - https://www.info-diamond.com/
