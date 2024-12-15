# **Spam Detector**

This challenge is to develop a supervised machine learning model that will accurately detect spam emails so it can filter them out of its customers' inboxes. g techniques.

## **Overview**

Two classsification models were created and compared to identiofy which model is more accurate in detecting spam. The following steps were used:

    Data Processing:
        Create features (X) by dropping the target column 'spam'.
        Assign the target variable (y) from the 'spam' column.
        Split the dataset into training and testing sets using train_test_split.
        Scale the feature data using StandardScaler

    Model Training and Evaluation:
        Logistic Regression Model:
            Train the model using the training set.
            Evaluate its performance on the testing set.

        Random Forest Model:
            Train the model using the training set.
            Evaluate its performance on the testing set.

    Model Comparison:
        The Logistic Regression model achieved an accuracy score of 0.9279.
        The Random Forest model achieved an accuracy score of 0.9670.

## **Findings**

    The Random Forest model proved to be more effective for spam detection due to its ability to handle complex data structures and non-linear relationships present in the dataset.
   
    The Random Forest model outperformed the Logistic Regression model with a higher accuracy score of 0.9670 compared to 0.9279. Despite concerns about potential overfitting due to the Random Forest's near-perfect training score (0.9997), its strong testing accuracy confirmed its reliability.