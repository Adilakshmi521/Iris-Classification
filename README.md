# Iris Flower Classification Using Machine Learning

## Project Overview
This project demonstrates a machine learning classification workflow using the Iris dataset. It predicts the species of Iris flowers based on their measurements.

The three flower species are:
- Setosa
- Versicolor
- Virginica

## Dataset Information
- Total records: 150
- Input features: 4
- Target classes: 3
- Dataset source: Scikit-learn built-in Iris dataset

## Technologies Used
- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## Project Workflow
1. Load the Iris dataset.
2. Perform Exploratory Data Analysis (EDA).
3. Check missing values and duplicate records.
4. Visualize the dataset using:
   - Scatter Plot
   - Box Plot
   - Histogram
   - Pair Plot
5. Split the dataset into training and testing data.
6. Train a Logistic Regression model.
7. Evaluate model accuracy and classification report.
8. Train a Random Forest Classifier.
9. Compare both machine learning models.
10. Create a confusion matrix.
11. Save the best-performing model as iris_model.pkl.

## Machine Learning Algorithms
- Logistic Regression
- Random Forest Classifier

## Model Evaluation
The models are evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

The best model is selected based on test accuracy.

## Project Files
- Iris_Classification.ipynb – Complete Python notebook containing code, analysis, visualizations, model training, and evaluation.
- iris_model.pkl – Saved trained machine learning model.
- README.md – Project documentation.
- requirements.txt – Required Python libraries.

## Installation and Usage

Install the required libraries:

bash
pip install -r requirements.txt


Open Iris_Classification.ipynb using Google Colab or Jupyter Notebook and run the cells from top to bottom.

## Conclusion
This project demonstrates the complete machine learning classification process, including data preprocessing, visualization, model training, evaluation, comparison, and model saving.
