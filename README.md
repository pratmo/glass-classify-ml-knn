### glass-classify-ml-knn

In this code we prepare a Machine Learning Model using KNN Algorithm to classify glass based on it's type from the below distinguishing features. We also used the grid search for algorithm tuning to find the best n_neighbours for this problem, and visualized the same using matplotlib.pyplot.

Data Description (glass.csv):

RI : refractive index

Na: Sodium (unit measurement: weight percent in corresponding oxide, as are attributes 4-10)

Mg: Magnesium

AI: Aluminum

Si: Silicon

K:Potassium

Ca: Calcium

Ba: Barium

Fe: Iron

Type: Type of glass: (class attribute)
1 -- building_windows_float_processed
2 --building_windows_non_float_processed
3 --vehicle_windows_float_processed
4 --vehicle_windows_non_float_processed (none in this database)
5 --containers
6 --tableware
7 --headlamps

Language: Python (3.9.2)

Tool: Jupyter Notebook (conda 4.9.2)

System: Linux (Ubuntu) 20.04.2 LTS Focal Fossa
