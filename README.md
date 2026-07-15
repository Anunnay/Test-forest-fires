# 🔥 Algerian Forest Fires – FWI Prediction Using Ridge Regression

## 📌 Project Overview

This project focuses on predicting the **Fire Weather Index (FWI)** using machine learning. The dataset contains weather and fire-related observations collected from two regions of Algeria.

The project includes data cleaning, exploratory data analysis, feature selection, feature standardization, and the implementation of a **Ridge Regression** model to predict FWI.

## 📊 Dataset

The **Algerian Forest Fires Dataset** contains data collected from two regions:

* **Bejaia Region**
* **Sidi-Bel Abbes Region**

The dataset includes meteorological conditions and different components of the Fire Weather Index system.

### Features

* **Temperature** – Temperature in degrees Celsius
* **RH** – Relative Humidity
* **Ws** – Wind Speed
* **Rain** – Rainfall
* **FFMC** – Fine Fuel Moisture Code
* **DMC** – Duff Moisture Code
* **DC** – Drought Code
* **ISI** – Initial Spread Index
* **BUI** – Buildup Index
* **FWI** – Fire Weather Index
* **Classes** – Fire or Not Fire
* **Region** – Region of the observation

## 🎯 Objective

The main objective of this project is to build a regression model that can accurately predict the **Fire Weather Index (FWI)** based on the available weather and fire-related features.

## ⚙️ Project Workflow

1. **Data Cleaning**

   * Handled missing values
   * Removed unnecessary rows and columns
   * Corrected column names and data types

2. **Exploratory Data Analysis**

   * Analyzed the distribution of fire and non-fire cases
   * Performed monthly fire analysis for both regions
   * Studied relationships between different features

3. **Feature Engineering**

   * Encoded categorical features
   * Removed highly correlated features to reduce multicollinearity
   * Selected relevant independent features for FWI prediction

4. **Train-Test Split**

   * Divided the dataset into training and testing sets

5. **Feature Standardization**

   * Applied `StandardScaler` to standardize the input features
   * The scaler was fitted only on the training data and then used to transform both training and testing data

6. **Model Training**

   * Implemented **Ridge Regression**
   * Ridge regularization helps control large coefficients and reduces the effect of multicollinearity

7. **Model Evaluation**

   * Evaluated the model using regression performance metrics such as:

     * Mean Absolute Error (MAE)
     * R² Score

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## 🤖 Machine Learning Model

The main model used in this project is:

**Ridge Regression with Feature Standardization**

Ridge Regression applies **L2 regularization**, which adds a penalty to large model coefficients. This helps improve model stability, particularly when some input features are highly correlated.

## 📈 Model Pipeline

The overall machine learning workflow can be summarized as:

`Dataset → Data Cleaning → EDA → Feature Selection → Train-Test Split → Standardization → Ridge Regression → Model Evaluation`

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone <your-repository-url>
```

2. Navigate to the project directory:

```bash
cd <repository-name>
```

3. Install the required dependencies:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

4. Start Jupyter Notebook:

```bash
jupyter notebook
```

5. Open the project notebook and run all the cells.

## 📌 Conclusion

This project demonstrates the complete machine learning workflow for predicting the **Fire Weather Index (FWI)** using **Ridge Regression**. Feature standardization and regularization are used to create a more stable regression model and handle relationships between correlated weather and fire-index features.

## 👨‍💻 Author

**Anunnay Sahu**

B.Tech Student
National Institute of Technology, Rourkela
