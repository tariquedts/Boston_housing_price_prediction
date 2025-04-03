# Boston Housing Price Prediction

### Overview
This project aims to build a machine learning model to predict house prices in the Boston area based on various features such as crime rate, average number of rooms, and property tax rates. The dataset used is the Boston Housing Dataset, which is a popular dataset in regression problems.

### Table of Contents
- Dataset
- Installation
- Usage
- Modeling Approach
- Evaluation Metrics
- Results
- Contributions
- License

### Dataset
The dataset contains 506 samples with 13 features describing different aspects of housing in Boston, such as:
- CRIM: per capita crime rate by town
- ZN: proportion of residential land zoned for lots over 25,000 sq.ft.
- INDUS: proportion of non-retail business acres per town
- CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
- NOX: nitric oxides concentration (parts per 10 million)
- RM: average number of rooms per dwelling
- AGE: proportion of owner-occupied units built prior to 1940
- DIS: weighted distances to five Boston employment centres
- RAD: index of accessibility to radial highways
- TAX: full-value property-tax rate per $10,000
- PTRATIO: pupil-teacher ratio by town
- B: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
- LSTAT: % lower status of the population
- MEDV: Median value of owner-occupied homes in $1000's

### Installation
1. Clone the repository:
- https://github.com/tariquedts/Boston_housing_price_prediction.git
Boston_housing_price_prediction

2. Install required dependencies
- [pip install -r requirements.txt](https://vscode.com)

### Usage
- Run the Jupyter Notebook to explore the dataset and train the model:
- [Linear Regression ML Implementation.ipynb](<Linear Regression ML Implementation.ipynb>)

- Alternatively, run the Python script:
- [regmodel.pkl](https://vscode.com)

### Modeling Approach
The project follows these steps:
- Data Preprocessing: Handling missing values, feature scaling, and encoding categorical variables.
- Exploratory Data Analysis (EDA): Visualizing distributions and correlations between features.
- Model Training:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting
- Hyperparameter Tuning: Using GridSearchCV or RandomizedSearchCV for optimization.

### Evaluation Metrics
The model is evaluated using the following metrics:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared Score (R²)

### Results
- The best-performing model was Random Forest Regressor with an R² score of 0.85
- The model effectively captures the patterns in housing prices. 
- Further improvements can be made with feature engineering and additional data.

### License
- [Apache License, Version 2.0](http://www.apache.org/licenses)

### Software and Tools Requirements
1. [GithubAccount](https://github.com/)
2. [VSCodeIDE](https://vscode.com/)
3. [Heroku](https://heroku.com/)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-the-Command-Line)


#### Make prediction
http://127.0.0.1:5000/

