# MNIST-SGDClassifier-Binary-Classification
This repository contains a machine learning project utilizing a Stochastic Gradient Descent (SGD) classifier for binary classification on the MNIST dataset. The goal is to identify and classify handwritten digits.
**See the Jupyter Notebook file for the complete project**

## Dataset
The MNIST dataset is a popular dataset consisting of 70,000 small images of handwritten digits. Each image is labeled with the digit it represents.

## Model Selection
In this project, binary classification was performed to distinguish between zeros and non-zeros. The SGD classifier was used to perform the binary classification task.

## Performance Evaluation Process


***

**Classification Report**

Generated a report detailing key metrics such as precision, recall, and f1-score for each class.

***

**Precision-Recall Curve**

Plotted a precision-recall curve to visualize the trade-off between precision and recall for different threshold settings.

***

**Confusion Matrix**

Used confusion matrix to visualize the performance of the algorithm by displaying the true positive, false positive, true negative, and false negative predictions.

***

**K-Fold Cross-Validation**

Employed K-Fold Cross-Validation to ensure that our model's performance is not dependent on the way we split the data. This method provides a more robust measure of the model's predictive power.

***

## Usage
- Clone this repository
- Open the `MNISTProject.ipynb` notebook
- See appendix for required packages
- Run the notebook cells
