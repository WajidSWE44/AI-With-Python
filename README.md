# AI using Python – Course Assignments

This repository contains my assignments completed as part of the **AI using Python** course. Each notebook focuses on a different stage of the machine learning / data science workflow, from core Python fundamentals to building and evaluating deep learning models.

## Repository Structure

| Notebook | Topic | Key Concepts |
|---|---|---|
| `Task1_DigiSkill.ipynb` | Python Fundamentals & OOP | Conditional statements, dictionaries, Object-Oriented Programming (classes, encapsulation) |
| `Assignment_2.ipynb` | Data Preprocessing (House Price Data) | Pandas, data exploration, handling missing values, duplicate removal, label encoding |
| `Assignment_no_3_House_Price_Prediction.ipynb` | Regression Modeling | Linear Regression, train-test split, model evaluation (MAE, RMSE, R²), visualization |
| `Assignment_4_FashionMNIST_CNN.ipynb` | Deep Learning (CNN) | TensorFlow/Keras, Convolutional Neural Networks, image classification, confusion matrix, classification report |

## Assignment Details

### 1. Task1_DigiSkill.ipynb — Python Fundamentals
- Tax calculation using conditional statements based on salary slabs
- Building a word-length dictionary from a list of strings
- Console-based chat system built with User, Message, and ChatRoom classes, implementing sending messages, viewing chat history, and users joining/leaving a chat room

### 2. Assignment_2.ipynb — House Price Data Preprocessing
- Loading and exploring the `HousePricePrediction.csv` dataset
- Generating summary statistics and checking data types
- Handling missing values (median for numeric, mode for categorical columns)
- Removing duplicate records
- Dropping irrelevant identifier columns (`Id`)
- Encoding categorical variables using `LabelEncoder`

### 3. Assignment_no_3_House_Price_Prediction.ipynb — House Price Prediction
- Building a **Linear Regression** model to predict house sale prices
- Splitting data into training and test sets
- Evaluating model performance using MAE, RMSE, and R² score
- Visualizing actual vs. predicted prices, residual plots, and a model performance summary

### 4. Assignment_4_FashionMNIST_CNN.ipynb — Fashion MNIST Classification (CNN)
- Loading and preprocessing the Fashion MNIST dataset (normalization, reshaping)
- Building a **Convolutional Neural Network (CNN)** using TensorFlow/Keras with convolutional, pooling, and dropout layers
- Training the model with early stopping and learning rate reduction callbacks
- Evaluating performance with test accuracy/loss, confusion matrix, and classification report
- Visualizing training history (accuracy/loss curves) and sample predictions

## Tools & Libraries Used
- **Python 3**
- `pandas`, `numpy` — data manipulation
- `scikit-learn` — preprocessing, regression modeling, evaluation metrics
- `matplotlib`, `seaborn` — data visualization
- `tensorflow` / `keras` — deep learning (CNN)

## How to Run
1. Clone this repository
   ```bash
   git clone <repository-url>
   ```
2. Install the required dependencies
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn tensorflow
   ```
3. Open any notebook using Jupyter Notebook / JupyterLab
   ```bash
   jupyter notebook
   ```
4. Run the cells in order from top to bottom

