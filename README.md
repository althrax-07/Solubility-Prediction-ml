# Solubility-Prediction-using-the-Delany-Dataset
This project focuses on building a machine learning model to predict aqueous solubility of chemical compounds using the Delany Solubility with Descriptors dataset.
The goal is to transform raw molecular descriptor data into a usable format, train a prediction model, and evaluate its performance — completing an end-to-end machine learning workflow.

The project demonstrates the entire ML pipeline, including preprocessing, model training, evaluation, and documentation of key decisions.

Dataset

Source: Delany Solubility with Descriptors dataset
Format: CSV file
Description:
This dataset contains molecular descriptors and experimentally measured solubility values for a variety of chemical compounds. Each record includes numeric features representing chemical structure/behavior and a target column representing solubility.

Data Preparation Steps Performed

The following steps were applied systematically to prepare the dataset for modeling:

1️⃣ Initial Data Inspection

Used head(), info(), and describe()

Identified dataset shape, column types, and basic statistics

Checked for duplicates, missing data, and inconsistencies

2️⃣ Feature & Target Selection

Dropped unnecessary columns (if any)

Selected all molecular descriptor columns as features (X)

Selected the solubility column as target (y)

3️⃣ Data Cleaning

Verified and handled missing values

Ensured all descriptors were numeric

Performed sanity checks on value ranges

Confirmed the target column was valid and continuous

4️⃣ Train-Test Split

Split dataset into training and testing sets

Used 80/20 ratio for model generalization

🤖 Machine Learning Workflow
5️⃣ Model Selection

A regression algorithm was used to predict solubility.
(Example: Linear Regression, Decision Tree Regressor, or Random Forest Regressor)

6️⃣ Model Training

Fitted the model using the training dataset

Verified model learned relationships between descriptors & solubility

7️⃣ Model Evaluation

Used common regression metrics:

Mean Squared Error (MSE)

R² Score

Evaluated how well predictions matched actual solubility values.

8️⃣ Predictions

Generated predictions on test data

Compared predicted vs. actual values

🛠️ Tools & Technologies Used

Python

pandas — data exploration & preprocessing

numpy — numerical operations

scikit-learn — model training & evaluation

Google Colab — development environment

GitHub — project version control and documentation

📈 Final Outcome

The final model successfully predicts the solubility of chemical compounds using molecular descriptors.
The cleaned dataset and trained model form a solid foundation for:

Exploratory data analysis (EDA)

Feature importance ranking

Model comparison or hyperparameter tuning

Building chemical property prediction tools

🧠 Key Learnings

How machine learning can be applied to chemistry and QSAR problems

Importance of clean numeric features for regression tasks

How to split data correctly and avoid data leakage

The value of evaluating models using appropriate metrics

How to document a complete ML workflow professionally
