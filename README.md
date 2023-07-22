# Restaurant Review Sentiment Analysis

This project aims to analyze restaurant reviews and predict whether they are positive or negative using different machine learning models. The models utilized in this project are:

- Support Vector Machine
- Multinomial Naive Bayes
- Bernoulli Naive Bayes
- Logistic Regression

  
The accuracy, precision, and recall metrics are calculated for each model and are then compared to determine the most effective one for this sentiment analysis task.

<ins>Tkinter Front-End </ins>-

The project includes a front-end built using Tkinter, the standard GUI library for Python. This Tkinter interface allows users to interact with the models easily.

The front-end interface will present a text input field where users can enter their review. By clicking on the submit button, users can see predictions for all models for the sentiment of the review (positive or negative). Using the radio buttons on the right side, you can also access the accuracy, precision, and recall metrics for each model.

<ins>Models Used </ins>-
1. Support Vector Machine (SVM)- 
It is a powerful supervised learning algorithm used for classification tasks.

2. Multinomial Naive Bayes- 
It is a probabilistic classifier based on the Bayes theorem. It is commonly used for text classification tasks.

3. Bernoulli Naive Bayes- 
It is another variant of the Naive Bayes algorithm that is suitable for binary feature data.

4. Logistic Regression- 
It is a linear classifier that is widely used for binary classification problems.

<ins>Results </ins>-

After training the models on the provided dataset, the following results were obtained:

Using Support Vector Machine (SVM)
- Accuracy: 77.22%
- Precision: 80.2%
- Recall: 79.41%

Using Multinomial Naive Bayes
- Accuracy: 78.89%
- Precision: 81.37%
- Recall: 81.37%

Using Bernoulli Naive Bayes
- Accuracy: 76.11%
- Precision: 75.21%
- Recall: 86.27%

Using Logistic Regression
- Accuracy: 77.78%
- Precision: 78.7%
- Recall: 83.33%

The results demonstrate that the Multinomial Naive Bayes model achieved the highest accuracy and precision among the four models. However, depending on specific use cases, other models may be more suitable.
