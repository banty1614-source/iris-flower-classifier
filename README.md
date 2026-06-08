# 🌸 Iris Flower Classifier

My second machine learning project built using Python and Scikit-learn.

## Project Overview

This project uses the K-Nearest Neighbors (KNN) algorithm to classify iris flowers into one of three species:

* Setosa
* Versicolor
* Virginica

The prediction is made using four flower measurements:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

This project helped me understand how KNN works, how machine learning models are trained and tested, and how classification problems are solved.

---

## Dataset

This project uses the Iris dataset available in Scikit-learn.

The dataset contains:

* 150 flower samples
* 4 input features
* 3 flower species

---

## Machine Learning Concepts Used

* Classification
* Features and Labels
* Train-Test Split
* K-Nearest Neighbors (KNN)
* Model Training
* Prediction
* Accuracy Evaluation

---

## Algorithm Used

### K-Nearest Neighbors (KNN)

KNN predicts the class of a new flower by:

1. Finding the nearest flowers in the dataset
2. Looking at their labels
3. Using majority voting to make the final prediction

For this project:

```python
K = 5
```

---

## Technologies Used

* Python
* Scikit-learn
* NumPy
* Jupyter Notebook
* Anaconda

---

## Project Workflow

```text
Load Dataset
      ↓
Separate Features and Labels
      ↓
Train-Test Split
      ↓
Create KNN Model
      ↓
Train Model
      ↓
Make Predictions
      ↓
Evaluate Accuracy
```

---

## Results

The model achieved approximately:

```text
96% - 100% Accuracy
```

depending on the train-test split.

---

## Example Prediction

Input:

```text
Sepal Length = 5.1
Sepal Width = 3.5
Petal Length = 1.4
Petal Width = 0.2
```

Output:

```text
Setosa
```

---

## What I Learned

Through this project, I learned:

* How KNN works internally
* Why choosing the value of K matters
* The difference between overfitting and underfitting
* How machine learning models make predictions
* How to evaluate classification models using accuracy

---

## Future Improvements

* Experiment with different values of K
* Compare KNN with Decision Trees
* Visualize the dataset using graphs
* Apply KNN to larger datasets

---

## Author

Banty Kumar

Electrical Engineering Undergraduate at NIT Patna

Currently learning Machine Learning and Data Analytics through hands-on projects.

---

This project is part of my machine learning learning journey.
