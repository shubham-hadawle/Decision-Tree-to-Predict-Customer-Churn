# Decision-Tree-to-Predict-Customer-Churn

**Building a Decision Tree to Predict Customer Churn**
Imagine you are a data analyst at a telecom company. The marketing department has noticed an increase in customer churn and needs your help to identify which customers are most likely to leave next month.

The dataset contains the following columns:

CustomerID: A unique identifier for each customer.</br>
Age: The age of the customer.</br>
MonthlyCharge: The monthly bill amount for the customer.</br>
CustomerServiceCalls: The number of times the customer contacted customer service.</br>
Churn: This is our target variable, indicating whether the customer churned (Yes) or not (No).
</br>
</br>

1. Setup the Environment:
Import necessary libraries: Pandas for data manipulation, Scikit-learn for machine learning, and Matplotlib for visualization.
2. Create the Dataset:
Use Python to create a synthetic dataset. We'll make a small dataset for simplicity.
3. Data Preparation:
Split the data into features (X) and the target variable (y).
Further split the dataset into training and testing sets.
4. Build the Decision Tree Model:
Use Scikit-learn to create a DecisionTreeClassifier.
Train the model on the training data.
5. Evaluate the Model:
Make predictions on the test set.
Calculate the accuracy of the model.
6. Visualize the Decision Tree:
Use Matplotlib to visualize how the decision tree makes decisions.
7. Discuss the Results:
Interpret the decision tree.
Discuss how it can be used by the company to reduce customer churn.
