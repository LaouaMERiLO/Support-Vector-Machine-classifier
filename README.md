# Support-Vector-Machine-classifier
This is a implementation of a Support Vector Machine (SVM) classifier for binary classification.

# Dataset 
The dataset consists of 150 samples with two features each. It was generated using the `make_blobs` function, creating two well-separated clusters representing two different classes. The labels are converted to -1 and 1 to be suitable for SVM classification.

# Implementation
The SVM class is implemented in the code, with the following parameters:

- `learning_rate`: Learning rate for the optimization algorithm (default: 0.001).
- `C`: Regularization parameter (default: 0.1) to control the trade-off between maximizing the margin and minimizing the         classification error of the Support Vector Machine (SVM) classifier
- `lambda_param`: Parameter controlling the regularization of the weights (default: 0.001).

