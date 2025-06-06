# 🌸 Iris Flower Classification using Random Forest 🌸

![iris img1](https://github.com/user-attachments/assets/e2eaa7fb-0258-4a14-99bb-37a1583ecb92)


> This project demonstrates the classification of iris flowers into species using a **Random Forest Classifier**. It is a great beginner-level machine learning project that involves data preprocessing, model training, evaluation, and visualization.

---

## 📌 About the Dataset

The [Iris dataset](https://archive.ics.uci.edu/ml/datasets/iris) is one of the most popular datasets in machine learning. It consists of 150 rows with 4 features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width  

Each sample is labeled with one of the following species:
- Setosa
- Versicolor
- Virginica

---

## 🚀 Project Workflow

1. Load and explore the dataset using `pandas` and `seaborn`.
2. Encode categorical species labels using `LabelEncoder`.
3. Split data into training and testing sets.
4. Train a **Random Forest Classifier**.
5. Evaluate using:
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
6. Visualize feature importance and prediction performance.

---

## 📊 Sample Output

```bash
Model Accuracy: 1.00

Classification Report:
              precision    recall  f1-score   support

           0       1.00      1.00      1.00         9
           1       1.00      1.00      1.00        10
           2       1.00      1.00      1.00        11

    accuracy                           1.00        30
   macro avg       1.00      1.00      1.00        30
weighted avg       1.00      1.00      1.00        30
```
💡 Author:
Vijay Kalyan ❤️
