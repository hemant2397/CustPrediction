# CustPrediction
 The aim of bank is to predict which customers will make a specific transaction in the future that means given particular features of customers we have to determine whether this customer will make a transaction or not

Conclusion
We have an anonymized dataset of 200,000 data points with 202 features in which 200 features are numerical
The dataset is highly imbalanced, which means that there are many more data points for one class than for the other class. This can make it difficult to train a model that can accurately predict the minority class.
There are no missing values in the dataset, which is good. Missing values can make it difficult to train a model and can introduce bias.
There are a small number of outliers in the dataset. Outliers are data points that are significantly different from the rest of the data. They can also make it difficult to train a model and can introduce bias.
There is very low correlation between the features. This means that the features are not very related to each other. This can make it difficult to train a model that can accurately predict the target variable.
The best model without any feature engineering is Naive Bayes. This is a simple model that is often used for classification problems with imbalanced datasets.
The best model with hyperparameter tuning is logistic regression. This is a more complex model that can be more accurate than Naive Bayes.
Overall, the dataset is challenging to work with due to the high imbalance and low correlation between the features. However, the logistic regression model with hyperparameter tuning was able to achieve the best results.

Task 5: Challenges Faced and Techniques Used Report
challenges_report = """ Challenges Faced and Techniques Used Report:

Challenges Faced:

Anonymized Features: The dataset contains anonymized features, making it challenging to interpret the meaning of each feature. As a result, we cannot perform extensive exploratory data analysis (EDA) to understand feature relationships.

Imbalanced Data: The distribution of target classes shows an imbalance, with significantly more instances of one class compared to the other. This imbalance may lead to biased model training and evaluation. We addressed this issue by using appropriate evaluation metrics like precision, recall, and F1-score, which consider both true positive and false positive rates.

Model Selection: With 200 features in the dataset, selecting the appropriate model and hyperparameters can be time-consuming and computationally intensive. We used a variety of classifiers to find the best-performing model.

Techniques Used:

Data Scaling: We applied standard scaling to the features to ensure that all features have a similar range and do not dominate the model training process.

Model Evaluation Metrics: Instead of solely relying on accuracy, we used precision, recall, and F1-score to assess the models' performance, especially in the context of imbalanced data.

Train-Test Split: We split the data into training and testing sets to evaluate the models' generalization performance and avoid overfitting.

Overall, by addressing the challenges and using appropriate techniques, we have developed a predictive model to identify customers likely to make transactions in the future.**
