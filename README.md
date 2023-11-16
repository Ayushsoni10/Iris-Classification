# Iris Classification

This project is a machine learning application that classifies iris flowers into three species: setosa, versicolor, and virginica. The project uses the iris dataset from the UCI Machine Learning Repository, which contains 150 samples of iris flowers with four features: sepal length, sepal width, petal length, and petal width. The project also uses the scikit-learn library to implement a k-nearest neighbors classifier that predicts the species of a new iris flower based on its features.

## Installation

To run this project, you need to have Python 3.6 or higher installed on your system. You also need to install the following packages:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

You can install these packages using pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Usage

To run this project, you need to execute the `iris_classification.py` file in your terminal:

```bash
python iris_classification.py
```

The program will load the iris dataset, split it into training and testing sets, train the k-nearest neighbors classifier, and evaluate its performance on the testing set. The program will also plot the decision boundaries of the classifier and the distribution of the features for each species. The program will output the following information:

- The accuracy score of the classifier on the testing set
- The confusion matrix of the classifier on the testing set
- The classification report of the classifier on the testing set
- The plots of the decision boundaries and the feature distributions

## Example

Here is an example of the output of the program:

```
Accuracy score: 0.9736842105263158
Confusion matrix:
[[13  0  0]
 [ 0 15  1]
 [ 0  0  9]]
Classification report:
              precision    recall  f1-score   support

      setosa       1.00      1.00      1.00        13
  versicolor       1.00      0.94      0.97        16
   virginica       0.90      1.00      0.95         9

    accuracy                           0.97        38
   macro avg       0.97      0.98      0.97        38
weighted avg       0.98      0.97      0.97        38
```

