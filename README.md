
## Credit Risk Classification Challenge ##
# Module 20 #

# Instructions #
The instructions for this Challenge are divided into the following subsections:
  1. Split the Data into Training and Testing Sets
  2. Create a Logistic Regression Model with the Original Data
  3. Write a Credit Risk Analysis Report

# Split the Data into Training and Testing Sets # 
Open the starter code notebook and use it to complete the following steps:
  1. Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
  2. Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
  3. Split the data into training and testing datasets by using train_test_split.
  

# Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:
  1. Fit a logistic regression model by using the training data (X_train and y_train).
  2. Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
  3. Evaluate the model’s performance by doing the following:
        3.a Generate a confusion matrix.
        3.b  Print the classification report.
  
  4. Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?
## Base on the results below indicate the model is highly effective at identifying both healthy and high-risk loans, making it well-suited for credit risk prediction.##
  1. Accuracy: 99%
  2. Precision:
    Healthy loans (0): 1.00
    High-risk loans (1):0.87
   3. Recall:
    Healthy loans (0): 1.00
     High-risk loans (1): 0.95
  4. F1-score:
    Healthy loans (0): 1.00
    High-risk loans (1):0.91


5.  Write a Credit Risk Analysis Report
## The machine learning pipeline included data preprocessing and standardization, splitting the data into training and test sets, training a logistic regression model, and evaluating its performance using classification metrics. 
# The logistic regression model achieved excellent results, with an overall accuracy of 99%. It perfectly classified healthy loans and performed strongly on high-risk loans, despite the imbalance. This high level of accuracy indicates the model is a strong candidate for practical use in identifying risky credit applications, even with slightly reduced performance on the minority class.





