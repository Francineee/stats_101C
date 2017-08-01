# stats_101C
This is the final project of my Statistics 101C class. As a team of three, we participate in a private Kaggle competition hosted by our instructor. We are given an initial data set including several fields related to LAPD response time, including the response variable. Our goal is to build a predictive model using any machine learning method of our choice in order to best predict future response time of the Los Angeles Police Department. As part of the focus of this course--data mining--we are free to use external data sets we may find relevant.

We implemented XGBoost in two of our best models due to its speed and flexibility. Since our data sets are relatively large, traditional random forest algorithm couldn't run fast enough in R. Besides, we consider XGBoost less prone to overfitting because of its penalty parameter to the complexity of the trees.

As for external data sets, we included geographical data of individual neighborhood, i.e. number of parks; average statistics of individual neighborhood, i.e. average response time calculated from training set; sociological data, i.e. income level; etc. Most of our external data sets come from Los Angeles Open Data.
