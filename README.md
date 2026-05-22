# Bicycle Theft Recovery Prediction

## Project Overview
This project predicts whether a stolen bicycle in Toronto is likely to be recovered using machine learning and data analysis.

The main goal of this project is to analyse bicycle theft patterns, understand recovery trends, and build a machine learning model that can support better decision-making for urban crime analysis.

## Tools and Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- SMOTEENN
- Power BI

## Key Features
- Cleaned and prepared Toronto bicycle theft data
- Analysed recovery patterns by time, location, and bicycle details
- Created new features such as weekend theft and night-time theft
- Handled severe class imbalance using SMOTEENN
- Built and compared multiple machine learning models
- Created a Power BI dashboard to show theft and recovery insights

## Machine Learning Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

## Dashboard Preview

![Dashboard Preview](dashboard/dashboard-preview.png)

## Dataset
The dataset contains bicycle theft records with details such as theft time, location, bike type, cost, and recovery status.

The target variable was created using recovery status:
- `0` = Stolen
- `1` = Recovered

## Key Insights
- Bicycle recovery rate is very low compared to stolen cases.
- Night-time thefts are less likely to be recovered.
- Higher-value bicycles may have lower recovery chances.
- XGBoost performed better than other models after handling class imbalance.
- SMOTEENN helped improve model recall and F1-score for recovered bicycles.

## Files Included
- `bicycle_theft_recovery_prediction.ipynb` - Python notebook for data analysis and machine learning
- `data/bicycle_thefts.csv` - Bicycle theft dataset
- `dashboard/dashboard-preview.png` - Power BI dashboard screenshot
- `requirements.txt` - Required Python libraries

## How to Run
1. Download or clone this repository.

2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook bicycle_theft_recovery_prediction.ipynb
```

4. Run all cells to view the analysis and model results.

## Note
The Power BI file is not uploaded publicly. A dashboard screenshot is included for preview.

## Project Type
Academic machine learning and business intelligence project.
