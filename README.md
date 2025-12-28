# 🌳 Decision Tree Multiclass Classification

##  Project Overview
This project demonstrates the implementation of a **Decision Tree Classifier** for solving a **multiclass classification problem** using Python and Scikit-Learn.  
The goal is to train a machine learning model that can accurately classify data into multiple categories and evaluate its performance using appropriate classification metrics.

---

##  Algorithm Used
- **Decision Tree Classifier**
- Splitting Criteria:
  - Gini Index (default)
  - Entropy (tested for comparison)

---

##  Technologies & Libraries
- Python
- NumPy
- Pandas
- Matplotlib / Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## 📂 Dataset
- The dataset contains multiple input features and a **multiclass target variable**
- Categorical features were encoded using **Label Encoding**
- Data was split into **training and testing sets**

---

## Project Workflow
1. Import required libraries  
2. Load and explore the dataset  
3. Handle missing values (if any)  
4. Encode categorical variables  
5. Split data into training and testing sets  
6. Train Decision Tree Classifier  
7. Tune hyperparameters  
8. Evaluate model performance  

---

## 📊 Model Evaluation Metrics
Since this is a **classification problem**, the following metrics were used:

- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)

---

##  Results
- The Decision Tree model achieved satisfactory accuracy on the test dataset
- Performance varies based on tree depth and splitting criteria
- Overfitting was controlled using hyperparameter tuning

---

##  Improvements & Future Work
- Apply Random Forest or Gradient Boosting
- Perform cross-validation
- Feature selection and scaling
- Hyperparameter tuning using GridSearchCV

---

##  Conclusion
This project successfully demonstrates how Decision Trees can be applied to multiclass classification problems.  
It highlights the importance of choosing correct evaluation metrics and tuning model parameters to achieve better generalization.

---

## 👤 Author
**Ariyan Shaikh**  
BSc IT Graduate  
Machine Learning & Data Analytics Enthusiast
