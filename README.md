# AI & ML Internship — Task 5: Decision Trees and Random Forests

## 📌 Project Overview

This project is part of the **AI & ML Internship — Task 5**, focused on learning tree-based machine learning models for classification.

The project uses a Heart Disease dataset to train and evaluate a Decision Tree Classifier and a Random Forest Classifier using Python and Scikit-learn.

The implementation explores model performance, overfitting, feature importance, decision tree visualization, and cross-validation.

## 🎯 Objectives

- Train a Decision Tree Classifier.
- Visualize the trained decision tree.
- Analyze overfitting by varying the maximum tree depth.
- Train a Random Forest Classifier.
- Compare the performance of both models.
- Interpret Random Forest feature importances.
- Evaluate model performance using five-fold stratified cross-validation.

## 🛠️ Technologies Used

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Git and GitHub

## 📂 Project Structure

```text
AI-ML-Internship-Task-5/
│
├── README.md
├── requirements.txt
├── heart_disease_task5.ipynb
├── task5_decision_trees_random_forest.py
│
├── dataset/
│   └── heart.csv
│
├── outputs/
│   ├── decision_tree_visualization.png
│   ├── tree_depth_overfitting.png
│   ├── model_comparison.csv
│   ├── tree_depth_comparison.csv
│   ├── random_forest_feature_importance.png
│   ├── random_forest_feature_importance.csv
│   ├── cross_validation_results.csv
│   └── confusion_matrices.png
│
└── screenshots/
    └── execution_results.png
```

*Note: The notebook, Python script, dataset, graphs, and screenshots should be added only after they have been created or generated. The exact output filenames may differ depending on your implementation.*

## 📊 Dataset

**Dataset:** Heart Disease Dataset

The dataset contains patient-related attributes used to train a binary or multiclass classifier, depending on the selected dataset version and target encoding.

The commonly used Heart Disease CSV version has a target column named `target`, where 0 represents no disease and 1 represents disease. Verify the target definition for your actual dataset before training.

**Dataset source:** Use the dataset download link provided in the internship task PDF, or another appropriately licensed source.

The dataset file is not included in the internship PDF.

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/AI-ML-Internship-Task-5.git
```

### 2. Open the project directory

```bash
cd AI-ML-Internship-Task-5
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Python script

```bash
python task5_decision_trees_random_forest.py
```

Alternatively, upload the notebook to Google Colab, upload the dataset, and execute the cells in sequence.

## 🧠 Methodology

### 1. Data Preprocessing

- Load the Heart Disease CSV dataset.
- Inspect the dataset structure and target distribution.
- Handle missing feature values.
- Encode categorical variables where required.
- Split the dataset into training and testing sets using an 80:20 ratio.

### 2. Decision Tree Classification

Train a Decision Tree Classifier using Scikit-learn.

The model learns feature-based decision rules to classify observations into target classes.

A tree visualization is generated to help interpret the learned decision rules.

### 3. Overfitting Analysis

Train decision trees with different maximum depths.

Compare training accuracy and testing accuracy to examine how tree complexity affects generalization.

Tree depth and minimum leaf size can be controlled to reduce overfitting.

### 4. Random Forest Classification

Train a Random Forest Classifier using multiple decision trees.

Random Forest combines predictions from an ensemble of trees and can reduce the variance associated with an individual decision tree.

### 5. Model Evaluation

Evaluate the models using:

- Accuracy
- Weighted precision
- Weighted recall
- Weighted F1-score
- Confusion matrix
- Five-fold stratified cross-validation

### 6. Feature Importance

Analyze Random Forest feature importance to identify which input features contributed most to the model's split decisions.

Feature importance indicates predictive contribution, not causation.

## 📈 Results and Analysis

The project generates evaluation tables and visualizations for comparing the Decision Tree and Random Forest models.

| Evaluation | Purpose |
|---|---|
| Accuracy | Measures the proportion of correct predictions |
| Precision | Measures the proportion of predicted positives that are correct |
| Recall | Measures the proportion of actual positives correctly identified |
| F1-score | Combines precision and recall |
| Confusion matrix | Summarizes correct and incorrect classifications |
| Cross-validation | Evaluates performance across multiple data splits |
| Feature importance | Ranks features by their contribution to model splits |
| Depth analysis | Examines the effect of tree complexity on overfitting |

**Actual results:** Add the measured model scores and observations after running the notebook or Python script. Results depend on the dataset version, target encoding, and model configuration.

## 💡 Key Learnings

- Understanding decision tree classification.
- Understanding Random Forest ensemble learning.
- Identifying overfitting in tree-based models.
- Visualizing and interpreting decision trees.
- Comparing machine learning models using evaluation metrics.
- Applying stratified cross-validation.
- Interpreting feature importance.

## 🎤 Interview Questions Covered

1. How does a decision tree work?
2. What are entropy and information gain?
3. How is Random Forest better than a single decision tree?
4. What is overfitting, and how can it be prevented?
5. What is bagging?
6. How can a decision tree be visualized?
7. How can feature importance be interpreted?
8. What are the advantages and disadvantages of Random Forests?

## 🚀 Future Improvements

- Compare additional classification algorithms.
- Tune model hyperparameters using GridSearchCV or RandomizedSearchCV.
- Evaluate ROC-AUC and precision-recall performance.
- Compare impurity-based and permutation-based feature importance.
- Add a simple demonstration interface for model predictions.

## 📁 Deliverables

- Python source code or Google Colab notebook.
- Dataset, where redistribution is permitted.
- Decision tree visualization.
- Overfitting analysis graph.
- Model comparison results.
- Confusion matrices.
- Feature importance analysis.
- Execution screenshots.
- Project documentation.

## ⚠️ Disclaimer

This project is intended for educational purposes only. The model is not a validated medical diagnostic system and must not be used to make clinical decisions.

## 👨‍💻 Author

**Vivek Vardhan**


GitHub: [VivekVardhanGubbala](https://github.com/VivekVardhanGubbala)

---

⭐ If you find this project useful, consider starring the repository.
