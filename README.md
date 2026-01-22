# In-Vehicle Coupon Recommendation Prediction

This project aims to predict whether a person will accept a coupon recommended to them in different driving scenarios. The dataset is sourced from the UCI Machine Learning Repository.

## Project Overview

The project involves:
- **Data Loading**: Fetching the 'In-Vehicle Coupon Recommendation' dataset from the UCI ML Repository.
- **Data Understanding**: Exploratory Data Analysis (EDA) to inspect missing values, feature distributions, and class imbalance.
- **Preprocessing**: Handling missing values, feature engineering (e.g., combining distance features), and encoding categorical variables.
- **Modeling**: Training and evaluating various classification models, including Logistic Regression, Linear SVC, and RandomForest.
- **Hyperparameter Tuning**: Using Randomized Search and Grid Search to find the best hyperparameters for the chosen model.
- **Evaluation**: Assessing model performance using metrics like F1-score, ROC-AUC, and PR-AUC, and selecting an optimal classification threshold.
- **Feature Importance**: Identifying the most important features driving coupon acceptance predictions.

## Running Instructions

To set up and run this project locally, follow these steps:

### 1. Clone the Repository (if applicable)

```bash
git clone https://github.com/BerhanDemiralp/Coupon-Recommendation.git
cd Coupon-Recommendation
```

### 2. Install Dependencies

First, ensure you have Python (3.7+) and `pip` installed. Then, install the required Python libraries using the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

### 3. Run the Notebook

Open the Jupyter Notebook or Google Colab environment and execute the cells sequentially.
You can see the plots and results as output.

## Data Source

The dataset used in this project is the "In-Vehicle Coupon Recommendation" dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/603/in+vehicle+coupon+recommendation).

## Libraries Used

- `ucimlrepo`
- `numpy`
- `pandas`
- `matplotlib`
- `scipy`
- `seaborn`
- `scikit-learn`
