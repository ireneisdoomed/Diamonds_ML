<img src=https://secure.meetupstatic.com/photos/event/9/2/1/1/600_475297393.jpeg alt="300" width="350"/>

Project framed in the Ironhack data analysis bootcamp.

# Kaggle competitions: Diamonds dataset


Prediction of the price of diamonds based on their characteristics, putting into practice supervised macine learning techniques.

[Diamonds competition](https://www.kaggle.com/c/diamonds-datamad0120/overview/description) (regression problem).



<img src=https://github.com/ireneisdoomed/Diamonds_ML/blob/master/IreneLS_Diamonds.png alt="400" width="700"/>

### Data preparation, feature selection and extraction

 *  Treatment of the categorical variables "cut", "color" and "clarity" following two different approaches:
    - Conversion to numbers by giving them an ordinal encoding.
    - One-hot encoding. Conversion to categorical variables using get_dummies.

* Analysis of correlated variables that contribute to the prediction variable following two different approaches:
    - Dropping highly correlated features: "table", "x", "y", "z".
    - Recursive feature elimination with cross-validation(RFECV). Calculation of model accuracy using Random Forest with the most relevant features.

* Normalization of the numerical features except those resulting from pd.get_dummies (the categorical ones).

### Supervised learning algorithms

* Train-test split to divide the data in X_ train, X_test, y_train, y_test.

* Model building, training and evaluation: Linear Regression, Generalized Additive Model, SVR, Random Forest Regressor, Gradient Boosting Regressor from the Scikit-learn and pygam libraries.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
