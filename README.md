# Credit-card
Credit Card Default Prediction Using Machine Learning
Project Overview
This project applies machine learning classification techniques to
predict whether a credit card customer will default on their payment.
The workflow includes data exploration, preprocessing, feature
selection, model training, and performance evaluation.
Project Objective
The objective is to build and compare classification models that
identify customers who may default on their credit card payments.
Dataset
The project uses a credit card default dataset.

Place the dataset in the project folder and ensure that the file path in
the notebook matches its actual filename.
- Target variable: Default status (binary classification: default
  / no default)
- Problem type: Supervised machine learning -- binary
  classification
The exact dataset filename and target-column name should be checked
against the notebook before publishing this README.
Project Workflow
1. Import the required Python libraries.
2. Load and inspect the dataset.
3. Explore descriptive statistics and the target distribution.
4. Check and handle missing values.
5. Identify and remove duplicate records.
6. Detect and handle numerical outliers using the IQR method, where
   appropriate.
7. Separate input features (X) and the target variable (y).
8. Split the dataset into training and testing sets.
9. Preprocess numerical and categorical features as required.
10. Apply feature selection, if included in the notebook.
11. Train classification models.
12. Evaluate and compare model performance.
13. Visualise relevant results, such as feature relationships and a
    confusion matrix, if included.
Machine Learning Models
The notebook may include some or all of the following classification
algorithms:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
Evaluation Metrics
- Accuracy: Percentage of total predictions that are correct.
- Precision: How many predicted default cases are actually
  defaults.
- Recall: How many actual default cases the model correctly
  identifies.
- F1-score: Harmonic mean of precision and recall.
- ROC-AUC: Measures how well the model distinguishes between the
  two classes.
- Confusion Matrix: Shows correct and incorrect predictions for
  each class.
Only report metrics that are actually calculated in the notebook.
Technologies and Libraries
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
How to Run the Project
1. Place the dataset in the project folder.
2. Open the Jupyter Notebook.
3. Check that the dataset path and target-column name match your file.
4. Run the notebook cells in order, starting from data loading.
5. Review the visualisations, model comparison table, and evaluation
   results.
Project Structure
Credit-Card-Default-Prediction/
├── credit_card_default.csv   # Replace with your actual dataset filename
├── credit_card_default.ipynb # Replace with your actual notebook filename
└── README.md
Notes
- This README is a general project description. Confirm the exact
  dataset filename, target-column name, models, and preprocessing
  steps against your notebook before publishing.
- Do not report model performance values unless they have been
  produced by running the notebook.
- This project is for educational and analytical purposes and is not a
  standalone credit decision system.
