# decision-tree-classifier
Python implementation of a decision tree to predict income brackets (Adult dataset).

##Overview
This project implements a machine learning classifier based on decision trees, coded entirely from scratch in Python using a Jupyter Notebook. The classifier is trained and evaluated using a modified version of the Adult dataset.

##Files
decision_tree_classifier.ipynb — Jupyter Notebook containing all code, results, and discussion.

decision_tree_classifier.html — HTML export of the notebook with code outputs.

adult_train_data.csv — Training dataset.

adult_test_data.csv — Test dataset.

adult_data_description.txt — Description of the dataset columns.

##Dataset
The dataset includes 12 input features related to demographic and employment attributes. The target label is the "income_more50K" column, indicating whether an individual's income exceeds $50,000. All categorical features have been preprocessed in the provided data files.

##Tasks
###Task 1: Coding
A. Implement a basic decision tree training procedure that recursively splits data based on the information gain criterion until leaves contain only one class.

B. Implement tree depth control by introducing a stopping_depth parameter to limit the depth of the tree. Evaluate and discuss model output at different depths (2, 3, 4).

C. Implement a test procedure that uses the trained decision tree to make predictions on the test data. Evaluate predictions using at least one standard classification metric.

###Task 2: Reflection
Discuss how changing the splitting criterion would affect the decision tree structure and performance.

Reflect on whether the test procedure can indicate if the model is overfitting or underfitting.

##Submission Format
The submission includes:

The raw Jupyter Notebook (.ipynb)

An HTML export of the notebook (.html)

All work is original and reproducible. Parameters are defined and random seeds are set to ensure consistent results.

##How to Run
Place adult_train_data.csv and adult_test_data.csv in the same directory as the notebook.

Open decision_tree_classifier.ipynb in Jupyter Lab or Jupyter Notebook.

Run all cells in sequence.

Review results and explanations, which are fully included in the HTML export.

##Author
Julie Bongartz
Computer Science Student, The University of Auckland


