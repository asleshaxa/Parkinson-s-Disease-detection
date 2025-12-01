

---

# Parkinson’s Disease Detection 

A lightweight ML project that uses a Support Vector Machine (SVM) classifier to predict whether a person is likely to have Parkinson’s Disease based on vocal biomarkers from the Parkinson’s dataset.

---

## **Steps**

* Load dataset using Pandas
* Perform basic EDA (shape, null values, summary stats, class distribution)
* Drop irrelevant columns and preprocess data
* Split data into train & test sets
* Apply StandardScaler for feature scaling
* Train SVM model (RBF kernel)
* Evaluate using:

  * Accuracy
  * Confusion Matrix
  * Classification metrics

---

## **Tech Stack**

* Python
* NumPy
* Pandas
* Scikit-learn
* Matplotlib / Seaborn

---

## **Results**

The SVM model achieves strong accuracy and clearly distinguishes between healthy and Parkinson’s-positive samples.

---

## **Future Scope**

* Hyperparameter tuning (GridSearchCV)
* Try other models like Logistic Regression, Random Forest, XGBoost
* Build a Streamlit or Flask interface for live predictions


---

