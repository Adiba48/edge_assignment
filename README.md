Student Performance Prediction

This project predicts student performance based on various learning and lifestyle factors using machine learning models.

Requirements

Make sure you have the following libraries installed:

Python 3.x

KaggleHub

Pandas

NumPy

Seaborn

Matplotlib

Scikit-learn

To install the required libraries, run:

pip install pandas numpy seaborn matplotlib scikit-learn kagglehub

Dataset

The dataset is downloaded from Kaggle using KaggleHub. It contains various student attributes such as age, study hours, learning styles, and final grades.

Usage

Download and Load Dataset: The script downloads the dataset using KaggleHub and loads it into a Pandas DataFrame.

Data Preprocessing:

Categorical variables are encoded using Label Encoding.

Features and target variables are defined.

Data is split into training and testing sets.

Numerical features are normalized using StandardScaler.

Model Training and Evaluation:

Three models are trained: Linear Regression, Support Vector Regression, and Gradient Boosting Regressor.

Model performance is evaluated using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score.

Actual vs. Predicted scores are visualized using scatter plots.

Running the Script

Run the following command to execute the script:

python student_performance.py

Output

The script prints the first few rows of the dataset.

Model performance metrics are displayed.

Scatter plots for actual vs. predicted scores are generated.
