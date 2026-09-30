# House Price Prediction using Linear Regression

## 📌 Project Overview

This project uses **Machine Learning and Linear Regression** to predict house prices based on different property features.

The dataset contains information about houses such as:

* Area
* Number of bedrooms
* Number of bathrooms
* Age of the house
* Location
* Price

The project demonstrates the basic workflow of a machine learning regression problem, including data loading, data exploration, preprocessing, model training, prediction, and model evaluation.

## 📂 Dataset

The dataset contains the following columns:

| Column     | Description                 |
| ---------- | --------------------------- |
| `area`     | Area of the house           |
| `bedroom`  | Number of bedrooms          |
| `bathroom` | Number of bathrooms         |
| `age`      | Age of the house            |
| `location` | Location value of the house |
| `price`    | House price                 |

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook

## 🔄 Project Workflow

1. Load the house price dataset.
2. Explore the dataset using:

   * `info()`
   * `describe()`
   * Missing-value checking
3. Prepare the features and target variable.
4. Split the dataset into training and testing sets.
5. Train a **Linear Regression** model.
6. Predict house prices for the test data.
7. Evaluate the model using:

   * Mean Absolute Error (MAE)
   * Mean Squared Error (MSE)
   * Root Mean Squared Error (RMSE)
   * R² Score
8. Visualize actual vs. predicted house prices.
9. Compare model performance using different feature sets.

## 🤖 Machine Learning Model

The project uses:

**Linear Regression**

The model is trained using the following features:

```text
area
bedroom
bathroom
age
location
```

The target variable is:

```text
price
```

The dataset is divided into training and testing data using an **80:20 split** with `random_state=42`.

## 📊 Model Evaluation

The model performance is evaluated using:

* **MAE** – Mean Absolute Error
* **MSE** – Mean Squared Error
* **RMSE** – Root Mean Squared Error
* **R² Score** – Measures how well the model explains the variation in house prices

The notebook also compares the R² score when using different numbers of features.

## 📈 Visualization

An **Actual vs Predicted House Price** scatter plot is created to visualize the model's predictions.

The closer the predicted values are to the actual values, the better the model's predictions.

## 📁 Project Structure

```text
house-price-prediction-linear-regression/
│
├── houseprices.csv
├── houseprices.ipynb
└── README.md
```

## ▶️ How to Run

1. Clone this repository.
2. Open `houseprices.ipynb` using Jupyter Notebook or JupyterLab.
3. Make sure the required Python libraries are installed.
4. Place the dataset in the same directory as the notebook.
5. Run the notebook cells in order.

Install the required libraries with:

```bash
pip install pandas numpy scikit-learn matplotlib jupyter
```

## 🎯 Learning Outcomes

This project demonstrates:

* Data loading and exploration
* Handling missing values
* Feature and target selection
* Train-test splitting
* Linear Regression
* Making predictions
* Regression model evaluation
* Data visualization
* Comparing model performance

## 👩‍💻 Project

**House Price Prediction using Linear Regression**

Built as a machine learning practice project using Python and Scikit-learn.
