# 🏠 HousePriceML

A data preprocessing and machine learning project focused on preparing real estate data for predictive modeling. This project handles missing values, removes irrelevant features, and gets the data ready to predict house prices using supervised learning techniques.

---

## 🎯 Project Objective

The goal is to clean and prepare housing data to build accurate machine learning models for predicting home sale prices. The dataset is derived from real estate listings and includes various features like lot size, location, number of rooms, etc.

---

## 🧼 Data Cleaning Steps

- **Identified missing values** in key columns.
- Filled `LotFrontage` using the **median** to avoid skewing the data.
- Filled categorical columns like `Electrical` using the **mode**.
- Dropped columns with too many missing values or irrelevant information.
- Separated the **target variable (`SalePrice`)** from the features.

---

## 📁 Dataset

- `train.csv`: The original dataset containing housing features and sale prices.
- Cleaned dataset prepared for modeling is generated within the Jupyter Notebook.

---

## 📘 Notebook

- `house pricing.ipynb`: Contains the full data preprocessing pipeline including:
  - Data exploration
  - Missing value treatment
  - Feature selection/removal
  - Saving cleaned dataset

---

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook
- Matplotlib / Seaborn (optional for EDA)

---

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/HousePriceML.git
   cd HousePriceML
