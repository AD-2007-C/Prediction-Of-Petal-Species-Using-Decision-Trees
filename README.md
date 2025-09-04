# Prediction-Of-Petal-Species-Using-Decision-Trees
Here we use a decision tree classifier model to predict the flower species having a certain petal length and width. They can either be setosa, vesicular or Virginia.
We train two models:
DecisionTreeClassifier → predicts the species of iris flowers (Setosa, Versicolor, Virginica).
DecisionTreeRegressor → predicts numeric values when treating the labels or features as continuous (for demonstration purposes).

📂 Dataset
Built into scikit-learn (sklearn.datasets.load_iris)
150 samples of iris flowers
Features:
Sepal length (cm)
Sepal width (cm)
Petal length (cm)
Petal width (cm)
Target:
0 = Setosa
1 = Versicolor
2 = Virginica

⚙️ Workflow
Load dataset with sklearn.datasets.load_iris.
Split into train/test sets using train_test_split.
Train a DecisionTreeClassifier with different max_depth values.
Visualize the trained decision tree (Graphviz / matplotlib).
Evaluate with accuracy score.
(Optional) Train a DecisionTreeRegressor for experimentation.

📊 Results
Classifier achieved ~96.66% accuracy on the test set.
Small max_depth (e.g., 2–3) already performs well.
Visualization shows clear separation of Setosa, with more overlap between Versicolor & Virginica.
Example decision tree (depth=3):
