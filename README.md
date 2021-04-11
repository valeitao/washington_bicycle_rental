# Washington Bicycle Rental
Masters' project focused on building models able to predict the number of bicycles rented in a bike-sharing system, in Washington D.C., United States.

## Preprocessing

Integration of various sources:
1. [Bike trips and schedules](https://s3.amazonaws.com/capitalbikeshare-data/index.html)
2. Bike stations and their localizations
3. [Weather data in Washington D.C.](https://power.larc.nasa.gov/data-access-viewer/)

## Geographical Data Processing

To this subtask we propose clustering analysis of bike stations with three methods: K-Means, DBSCAN, Affinity Propagation.

Method analysis done with the following metrics: Silhouette Score, Calinski-Harabasz Index and Davies-Bouldin Index, complemented with graphic analysis and visualizations.

## Regression Models

Goal: to predict bicycle rental demand for a given day and hour, and for a specific cluster obtained in the geographical data processing.

Models used:
1. Ensemble Estimators: **Random Forest Regressor**;
2. Boosting estimators: **AdaBoost Regressor**;
3. Bagging estimators: **Bagging Regressor**;
4. **Support Vector Regressors** e **K-Nearest Neighbors**.
