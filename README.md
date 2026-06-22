__ML Classification Project__

Project Title: Breast Cancer Classification using Machine Learning

Objective: The objective of this project is to build and evaluate supervised machine learning classification models to predict whether a breast cancer tumor is malignant or benign. The project includes data preprocessing, train-test splitting, cross-validation, model training, and performance evaluation.

Dataset :

The Breast Cancer Wisconsin Dataset is used from the Scikit-learn library.

* Total Samples: 569
* Features: 30
* Target Classes:

  * Malignant (Cancerous)
  * Benign (Non-Cancerous)

Technologies Used :

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

Machine Learning Algorithms :

1. Logistic Regression
2. Random Forest Classifier

Evaluation Metrics :

The following metrics were used to evaluate model performance:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score

Project Workflow :

1. Import required libraries.
2. Load the dataset.
3. Perform data preprocessing.
4. Check for missing values.
5. Split the dataset into training and testing sets.
6. Train Logistic Regression model.
7. Train Random Forest model.
8. Evaluate both models using classification metrics.
9. Perform cross-validation.
10. Compare model performance.
11. Visualize results using a confusion matrix.

How to Run the Project

Step 1: Install Required Libraries in command prompt

pip install pandas numpy matplotlib seaborn scikit-learn

Step 2: Launch Jupyter Notebook

Step 3: Open the Notebook save the file with a name 

ML_Classification_Project.ipynb

Step 4: Run All Cells

Run the notebook cells sequentially from top to bottom.

Results:

Both models were successfully trained and evaluated. Random Forest achieved slightly better performance compared to Logistic Regression based on accuracy, F1 score, and ROC-AUC score.

Repository Structure :

ML_Classification_Project/

├── ML_Classification_Project.ipynb

├── README.md

├── Report.pdf

└── screenshots/


