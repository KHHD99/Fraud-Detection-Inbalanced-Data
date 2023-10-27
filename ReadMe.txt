# Inbalanced data web app deployed on Heroku
Fraud detection (classification task) in a context of inbalanced data using Credit card dataset -Unbalanced dataset-.  

The deployed web app is live at ([Link](https://khhd-unbalanced-data-dep-corrected.streamlit.app/))

This web application predicts the class of a bank transaction as fraudulent or legitimate, using 4 algorithms (LogisticRegression, DecisionTreeClassifier, RandomForestClassifier, XGBClassifier), and different resampling methods to deal with the imbalance problem. A cost-sensitive method is used to improve the algorithms in order to reduce the number of false classifications (false positives, false negatives).

The web application was built in Python using the following libraries:

  - streamlit
  - matplotlib
  - numpy
  - scikit-learn
  - pickleshare
  - bz2file
  - matplotlib
  - imbalanced-learn
  - XGBoost
