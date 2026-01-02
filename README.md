# IRIS-PREDICTION-USING-SVM-AND-HYPERPARAMETER-TUNNING-\
🌸 Iris Flower Classification using Machine Learning
📌 Project Overview

This project focuses on building a machine learning classification model using the Iris dataset.
The goal is to predict the species of an iris flower based on its physical features.

📊 Dataset Information

Dataset Name: Iris Dataset

Number of Samples: 150

Features:

Sepal Length

Sepal Width

Petal Length

Petal Width

Target Variable: Species (Setosa, Versicolor, Virginica)

🧠 Approach Used
1️⃣ Data Loading & Exploration

Loaded dataset using Pandas

Checked basic statistics and data distribution

Visualized correlations using a heatmap

2️⃣ Outlier Handling

Identified outliers in sepal_width using the IQR method

Applied capping (winsorization) instead of removing data

3️⃣ Data Preprocessing

Separated features (X) and target (y)

Used train-test split with stratification

Applied StandardScaler for feature scaling

4️⃣ Model Building

Used Support Vector Machine (SVM) classifier

Applied Pipeline to avoid data leakage

5️⃣ Hyperparameter Tuning

Used GridSearchCV to tune:

C

gamma

kernel

Performed cross-validation for reliable results

6️⃣ Model Evaluation

Evaluated model using accuracy score

Achieved ~95% accuracy on test data

🛠️ Technologies & Libraries Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

📈 Results

Final Model: SVM with RBF kernel

Test Accuracy: ~95%

Model is well-generalized with no data leakage

📂 Project Structure
├── iris_dataset.csv
├── model_training.ipynb
├── README.md

🚀 Future Improvements

Try other models like Random Forest or Logistic Regression

Deploy the model using Streamlit

Add confusion matrix and classification report

Perform feature selection

📌 Key Learnings

Importance of handling outliers correctly

Avoiding data leakage using pipelines

Hyperparameter tuning with GridSearchCV

Building reliable and production-ready ML models

👤 Author

Dev Sah
Aspiring Data Scientist | Machine Learning Enthusiast
