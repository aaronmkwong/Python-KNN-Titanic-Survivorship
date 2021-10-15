# Python-KNN-Titanic-Survivorship

This project uses K-Nearest Neighbours to  classify a passenger's survivorship as died or survived. It uses the same engineered data and features as the  **[Logistic Regression Titanic Survivorship](https://github.com/aaronmkwong/Python-Logistic-Regression-Titanic-Survivorship)** project. The custom function k_value_trials() generates a dataframe of multiple trials (and the mean) of error rate versus k value curves using Monte Carlo cross validation. The custom function knn_mod_assess() returns a dataframe of all of the classifcation report results for each trial. These functions are used to create the following plot and average results table.

See also the **[Random Forest Titanic Survivorship](https://github.com/aaronmkwong/Python-Random-Forest-Titanic-Survivorship)** project.

The **_KNN outperformed Logistic Regression by 1%_**. 

The code can be viewed here: **[Titanic_Survivorship_KNN_01.ipynb](https://github.com/aaronmkwong/Python-KNN-Titanic-Survivorship/blob/main/Program%20Files/Titanic_Survivorship_KNN_01.ipynb)**.  

<img src="https://github.com/aaronmkwong/Python-KNN-Titanic-Survivorship/blob/main/Other%20Files/results_knn_titanic_survivorship_01.JPG">
