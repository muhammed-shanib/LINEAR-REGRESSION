# Linear Regression using Scikit-learn

## Overview

This project demonstrates how to build a **Linear Regression** model using Python and Scikit-learn to analyze the relationship between productivity and compensation over time. The notebook includes data loading, visualization, preprocessing, model training, prediction, and evaluation.

---

## Dataset

The project uses the dataset:

`productivity_n_hourly_compensation.csv`

### Features (Independent Variables)

- `net_productivity_per_hour_worked`
- `average_compensation`
- `average_compensation_of_production_and_nonsupervisory_workers`

### Target Variable (Dependent Variable)

- `year`

---

## Project Workflow

1. Import required Python libraries.
2. Load the CSV dataset using Pandas.
3. Explore the dataset using:
   - `head()`
   - `tail()`
   - `shape`
4. Visualize relationships between variables using scatter plots.
5. Select feature columns and target variable.
6. Split the dataset into training and testing sets.
7. Train a Linear Regression model using Scikit-learn.
8. Generate predictions on the test dataset.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

---

## Libraries

```python
pandas
numpy
matplotlib
scikit-learn
```

---

## Project Structure

```
Linear-Regression/
│
├── linear_regression1.ipynb
├── productivity_n_hourly_compensation.csv
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Linear-Regression.git
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn
```

---

## Running the Project

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Upload the dataset when prompted.
3. Execute each notebook cell in order.
4. View the generated visualizations and prediction results.

---

## Model

The project uses **Linear Regression**, a supervised machine learning algorithm for predicting continuous values.

### Advantages

- Easy to understand
- Fast training
- Highly interpretable
- Suitable for linear relationships

### Limitations

- Assumes a linear relationship between variables
- Sensitive to outliers
- Performance decreases with non-linear data

---

## Visualizations

The notebook includes scatter plots showing relationships between:

- Net Productivity vs Year
- Average Compensation vs Year
- Average Compensation of Production and Nonsupervisory Workers vs Year

---

## Learning Outcomes

- Data preprocessing with Pandas
- Data visualization using Matplotlib
- Feature selection
- Train-test split
- Building a Linear Regression model
- Making predictions with Scikit-learn

---

## Future Improvements

- Add model evaluation metrics (R² Score, MAE, MSE, RMSE)
- Feature scaling
- Cross-validation
- Compare with other regression algorithms
- Improve visualization using Seaborn

---

## Author

Muhammed Shanib Mannooparambil
