# ML-Projects

Supervied Learning -> SL
Unsupervised Learning -> USL
_______________________________________________________

- Heart Disease Prediction                 -> SL -> Binary Classification  -> Linear Regression
- Diabetes Prediction                      -> SL -> Binary Classification  -> SVM(linear)
- House Price Prediction                   -> SL -> Regression             -> XGBoost Regressor
- Fake New Prediction                      -> SL -> Binary Classification  -> Logistic Regression (NLP)
- Loan Status Prediction                   -> SL -> Binary Classification  -> SVM(linear)
- Coffee Quality Prediction                -> SL -> Binary Classification  -> (Random Forest)
- Car Price Prediction                     -> SL -> Regression             -> Linear Regression
- Gold Price Prediction                    -> SL -> Regression             -> (Random Forest)
- Credit Card Fraud Detection              -> SL -> Binary Classification  -> Logistic Regression
- Medical Insurance Price Prediction       -> SL -> Regression             -> Linear Regression






## Note:
### Handling categorical values -> OneHot Encodding:

- <pd.get_dummies()> function in pandas
- categorical_cols = dataset.select_dtypes(include=['object']).columns
- dataset_encoded = pd.get_dummies(dataset, columns=categorical_cols)

- <replace()> function
- dataset.replace({'categorical_col':{'N': 0, 'Y': 1}}, inplace=True)

- dataset['categorical_col'] = dataset['categorical_col'].astype('category').cat.codes

