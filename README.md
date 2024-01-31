# Machine Learning

The repo consists of a compendium of projects involving Machine Learning algorithms.

**[Used Car Prices](https://www.kaggle.com/datasets/sujay1844/used-car-prices)**

**Description**: This is a tabular dataset, with each row representing a specific used car listing. 

The key attributes included in the dataset are: *Make and model of the car, Year of manufacture, Mileage, Odometer (kilometers driven) etc.*

The target variable in the dataset is 'Price' which gives the *selling price* of the car (units: 100,000 INR)

**Objective**: predict the selling price of the used car based on tha available attributes

**Problem Type**: Supervised Regression 

**Key concepts used in the analysis:**
* Data Profiling: Understanding dimensions, missing values, outliers etc.
* Exploratory Data Analysis & Visualization: Pairplots, Histograms, Box-plots etc.
* Data pre-procesing using Pipeline transformer from sci-kit learn
* Building candidate prediction models:
    * Linear Regressions:
        * Custom build Linear regression model trained using Normal Equations:
            * First approach was using matrix inversion to compute the 'hat' matrix
            * Estimate parameters using Moore-Pensrose pseudo inverse of the Design matrix
    * Custom built Stochastic Gradient Descent (Batch) model
    * Sci-kit learn models:
        * SGDRegressor
        * DecisionTree Regression
* Regularization using Ridge, Lasso & Elastic-net
* Hyper-parameter tuning using GridSearchCV


