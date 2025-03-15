# Laptop_Data
This repository contains an analysis of laptop prices using data science techniques. The project involves data preprocessing, exploratory data analysis (EDA), hypothesis testing, and predictive modeling to determine key factors influencing laptop prices.

## Dataset
The dataset consists of various laptop attributes, including:
- Brand
- Processor Type
- Weight
- Touch screen
- RAM Size
- Storage Type
- Price

## Key Insights
The analysis covers:
- **Data Cleaning & Preprocessing:** Handling missing values, normalizing data, and converting categorical features.
- **Exploratory Data Analysis (EDA):** Identifying trends, correlations, and key variables affecting laptop prices.
- **Hypothesis Testing:** Applying statistical tests to validate assumptions about price distribution.
- **Machine Learning Modeling:** Implementing regression models to predict laptop prices based on specifications.
- **Model Performance:**
  - The **Linear Regression model** resulted in an underfitting R² score, indicating poor predictive power.
  - Testing with the **Decision Tree Regressor** showed better predictions with improved accuracy.
  - Finally, the **Random Forest model** provided the best prediction accuracy, reducing overfitting and improving generalization.

## Sample Code
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
%matplotlib inline
import seaborn as sns
import warnings
from warnings import filterwarnings
filterwarnings('ignore')

laptop_data = pd.read_csv('laptop_data_cleaned.csv')

# Display first 5 rows of the data
laptop_data.head()
```

## Dependencies
To run this analysis, install the required Python packages:
```bash
pip install pandas numpy seaborn matplotlib scikit-learn
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/laptop-price-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd laptop-price-prediction
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook laptop_data.ipynb
   ```

## Author
Richard Olanite - Data Analyst

## License
This project is licensed under the MIT License.

