# Exploring imbalanced dataset with Sampling Techniques

**This project focuses on exploring an imbalanced dataset of creditcard info**

### Prerequisites:
-  Python (version>=3.x)
-  Jupyter Notebook
-  Libraries: pandas, scikit-learn, numpy, imbalanced-learn

### Sampling Techniques
- Apply Various sampling techniques to address class imbalance:
1.  Oversampling:
    -   Random Oversampling: balance the class distribution by randomly duplicating the instances of the minority class
    -   SMOTE: Generates synthetic samples by focusing on the minority samples
2.  Undersampling:
    -   Random Undersampling: balance the class distribution by randomly duplicating the instances of the majority class
    -   Tomek Links: Identifies and remove instances that are considered ambiguous or near the decision boundary between classes
    -   Near miss: Identifies instances which are close to instances from minority class, aiming to retain the instances that are more difficult to classify correctly


### Models on which evaluation is done:
- Evaluate different models on the imbalanced dataset with different sampling
- **RandomForest**
- **XGBoost**
- **LGBM**
- **SVC**
- **CatBoost**

### Result:
-  On comparison of different models and their corresponding sampling techniques TomekLinks undersampling technique gave us the best results on different models.
-  Note: Data can be preprocessed and explored further and metrics might come out different
