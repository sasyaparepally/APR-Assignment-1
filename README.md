# APR-Assignment-1

# Naive Bayes Classifier on Iris Dataset

This project demonstrates how to apply the **Gaussian Naive Bayes classifier** on the classic **Iris dataset** using Python and scikit-learn.  
It includes data visualization, model training, evaluation, and feature analysis.

---

## 📂 Project Structure
- `APR_assignment1.ipynb` → Main script (training + evaluation + plots)
- `README.md` → Documentation

---

## 📊 Dataset
We use the built-in **Iris dataset** from scikit-learn, which contains 150 flower samples with 4 features each:

- `sepal length (cm)`
- `sepal width (cm)`
- `petal length (cm)`
- `petal width (cm)`

Target classes:
- **Setosa**
- **Versicolor**
- **Virginica**

---

## ⚙️ Steps in Code
1. **Load dataset**  
   - Download Iris dataset using `sklearn.datasets.load_iris`.  
   - Print column names for clarity.

2. **Split dataset**  
   - Training (70%) and Testing (30%) split using `train_test_split`.

3. **Train model**  
   - Train a `GaussianNB` classifier.

4. **Evaluate model**  
   - Accuracy score  
   - Confusion Matrix  
   - Classification Report

5. **Visualizations**  
   - Pairplot of features by class  
   - Confusion matrix heatmap  
   - Feature means & variances per class  
