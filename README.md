# House_Price_Prediction_using_Linear_Regression

A Machine Learning project that predicts house prices based on various housing features using the **Linear Regression** algorithm. This project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis, model training, evaluation, and prediction.

---

## Project Overview

The real estate market relies heavily on accurate property valuation. This project aims to build a predictive model that estimates house prices using historical housing data and various property attributes.

The model is developed using **Linear Regression**, a supervised machine learning algorithm suitable for predicting continuous numerical values.

---

## Objective

To develop a machine learning model capable of predicting house prices based on features such as:

- Area of the house
- Number of bedrooms
- Number of bathrooms
- Number of stories
- Parking availability
- Furnishing status
- Additional amenities

---

## Dataset Information
The dataset contains multiple features related to residential properties.

### Features Used
| Feature | Description |
|----------|-------------|
| `price` | Price of the house (Target Variable) |
| `area` | Total area of the house in square feet |
| `bedrooms` | Number of bedrooms in the house |
| `bathrooms` | Number of bathrooms in the house |
| `stories` | Number of floors/stories in the house |
| `mainroad` | Indicates whether the house is connected to the main road (`yes`/`no`) |
| `guestroom` | Indicates the availability of a guest room (`yes`/`no`) |
| `basement` | Indicates whether the house has a basement (`yes`/`no`) |
| `hotwaterheating` | Indicates the availability of hot water heating (`yes`/`no`) |
| `airconditioning` | Indicates whether the house has air conditioning (`yes`/`no`) |
| `parking` | Number of parking spaces available |
| `prefarea` | Indicates whether the house is located in a preferred area (`yes`/`no`) |
| `furnishingstatus` | Furnishing status of the house (`furnished`, `semi-furnished`, `unfurnished`) |

## Dataset Usage

This dataset is used for:

- Exploratory Data Analysis (EDA)
- Data preprocessing and feature encoding
- Training a Linear Regression model
- Evaluating model performance using regression metrics
- Predicting house prices based on housing characteristics

## Data Preprocessing

The following preprocessing steps were performed before model training:

1. Handling categorical variables using encoding techniques.
2. Splitting the dataset into training and testing sets.
3. Feature selection for model development.
4. Preparing the data for Linear Regression.

## Target Variable

The objective of this project is to predict:

```text
House Price (`price`)
```

using the remaining features as input variables.

## Dataset Source

This dataset is publicly available and is commonly used for educational purposes and machine learning practice in regression problems.

## License

This dataset is used strictly for educational and learning purposes as part of this machine learning project.

##  Technologies Used

- **Python**
- **Jupyter Notebook**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

---

##  Machine Learning Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Encoding
5. Feature Selection
6. Train-Test Split
7. Model Training using Linear Regression
8. Model Evaluation
9. House Price Prediction

---

##  Model Used

### Linear Regression

Linear Regression is a supervised learning algorithm used to predict continuous target variables by modeling the relationship between dependent and independent variables.

The model attempts to fit a linear equation to the observed data:

```
Price = β₀ + β₁X₁ + β₂X₂ + ... + βₙXₙ + ε
```

Where:

- **β₀** = Intercept
- **β₁ ... βₙ** = Coefficients
- **X₁ ... Xₙ** = Input Features
- **ε** = Error Term

---

## Model Evaluation

The model performance was evaluated using standard regression metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

> **Note:** Update this section with the actual evaluation metrics obtained from your notebook.

---

## Project Structure

```text
House-Price-Prediction-Linear-Regression/
│
├── Housing.csv
├── House_Price_Prediction_using_Linear_Regression.ipynb
├── README.md
└── .gitignore
```

---

##  Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/KORAKASI/House-Price-Prediction-Linear-Regression.git
```

### 2. Navigate to the Project Directory

```bash
cd House-Price-Prediction-Linear-Regression
```

### 3. Install Required Dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open and Run

```text
House_Price_Prediction_using_Linear_Regression.ipynb

##  Learning Outcomes

Through this project, I gained practical experience in:

- Data preprocessing techniques
- Exploratory Data Analysis (EDA)
- Feature engineering
- Building regression models
- Evaluating machine learning models
- End-to-end machine learning project development

---
## Support

If you found this project helpful or interesting, please consider giving it a **⭐ Star** on GitHub.

---

