# Predictive-Model-for-Car-Price-Estimation

## Introduction

This project presents a complete workflow for cleaning, analyzing, and modeling used car price data sourced from Quikr, a classified advertisement platform in India. The primary goal is to develop a reliable price prediction model using linear regression, supported by robust data preprocessing and exploratory data analysis (EDA).

## Description

The dataset comprises second-hand car listings with features such as car name, company, year of manufacture, kilometers driven, fuel type, and price. Due to the unstructured nature of the data, extensive cleaning was required to remove noise, handle missing values, and standardize formats. The cleaned data was then used to train a machine learning model capable of predicting car prices with high accuracy.

This work is part of my larger portfolio of applied machine learning projects and demonstrates practical proficiency in data handling, feature engineering, and regression modeling.

## Tools and Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- Jupyter Notebook
- Matplotlib, Seaborn

## Objectives

- Load and inspect real-world car listing data
- Identify and address quality issues in the dataset
- Conduct exploratory data analysis to understand key pricing factors
- Build and evaluate a regression model to predict car prices

## Key Insights

- Initial dataset size: ~8,900 rows
- Rows removed (spam/invalid entries): ~1,000
- 'Ask For Price' entries removed: 245
- Final cleaned dataset: ~7,800 rows
- Missing values and outliers were handled to enhance data quality

## Data Cleaning Highlights

- Removed inconsistent and spam-like entries from `name` and `company`
- Converted `price`, `year`, and `kms_driven` fields to numeric types
- Handled missing values in categorical and numerical fields
- One-hot encoded categorical variables for modeling

## Model Summary

- Model used: Linear Regression
- Feature encoding: OneHotEncoding
- Train-test split: 80% training, 20% testing
- Evaluation metric: R² Score
- Achieved R² Score: 0.92  
  The model demonstrates strong predictive power and generalization.

## How to Run

1. Clone the repository to your local machine.
2. Open `Quikr_Analysis_Project.ipynb` using Jupyter Notebook or Google Colab.
3. Run the notebook cells in order to follow the data cleaning and modeling process.

## Future Work

- Integrate additional regression models for comparison (e.g., Random Forest, Gradient Boosting)
- Tune hyperparameters to further optimize performance
- Deploy the model using Streamlit or Flask for real-time predictions

## Acknowledgments

- Dataset inspired by publicly available car listings on [Quikr.com](https://www.quikr.com/).
- Model development inspired by coursework and self-paced learning from the Deep Learning Specialization by Andrew Ng.
- Tools and techniques based on industry-standard practices and academic coursework.

## License

This project is licensed under the MIT License.  
You are free to use, modify, and distribute this code with appropriate attribution.

---

## Author

**Jomaina Hafiz Ahmed**  
B.Tech Computer Science and Engineering, Lovely Professional University  
GitHub: [https://github.com/JomainaAhmed](https://github.com/JomainaAhmed)  
LinkedIn: [https://www.linkedin.com/in/jomaina-hafiz-ahmed-ml/](https://www.linkedin.com/in/jomaina-hafiz-ahmed-ml/)

