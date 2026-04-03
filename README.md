# Linear-Regression
# Student Score Prediction using Linear Regression

## Project Description
This notebook demonstrates a simple linear regression model to predict student scores based on the number of hours they study. The goal is to understand the relationship between study hours and academic performance.

## Dataset
The dataset used contains two columns:
- `Hours`: The number of hours a student studied.
- `Scores`: The percentage score obtained by the student.

## Methodology
1.  **Data Loading and Exploration**: The dataset is loaded and initial exploratory data analysis (EDA) is performed to understand its structure and visualize the relationship between hours studied and scores.
2.  **Data Preparation**: The data is split into features (X) and target (y).
3.  **Model Training**: A simple Linear Regression model from `sklearn.linear_model` is used.
4.  **Model Evaluation**: The model's performance is evaluated using appropriate metrics.

## How to Run
1.  **Open in Google Colab**: You can open this notebook directly in Google Colab.
2.  **Mount Google Drive**: Ensure your Google Drive is mounted to access the `student_scores.csv` file, which is expected to be at `/content/drive/MyDrive/Untitled folder/student_scores.csv`.
3.  **Run Cells**: Execute each cell sequentially. The notebook will guide you through data loading, exploration, model training, and prediction.

## Libraries Used
-   `pandas`
-   `numpy`
-   `matplotlib.pyplot`
-   `seaborn`
-   `sklearn.linear_model`
-   `sklearn.model_selection`
