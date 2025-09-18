# 🌸 Iris Classification Project

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-1.2.2-orange)
![License](https://img.shields.io/badge/License-MIT-green)

This project demonstrates **machine learning classification** on the **Iris dataset** using **Decision Tree** and **Perceptron** models.  
It includes **data visualization, model evaluation, model comparison**, and saving trained models for future use.  

---

## 📖 Table of Contents
1. [Dataset](#dataset)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Visual Results](#visual-results)
6. [Saved Models](#saved-models)
7. [Author](#author)
8. [License](#license)

---

## 🌼 Dataset

The project uses the classic [Iris dataset](https://archive.ics.uci.edu/ml/datasets/iris) with 150 samples, 4 numerical features, and 3 species labels:

| Feature       | Description                     |
|---------------|---------------------------------|
| sepal_length  | Sepal length in cm               |
| sepal_width   | Sepal width in cm                |
| petal_length  | Petal length in cm               |
| petal_width   | Petal width in cm                |
| species       | Target label: Setosa, Versicolor, Virginica |

---

## 🚀 Features

- Load and inspect dataset using **pandas**  
- Visualize feature relationships with **Seaborn pairplots**  
- Train **Decision Tree** and **Perceptron** classifiers  
- Evaluate models using:  
  - **Accuracy** ✅  
  - **Classification Report** (precision, recall, f1-score) 📝  
  - **Confusion Matrix** 🔢  
- Compare model performance visually with bar plots 📊  
- Save trained models as `.pkl` files for reuse 💾  
- Save plots in `images/` folder for README display  

---

## 🛠 Installation

Clone the repository:

```bash
git clone https://github.com/Raludzingana98/iris-classification.git
cd iris-classification

Install required Python libraries:

pip install pandas scikit-learn matplotlib seaborn joblib

💻 Usage

Run the script:

python iris_classification.py


The script will:

Load and inspect the Iris dataset

Plot pairwise feature relationships

Train Decision Tree and Perceptron models

Print model accuracy and classification reports

Display confusion matrices

Show a comparison bar plot of model accuracies

Save trained models as decision_tree_model.pkl and perceptron_model.pkl

Save plots in the images/ folder for documentation

📊 Visual Results
Pairplot of Dataset Features

Confusion Matrices

Accuracy Comparison

Note: Ensure the images/ folder exists in your repository and your script saves plots using plt.savefig("images/plot_name.png").

💾 Saved Models

decision_tree_model.pkl → Decision Tree classifier

perceptron_model.pkl → Perceptron classifier

Load models in Python:

import joblib

dt_model = joblib.load('decision_tree_model.pkl')
perc_model = joblib.load('perceptron_model.pkl')

👤 Author

Shumani Raludzingana

📧 raludzingana98@gmail.com

LinkedIn

⚖️ License

This project is licensed under the MIT License – see the LICENSE
 file for details.
