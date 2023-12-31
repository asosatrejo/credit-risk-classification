# 📈 Credit Risk Classification
> In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

The instructions for this Challenge are divided into the following subsections:
- Split the Data into Training and Testing Sets
- Create a Logistic Regression Model with the Original Data
- Write a Credit Risk Analysis Report
  
# 📌 Requirements
## 1️⃣ Split the Data into Training and Testing Sets 
- [ ] Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
- [ ] Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
- [ ] Split the data into training and testing datasets by using train_test_split. (15 points)

## 2️⃣ Create a Logistic Regression Model
- [ ] Fit a logistic regression model by using the training data (X_train and y_train).
- [ ] Save the predictions on the testing data labels by using the testing feature data (X_test) and the fitted model.
- [ ] Evaluate the model’s performance by doing the following:
  - [ ] Generate a confusion matrix.
  - [ ] Generate a classification report. (5 points)
  - [ ] Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

## 3️⃣ Write a Credit Risk Analysis Report
- [ ] Provide an overview that explains the purpose of this analysis.
- [ ] Using a bulleted list, describe the accuracy, precision, and recall scores of the machine learning model.
- [ ] Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.

## Coding Conventions and Formatting
- [ ] Place imports at the top of the file, just after any module comments and docstrings and before module globals and constants.
- [ ] Name functions and variables with lowercase characters, with words separated by underscores.
- [ ] Follow DRY (Don’t Repeat Yourself) principles, creating maintainable and reusable code.
- [ ] Use concise logic and creative engineering where possible.

## Code Comments
- [ ] Be well commented with concise, relevant notes that other developers can understand.
