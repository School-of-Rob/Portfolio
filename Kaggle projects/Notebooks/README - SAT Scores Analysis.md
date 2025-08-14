# SAT Scores Analysis - Machine Learning Notebook

This notebook investigates factors influencing SAT exam scores using a dataset from Kaggle. The workflow includes:

- **Data Preparation:** Importing, cleaning, handling missing values, and removing irrelevant columns.
- **Exploratory Data Analysis:** Visualizing distributions and relationships between exam scores and features such as study hours, sleep, diet, parental education, and extracurricular activities.
- **Feature Engineering:** One-hot encoding categorical variables for modeling.
- **Correlation Analysis:** Heatmap to identify features most correlated with exam scores.
- **Modeling:** Multiple linear regression with train/test split to predict exam scores.
- **Evaluation:** R² score, RMSE, and visualization of actual vs. predicted scores.
- **Insights:** Identification of top predictors (e.g., study hours, attendance, sleep, exercise, mental health).

## Usage

1. Download the SAT scores dataset from Kaggle.
2. Update the file path in the notebook to match your local environment.
3. Run the notebook cells sequentially.

## Requirements

- Python 3.x
- pandas, numpy, seaborn, matplotlib, plotly
- scikit-learn

---

**Author:** Robert Hilario
**Coding time:** ~2 hours (no AI assistance)