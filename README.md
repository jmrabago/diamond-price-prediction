# 💎 Diamond Price Prediction — Kaggle Competition

A **regression machine learning project** developed for a Kaggle competition. The objective is to accurately predict the price of diamonds based on their physical and quality characteristics, applying a complete data science workflow from exploratory analysis to model submission.

-----

## 📌 Project Overview

|Item        |Detail                                                             |
|------------|-------------------------------------------------------------------|
|**Type**    |Regression (Price Prediction)                                      |
|**Domain**  |Retail / Gemology / Pricing Models                                 |
|**Platform**|Kaggle Competition                                                 |
|**Dataset** |Diamonds dataset (train/test split)                                |
|**Tools**   |Python, Pandas, Scikit-Learn, Matplotlib, Seaborn, Jupyter Notebook|

-----

## 🗂️ Repository Structure

```
diamond-price-prediction/
│
├── diamond-price-prediction.ipynb            # Full analysis and model pipeline
├── diamonds_train.csv                        # Training dataset
├── diamonds_test.csv                         # Test dataset
└── diamond-price-prediction-submission.csv   # Final Kaggle submission file
```

-----

## 🔬 Methodology

### 1. 📊 Exploratory Data Analysis (EDA)

- Distribution analysis of diamond prices and physical features
- Correlation analysis between cut, color, clarity, carat, and price
- Detection and treatment of outliers
- Visualization of feature relationships using Matplotlib and Seaborn

### 2. 🧹 Data Preprocessing

- Encoding of categorical variables (cut, color, clarity)
- Feature scaling and normalization
- Feature engineering to improve model performance

### 3. 🤖 Model Training & Selection

- Trained and compared multiple regression models
- Evaluated with RMSE, MAE, and R² metrics
- Hyperparameter tuning to optimize prediction accuracy

### 4. 📤 Kaggle Submission

- Generated predictions on the test dataset
- Formatted and exported submission file following Kaggle requirements

-----

## 💡 Key Features (Diamond Attributes)

|Feature  |Description                                               |
|---------|----------------------------------------------------------|
|`carat`  |Weight of the diamond                                     |
|`cut`    |Quality of the cut (Fair, Good, Very Good, Premium, Ideal)|
|`color`  |Diamond color grade (D to J)                              |
|`clarity`|Clarity grade (I1 to IF)                                  |
|`depth`  |Total depth percentage                                    |
|`table`  |Width of top of diamond relative to widest point          |
|`x, y, z`|Length, width, and depth in mm                            |
|`price`  |**Target variable** — price in USD                        |

-----

## 🛠️ Technologies

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-150458?logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikit-learn)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)
![Kaggle](https://img.shields.io/badge/Kaggle-Competition-20BEFF?logo=kaggle)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue)

-----

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/jmrabago/diamond-price-prediction.git
cd diamond-price-prediction
```

1. Install dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

1. Open and run the notebook:

```bash
jupyter notebook diamond-price-prediction.ipynb
```

-----

## 👤 Author

**José Manuel Rábago Fernández**
Biomedical Engineer | Data Scientist
[LinkedIn](https://linkedin.com/in/jmrabago) · [GitHub](https://github.com/jmrabago)