# Supervised Learning

Supervised learning is a type of machine learning where the algorithm learns from labeled data, which consists of input-output pairs. In supervised learning, the algorithm is trained on a dataset where each example is associated with a target or label, which represents the correct output for that input. The goal of supervised learning is to learn a mapping or relationship between input features and output labels so that the algorithm can make accurate predictions on new, unseen data.

Supervised learning algorithms learn from the data, produce a output called hypothesis. To this hypothesis, we can give input and get predictions.

## Types

Supervised learning can be broadly categorized into two main types:

1. **Based on Dataset**
    1. **Regression**:
        - In regression, the *output variable is continuous,* meaning it can take on any value within a certain range.
        - The goal of regression is to predict a continuous target variable based on input features.
        - Examples of regression problems include predicting house prices based on features such as size, number of bedrooms, and location, or predicting the temperature based on weather conditions.
    2. **Classification**:
        - In classification, the *output variable is categorical,* meaning it belongs to a *discrete* set of classes or categories.
        - The goal of classification is to predict the class or category to which a new input belongs.
        - Examples of classification problems include classifying emails as spam or non-spam, identifying whether a tumor is malignant or benign based on medical images, or recognizing handwritten digits in images.
2. **Based on Parameter**
    1. Parametric Learning Algorithm
    2. Non-parametric Learning Algorithm

## Algorithms

Within these two main types, there are various algorithms and techniques that can be used for supervised learning, including:

- **Linear Regression**: A simple regression algorithm that models the relationship between input features and a continuous output variable using a linear equation.
- **Logistic Regression**: A classification algorithm used to model the probability that an input belongs to a particular class.
- **Support Vector Machines (SVM)**: A versatile supervised learning algorithm used for both classification and regression tasks, which finds the optimal hyperplane that separates data points into different classes.
- **K-nearest Neighbors (KNN):** A non-parametric method used for classification and regression tasks, where the output is based on the majority class of its K nearest neighbors.
- **Naive Bayes**: A probabilistic classifier based on Bayes' theorem with an assumption of independence between features.
- **Decision Trees**: A popular algorithm for both regression and classification tasks that models decisions based on a sequence of if-else questions.
- **Random Forests**: An ensemble learning method that combines multiple decision trees to improve predictive performance.
- **Neural Networks**: Deep learning models consisting of interconnected layers of nodes (neurons) that can learn complex patterns from data.
- **Gradient Boosting Machines (GBM)**: An ensemble learning technique that builds a series of decision trees sequentially, with each tree correcting the errors of the previous ones.
- **Ensemble Method:**

Supervised learning is widely used in various real-world applications, such as predictive modeling, image recognition, natural language processing, and recommendation systems. It forms the basis of many machine learning tasks and continues to be a fundamental area of research and development in the field.

## Standard Notations

Consider a dataset where the input is the square-feet area of a home and it’s respective price. Then, following are the notations that is used generally to represent the components of a supervised machine learning model.

$\beta$ = Parameters of a Regression Model (slope)

$n$ = Number of Training Examples (total number of input rows)

$X$ = Input/Feature

$Y$ = Output/Prediction/Target

$(X, Y)$ = Training Examples

$(X^{i}, Y^{i})$ = $i^{th}$ Training Example

[Linear Regression](./supervised-learning/linear-regression.md)
