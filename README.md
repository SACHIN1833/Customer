
# 🧠 Ad. Sale Prediction from Existing Customers - Logistic Regression

This project focuses on predicting whether a customer will purchase a product after seeing a digital advertisement. Using **Logistic Regression**, the model analyzes customer data and predicts purchase decisions based on features like age, estimated salary, and ad exposure.

---

## 📂 Dataset
- **File:** `DigitalAd_dataset.csv`  
- Contains customer demographic information and whether they made a purchase after viewing an ad.  
- Example features:
  - `Age` – Age of the customer
  - `EstimatedSalary` – Customer’s estimated income
  - `Purchased` – Target variable (1 = Purchased, 0 = Not Purchased)

---

## 🛠️ Technologies & Libraries
- Python 3.x  
- [pandas](https://pandas.pydata.org/) – Data loading & manipulation  
- [numpy](https://numpy.org/) – Numerical computations  
- [matplotlib](https://matplotlib.org/) – Data visualization  
- [seaborn](https://seaborn.pydata.org/) – Enhanced visualizations  
- [scikit-learn](https://scikit-learn.org/stable/) – Machine learning (Logistic Regression, train-test split, accuracy score)

---

## 📊 Project Workflow
1. **Import Libraries** – Load required packages.  
2. **Load Dataset** – Read `DigitalAd_dataset.csv` into a pandas DataFrame.  
3. **Exploratory Data Analysis (EDA)**  
   - Check dataset shape & preview data  
   - Visualize distributions & relationships  
4. **Data Preprocessing**  
   - Split dataset into train/test sets  
   - Feature scaling (if required)  
5. **Model Training**  
   - Apply **Logistic Regression**  
   - Train on training set  
6. **Model Evaluation**  
   - Predict on test set  
   - Calculate accuracy score & confusion matrix  
   - Visualize decision boundaries  

---
