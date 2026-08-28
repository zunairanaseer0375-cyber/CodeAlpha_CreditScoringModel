# Credit Scoring Model

## Project Overview
This project develops a Machine Learning model to predict credit risk and classify customers based on their creditworthiness. The workflow includes data preprocessing, feature transformation, model training, evaluation, and final model selection.

## Objective
The main objective is to develop a reliable classification model that can help identify customers who are more likely to represent credit risk.

## Machine Learning Models
Three classification algorithms were trained and compared:
* **Logistic Regression**
* **Decision Tree**
* **Random Forest**

The **Random Forest Classifier** was selected as the final model based on its overall performance.

## Data Preprocessing
The dataset was divided into **80% training data** and **20% testing data**.
* **Training data:** 800 samples
* **Testing data:** 200 samples

Numerical features were standardized using **StandardScaler**.  
Categorical features were converted using **OneHotEncoder**.

After preprocessing:
* **Training:** 800 × 61
* **Testing:** 200 × 61

## Model Performance

| Model | Precision | Recall | F1-Score | ROC-AUC |
| :--- | :---: | :---: | :---: | :---: |
| **Logistic Regression** | 0.776 | 0.814 | 0.794 | 0.759 |
| **Decision Tree** | 0.752 | 0.736 | 0.744 | 0.585 |
| **Random Forest** | **0.799** | **0.879** | **0.837** | **0.780** |

## Final Model
**Random Forest Classifier**
* **Precision:** 0.799
* **Recall:** 0.879
* **F1-Score:** 0.837
* **ROC-AUC:** 0.780

## Technologies Used
* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Google Colab**
* **Jupyter Notebook**

## Project File
* **`Credit_Scoring_Model.ipynb`** — Complete data preprocessing, model training, evaluation, and results.

## Conclusion
The **Random Forest** model achieved an **F1-Score of 0.837** and a **ROC-AUC score of 0.780**, making it the final selected model for this credit scoring project.

