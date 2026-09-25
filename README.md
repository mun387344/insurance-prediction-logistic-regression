# Insurance Purchase Prediction Using Logistic Regression

## 📌 Project Overview

This is a beginner machine learning project that uses **Logistic Regression** to predict whether a person will buy insurance based on their age.

The project demonstrates a basic machine learning workflow using Python and Scikit-learn, including data loading, visualization, train-test splitting, model training, prediction, and evaluation.

## 🎯 Objective

The main question explored in this project is:

**Can a person's age be used to predict whether they will buy insurance?**

The target variable has two possible outcomes:

- `0` → Did not buy insurance
- `1` → Bought insurance

Because the target represents two classes, Logistic Regression is used as the classification model.

## 🛠️ Tools & Libraries

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab / Jupyter Notebook

## 📊 Project Workflow

The project follows these steps:

1. Load the insurance dataset using Pandas
2. Explore the dataset
3. Visualize the relationship between age and insurance purchase
4. Split the data into training and testing sets
5. Create a Logistic Regression model
6. Train the model using the training data
7. Make predictions on the test data
8. Evaluate the model using accuracy
9. Examine prediction probabilities
10. Make a prediction for a new age value

## 🤖 Model

The model is trained using:

```python
model = LogisticRegression()
model.fit(X_train, y_train)
```

💡 What I Learned

Through this project, I practiced:

Understanding a binary classification problem
Preparing features and a target variable
Splitting data into training and testing sets
Training a Logistic Regression model
Making predictions with a trained model
Evaluating model accuracy
Understanding predicted probabilities
Using Scikit-learn for a basic machine learning workflow
🚀 Next Steps

As I continue learning machine learning, I plan to explore more classification models, additional evaluation metrics, and projects with multiple input features.

👩‍💻 Author

Muna Mohammed
