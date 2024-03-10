# Iris Classification
# Stages Involved
# Data Loading and Initial Exploration:

The code starts by loading the Iris dataset from a CSV file into a Pandas DataFrame (df).
It drops the 'Id' column, as it seems to be an identifier and not relevant for analysis.
Descriptive statistics and general information about the dataset are displayed.
# Data Visualization:

Histograms are plotted for each feature ('SepalLengthCm', 'SepalWidthCm', 'PetalLengthCm', 'PetalWidthCm') to visualize the distribution of data.

Scatter plots are created to visualize relationships between different pairs of features, colored by species ('Iris-virginica', 'Iris-versicolor', 'Iris-setosa').

# Correlation Analysis:

The code calculates and displays the correlation matrix for numerical features.
A heatmap is plotted to visualize the correlations between features.
# Data Preprocessing:

Label encoding is applied to the 'Species' column to convert categorical labels into numerical format for model training.
# Model Training and Evaluation:

The dataset is split into training and testing sets using the train_test_split function.

Three different classification models are trained and evaluated:

Logistic Regression: Achieves accuracy of {Accuracy}.
K-Nearest Neighbors (KNN): Achieves accuracy of {Accuracy}.
Decision Tree Classifier: Achieves accuracy of {Accuracy}.
