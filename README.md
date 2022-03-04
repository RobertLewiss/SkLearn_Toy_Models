# SkLearn_Toy_Models

This notebook contains several toy models using scikit-lear Package. The focus of this notebook it to try out the processing/validation/testing/post analysis methods SKLearn rovides. The data used and the results of the models are not the focus. 

In this Notebook I utilise:
  - Preprocessing methods:
    - One hot encoding
    - PCA
    - imputation methods
    - scaling
    - transformations of skewed features
    - Under and Over sampling (+ stratified methods)
    - Cardinality reduction
    - Feature selection (See below)

  - Feature selection:
    - Correlation analysis
    - Variance analysis
    - Maximal Independent set analysis (Via NetworkX Package)
    - Feature Importance ( Several methods such as Sequential feature selection and simple tree-based selection)
    - Missing value analysis (were I decide to drop or impute features given some prior knowledge on the source of the data)
 
  - Models:
    - Only Tree based models were used, Notebook focuses on how to handle the data before and after the models. This notebook is not focussed on the models themselfs.

  - Validation and post training methods:
    - Hyperparameter tuning (GridSearchCV)
    - Learning and validation curves
    - ROC Curve
    - Lift Charts
    - Threshold tuning (precision and recall curve)
    - Probability Calibration
    - Partial Dependence Plots
    - Permutation test scores.

 
