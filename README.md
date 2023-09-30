# Breast-cancer-Prediction

# Project Title: 
 ### *Analysis and Predication of "Breast Cancer Diagnosis Using Logistic Regression" to  classify breast cancer tumors as either malignant or benign with high accuracy*

# Probleam Statement
Breast cancer is a prevalent and potentially life-threatening disease. Early detection is crucial for successful treatment. This project leverages logistic regression and machine learning techniques to predict breast cancer diagnoses based on patient data. The Breast Cancer dataset is used, containing various features extracted from breast cancer biopsies.

The primary goal is to build a predictive model that can classify breast cancer tumors as either malignant or benign with high accuracy. We preprocess the data by splitting it into training and testing sets and standardizing the features to improve model performance. A logistic regression model is trained on the training data to learn the underlying patterns.

The project evaluates the model's performance using metrics such as accuracy, confusion matrix, and a classification report. Accurate breast cancer classification can assist medical professionals in making more informed decisions about patient care and treatment options, potentially saving lives through early diagnosis.

# Project Methodology
In the code example provided for the Breast Cancer dataset, here's how the input (`X`) and output (`y`) are structured:

- **Input (`X`)**:
  - `X` is a Data Frame containing various features extracted from diagnostic images of breast tumors. These features include measurements like radius, texture, perimeter, area, smoothness, and more. Each row in `X` corresponds to a specific tumor, and each column represents a different feature.

- **Output (`y`)**:
  - `y` is a 1D array or list of labels associated with each tumor sample in `X`. These labels indicate whether the tumor is benign (non-cancerous) or malignant (cancerous). It's a binary classification task:
    - `0` corresponds to malignant tumors (cancerous).
    - `1` corresponds to benign tumors (non-cancerous).

The logistic regression model is trained to learn the relationship between these input features (from `X`) and the output labels (from `y`) to make predictions about whether a given tumor is benign or malignant. The model's output is a binary classification prediction, where it predicts whether a tumor is cancerous (`0`) or non-cancerous (`1`) based on the input features.

![image](https://github.com/keshoju-Jagadhish-kumar/Breast-cancer-Prediction/assets/146511718/ef4b2e81-cd80-45f0-8dde-ac435fe6cbf3)

# Project Approched
![image](https://github.com/keshoju-Jagadhish-kumar/Breast-cancer-Prediction/assets/146511718/77540189-0348-42f1-9c9b-42c87ae9a9a1)

# Conclusion
1. From my ML Model I concluded that , It's to predict whether a breast tumor is benign (non-cancerous) or malignant
(cancerous) based on various features extracted from diagnostic..
2. Here's a brief description of the target variable:
Target Variable (y):
0: Malignant (cancerous)
1: Benign (non-cancerous)
3. So, in this dataset, we are predicting the presence or absence of breast cancer (malignant or benign) based on features like
tumor size, texture, perimeter, and other characteristics extracted from medical images. The logistic regression model is
used to classify tumors into one of these two categories.
✨Result / Conclusion

----------------------Thank You! ----------------------------

