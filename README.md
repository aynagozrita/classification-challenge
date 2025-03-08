# classification-challenge
## Spam Dataset Analysis Using Logistic Regression and Random Forest Classifier
This challenge involves analyzing a dataset for spam classification using two distinct machine learning models: Logistic Regression and Random Forest Classifier. The dataset is sourced from the UCI Machine Learning Library's Spambase repository.
  • Dataset Location: spam-data.csv
  • Dataset Source: UCI Machine Learning Library
## Objectives
1. Make a prediction regarding which machine learning model (Logistic Regression or Random Forests Classifier) will perform better on the dataset.
2. Create and fit both models.
3. Evaluate the models based on their accuracy scores.
## Methodology
1. Data Preparation:
  • Load the dataset and inspect its structure.
  • Preprocess the data as necessary (Split the Data into Training and Testing Sets, `StandardScaler` to scale the features data).
2. Logistic Regression Model:
  • Create the Logistic Regression model.
  • Fit it to the training data.
  • Make predictions on the test set.
  • Calculate and print the model's accuracy score using a random state of 1.
3. Random Forest Classifier Model:
  • Create the Random Forest Classifier model.
  • Fit it to the training data.
  • Make predictions on the test set.
  • Calculate and print the model's accuracy score using a random state of 1.
## Results
After executing the models, compare their accuracy scores to determine which model performed better:
  • Logistic Regression Model Accuracy: 0.5161 (51.61%)
  • Random Forest Classifier Accuracy: 1.0 (100%)
## Conclusion
The Random Forest Classifier outperformed the Logistic Regression model in terms of accuracy, achieving a perfect score of 100%. However, such high accuracy might indicate overfitting, where the model learns the noise in the training data rather than generalized patterns. 
In contrast, the Logistic Regression model displayed a lower accuracy of 51.61%, suggesting that the data may not be linearly separable, which is a limitation of the Logistic Regression algorithm. 
