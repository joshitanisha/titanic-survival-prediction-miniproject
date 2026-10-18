# Titanic Survival Prediction Using Machine Learning

## Project Overview

Titanic Survival Prediction is a machine learning mini project developed using Python in Jupyter Notebook.

The project analyzes passenger information from the Titanic dataset and builds machine learning classification models to predict whether a passenger survived the Titanic disaster.

The project includes data cleaning, exploratory data analysis, feature engineering, model training, model evaluation, and survival prediction.

## Objectives

- Understand and analyze the Titanic passenger dataset.
- Perform data cleaning and preprocessing.
- Handle missing values.
- Perform exploratory data analysis (EDA).
- Visualize survival patterns using graphs.
- Apply feature engineering techniques.
- Train multiple machine learning classification models.
- Evaluate and compare model performance.
- Generate survival predictions for unseen passenger records.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Git and GitHub

## Dataset

The project uses the Titanic: Machine Learning from Disaster dataset provided through Kaggle.

Dataset Link:
https://www.kaggle.com/c/titanic/data

The dataset contains passenger information such as passenger class, age, sex, ticket fare, family relationships, and survival status.

### Dataset Files

- `train.csv`: Used for exploratory data analysis, model training, and validation.
- `test.csv`: Used to generate predictions for passengers whose survival labels are not provided.
- `gender_submission.csv`: Optional example prediction file provided by Kaggle.

Download the dataset from Kaggle and place the required CSV files in the project directory.

## Project Workflow

1. Import the required Python libraries.
2. Load and inspect the dataset.
3. Analyze dataset structure and statistical summaries.
4. Identify missing values and duplicate records.
5. Perform exploratory data analysis.
6. Visualize survival patterns based on passenger attributes.
7. Handle missing values and preprocess the data.
8. Perform feature engineering.
9. Split the labelled dataset into training and validation sets.
10. Train multiple machine learning models.
11. Evaluate model performance using classification metrics.
12. Compare the trained models.
13. Generate a confusion matrix and ROC curve.
14. Perform cross-validation.
15. Analyze feature importance.
16. Generate predictions for the test dataset.
17. Save prediction and evaluation results as CSV files.

## Machine Learning Algorithms

The project compares the following classification algorithms:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors Classifier

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC Score
- Cross-validation accuracy

The models are compared using validation results to identify a suitable candidate for final prediction.

## Project Structure

```text
Titanic-survival-prediction-mini-project/
│
├── data/
│   ├── train.csv
│   ├── test.csv
│   └── gender_submission.csv
│
├── Titanic_Survival_Prediction.ipynb
│
├── submission.csv
├── model_comparison.csv
├── cross_validation_results.csv
├── feature_importance.csv
│
├── README.md
├── requirements.txt
└── .gitignore
```

The CSV files under `data/` should be included only if their applicable terms permit redistribution. Generated output files will be available after executing the notebook.

## Installation and Execution

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Titanic-survival-prediction-mini-project.git
```

Replace `YOUR-USERNAME` with your GitHub username.

### 2. Navigate to the Project Directory

```bash
cd Titanic-survival-prediction-mini-project
```

### 3. Install Dependencies

```bash
python3 -m pip install -r requirements.txt
```

### 4. Download the Dataset

Download `train.csv` and `test.csv` from the Kaggle competition page.

Place the files in the location expected by the notebook.

### 5. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `Titanic_Survival_Prediction.ipynb` and execute the cells sequentially.

## Outputs

After successful execution, the notebook generates:

- Exploratory data analysis visualizations.
- Missing-value summaries.
- Model performance comparisons.
- Classification reports.
- Confusion matrix and ROC curve.
- Feature importance visualizations.
- Test dataset survival predictions.
- CSV files containing prediction and evaluation results.

## Results

Model performance results will be documented after executing the notebook and evaluating the trained models.

## Limitations

- The dataset contains a limited number of labelled passenger records.
- The test dataset does not contain actual survival labels.
- Model performance depends on feature selection, preprocessing, and model configuration.
- Validation performance may differ from performance on genuinely unseen data.

## Future Scope

- Hyperparameter tuning.
- Additional feature engineering.
- Comparison with additional classification algorithms.
- Improved model selection and validation.
- Further investigation of feature importance.

## Acknowledgements

The Titanic dataset is provided through Kaggle's Titanic: Machine Learning from Disaster competition.

Dataset: https://www.kaggle.com/c/titanic/data
