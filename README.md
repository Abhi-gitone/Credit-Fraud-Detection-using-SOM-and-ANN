# Credit-Fraud-Detection-using-SOM-and-ANN
Fraud detection on an unlabeled dataset leveraging both unsupervised and supervised deep learning techniques such as Self Organizing Map (SOM) and Artificial Neural Networks (ANN).

### Overview
Fraud detection is one of the most critical data science tasks performed in the financial services industry. Banks across the world invest heavily in fraud detection algorithms to mitigate the chances of financial losses by preemptively identifying potential avenues for fraud.

### Motivation
Fraud detection using supervised machine learning is a classic data science problem. But there's a caveat: assuming data science does a good job at predicting fraud, how do we get access to enough historical fraud data to train supervised deep learning models for future fraud detection? Hence, the need to use unsupervised learning techniques to label unlabeled data, followed by supervised deep learning, resulting in a robust fraud detection model.

### Data
Credit card applications dataset from the UCI Machine Learning repository.

### Modeling
Self Organizing Maps (SOMs) are used to identify outliers (potential frauds) from the dataset through unsupervised learning. The data is labeled using the results from the SOM and then fed into a Deep Neural Network (fully connected) to create a robust fraud detection algorithm.

## Result
The model achieved an overall accuracy of 0.927 on the test set. More importantly, it achieved a precision score of 0.81, a recall score of 0.90, and an f1 score of 0.85 on the minority class (frauds) in the test dataset.
