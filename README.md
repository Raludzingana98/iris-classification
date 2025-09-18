Iris Classification Project 🌸

This project demonstrates machine learning classification on the Iris dataset using Decision Tree and Perceptron models. The workflow includes data visualization, model training, evaluation, comparison, and saving trained models for future use.

Dataset

The project uses the classic Iris dataset
 consisting of 150 samples with 4 numerical features and 3 species labels:

Feature	Description
sepal_length	Sepal length in cm
sepal_width	Sepal width in cm
petal_length	Petal length in cm
petal_width	Petal width in cm
species	Target label: Setosa, Versicolor, Virginica
Features

Load and inspect dataset using pandas

Visualize feature relationships with Seaborn pairplots

Train Decision Tree and Perceptron classifiers

Evaluate models using:

Accuracy

Classification Report (precision, recall, f1-score)

Confusion Matrix

Compare model performance visually with bar plots

Save trained models as .pkl files for later use

Installation

Clone the repository:

git clone <your-repo-url>
cd <your-repo-folder>


Install required libraries:

pip install pandas scikit-learn matplotlib seaborn joblib

Usage

Run the Python script:

python iris_classification.py


The script will:

Load and inspect the Iris dataset

Plot pairwise feature relationships

Train Decision Tree and Perceptron models

Print model accuracy and classification reports

Display confusion matrices

Show a comparison bar plot of model accuracies

Save trained models as decision_tree_model.pkl and perceptron_model.pkl

Visual Results
Pairplot of Dataset Features

Confusion Matrices

Accuracy Comparison

Note: Save your generated plots into an images/ folder in your repository before pushing. Use plt.savefig("images/plot_name.png") in your code.

Saved Models

decision_tree_model.pkl → Decision Tree classifier

perceptron_model.pkl → Perceptron classifier

Load models in Python:

import joblib

dt_model = joblib.load('decision_tree_model.pkl')
perc_model = joblib.load('perceptron_model.pkl')

Author

Shumani Raludzingana

📧 raludzingana98@gmail.com

LinkedIn

License

This project is licensed under the MIT License – see the LICENSE
 file for details.
