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


Understanding the terms of a decision tree, especially one created using Scikit-learn's DecisionTreeClassifier, is crucial for interpreting the tree's decision-making proces:

1. *Gini*</br>
The Gini impurity is a measure of how often a randomly chosen element from the set would be incorrectly labeled if it was randomly labeled according to the distribution of labels in the subset.</br>
The Gini impurity ranges from 0 to 0.5, where 0 indicates that all elements in the subset belong to the same class (perfect purity), and 0.5 means the data is randomly distributed across various classes.
In decision trees, a lower Gini impurity is generally preferred as it indicates greater purity of the node.</br>

2. *Samples*</br>
This value represents the number of samples (or records) that reach the node.
It gives an idea of how much of the training data is affected by the conditions leading to this node.
A high number of samples in a node means that the condition or rule associated with that node is relevant for a significant portion of the dataset.</br>

3. *Value*</br>
This shows the distribution of the samples in different classes at that particular node.
For a binary classification problem (like churn prediction with 'Yes' or 'No'), the value is presented as a list of two numbers. The first number indicates the count of samples in the first class, and the second number indicates the count of samples in the second class.
This distribution helps in understanding which class is predominant at a particular node.</br>

4. *Class*</br>
This indicates the class that would be predicted if the decision tree traversal ends at that node.
It is determined based on the majority class of the samples that reach the node. For instance, if most samples at a node belong to the 'No Churn' class, the node will predict 'No Churn'.</br>

5. *Feature Name (e.g., 'Monthly Charge')*</br>
This is not a standard part of the decision tree node description, but it may appear in the tree's branches.
It represents the feature (or attribute) used to split the data at that node.
For example, if you see "MonthlyCharge <= 80", it means that the tree is splitting the data at this node based on whether the monthly charge is less than or equal to 80.</br>
</br>

Understanding these components is essential for interpreting how the decision tree makes its predictions and which features are influential in the decision-making process. This can provide valuable insights, especially in business contexts like customer churn prediction.
