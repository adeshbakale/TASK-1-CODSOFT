# TASK-1-CODSOFT
Project goal:
Create a model that, based on the information provided, will predict whether the passengers of the Titanic survived.

#dataset:
The data comes from a CSV file called "archive.zip". Includes details like survival, class, gender and age.

Key Libraries:
Libraries used: numpy, pandas, matplotlib.pyplot, seaborn, sklearn.preprocessing.LabelEncoder, sklearn.model_selection.train_test_split, sklearn.linear_model.LogisticRegression.

#steps:

1)Loaded the data using pandas, checked its size and previewed the first 10 rows.
2)Explore the numeric data with df.describe() to understand the dataset.
3)Visualized survival counts and class distributions using seaborn.
4)Sex-specific survival examined using census and sex-specific survival rates calculated.
5)Using LabelEncoder, the "Gender" column was converted to numbers and unnecessary columns were removed.
6)Created X (features) and Y (goal) for training.
7)Split the data into training and test sets.
8)Trained a logistic regression model on the training data.
9)Used the model to predict survival for test data.
Controlled predicted and actual results.
Sample forecast:
For class P=2 and male (1), the model predicts survival status.
