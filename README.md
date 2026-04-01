1 - Logistic Regression

2 - Support Vector Machine (SVM)

3 - Random Forest

4 - XGboost

5 - Adaboost

6 - Catboost 

7 - Decision Tree

8 - K-Nearest Neighbors (KNN)

9 - Naive Bayes

10 - LightGBM

11 - Gradient Bosting

12 - Extra Trees

top 6 model ANSH ( 1 - 6 )

bottom 6 model SHIVAM ( 7 - 12 )

///////////////////////////////////

Target Column (Output)


diagnosis


M → Malignant (Cancer)

B → Benign (Non-Cancer)

//////////////////////////////////

Columns Removed

These are not used in prediction:


id → just patient number

Unnamed: 32 → empty column


So they are dropped.


/////////////////////////////////


Columns Used as Input Features


Total 30 columns



Mean Features

radius_mean

texture_mean

perimeter_mean

area_mean

smoothness_mean

compactness_mean

concavity_mean

concave points_mean

symmetry_mean

fractal_dimension_mean

////////////////////////////////

Standard Error Features

radius_se

texture_se

perimeter_se

area_se

smoothness_se

compactness_se

concavity_se

concave points_se

symmetry_se

fractal_dimension_se

/////////////////////////////////

Worst Features

radius_worst

texture_worst

perimeter_worst

area_worst

smoothness_worst

compactness_worst

concavity_worst

concave points_worst

symmetry_worst

fractal_dimension_worst
