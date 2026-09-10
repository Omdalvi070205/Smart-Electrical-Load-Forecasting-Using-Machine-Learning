# ⚡ Smart Electrical Load Forecasting Using Machine Learning

A beginner-friendly Machine Learning project that predicts **electrical load demand** using environmental factors such as **temperature and humidity**. The project combines concepts from **Electrical Engineering, Data Analytics, and Machine Learning** to explore how data-driven models can support electrical energy demand analysis.

---

## 📌 Project Overview

Electrical load forecasting is an important application in power systems and energy management. Accurate prediction of electricity demand can help in planning, scheduling, and efficient utilization of electrical resources.

In this project, Python and Machine Learning techniques are used to analyze the relationship between environmental conditions and electrical load and build a **Random Forest Regression** model for load prediction.

The notebook demonstrates the complete beginner-level workflow:

**Data Generation → Data Exploration → Data Quality Check → Visualization → Feature Analysis → Machine Learning → Model Evaluation**

---

## 🎯 Objectives

* Analyze electrical load patterns.
* Study the relationship between temperature, humidity, and electrical load.
* Perform basic data exploration and statistical analysis.
* Visualize feature relationships using correlation analysis.
* Build a Machine Learning regression model.
* Evaluate the prediction performance of the model.
* Explore how Machine Learning can be applied to electrical energy problems.

---

## 🛠️ Technologies & Tools

| Technology       | Purpose                   |
| ---------------- | ------------------------- |
| Python           | Programming & analysis    |
| Pandas           | Data manipulation         |
| NumPy            | Numerical computation     |
| Matplotlib       | Data visualization        |
| Seaborn          | Statistical visualization |
| Scikit-learn     | Machine Learning          |
| Jupyter Notebook | Development environment   |

---

## 📊 Dataset

The current notebook generates a dataset containing **1,000 observations** with the following features:

| Feature       | Description               |
| ------------- | ------------------------- |
| `Temperature` | Environmental temperature |
| `Humidity`    | Environmental humidity    |
| `Load`        | Electrical load value     |

The dataset is generated programmatically inside the notebook for demonstrating the Machine Learning workflow.

> **Note:** This version uses a generated/simulated dataset rather than a real utility or industrial dataset.

---

## 🔍 Project Workflow

### 1. Data Generation

A dataset containing temperature, humidity, and electrical load observations is created using Python and NumPy.

```python
temperature = np.random.randint(20, 45, 1000)
humidity = np.random.randint(30, 90, 1000)
```

The electrical load is generated based on these environmental variables with random noise to simulate variation in demand.

---

### 2. Data Exploration

Pandas is used to inspect the dataset and understand its structure.

The project performs:

* Dataset inspection
* Data type checking
* Statistical summary
* Minimum and maximum value analysis
* Mean and standard deviation analysis

---

### 3. Data Quality Check

Missing values are checked using:

```python
df.isnull().sum()
```

The current dataset contains no missing values.

---

### 4. Exploratory Data Analysis

Statistical and visual analysis is performed to understand relationships between the variables.

A correlation heatmap is created using:

```python
sns.heatmap(df.corr(), annot=True)
```

This helps analyze the relationship between:

* Temperature
* Humidity
* Electrical Load

---

### 5. Machine Learning

A **Random Forest Regression** model is used to predict electrical load.

The project uses:

```python
from sklearn.ensemble import RandomForestRegressor
```

Input features:

```text
Temperature
Humidity
```

Target:

```text
Load
```

---

### 6. Model Evaluation

The model is evaluated using regression performance metrics including:

* **Mean Absolute Error (MAE)**
* **R² Score**

These metrics help determine how accurately the model predicts electrical load.

---

## 📈 Key Analysis

The project demonstrates that environmental variables can be used as input features for estimating electrical load.

The analysis focuses on understanding how changes in:

🌡️ Temperature
💧 Humidity

can be associated with changes in:

⚡ Electrical Load

The project provides a foundation for developing more advanced electrical load forecasting systems using additional time-series and electrical parameters.

---

## 💡 Electrical Engineering Relevance

This project connects **Electrical Engineering with Data Science and Machine Learning**.

Potential applications include:

* Electrical load forecasting
* Energy demand analysis
* Peak-load identification
* Energy scheduling
* Smart-grid applications
* Energy consumption optimization
* Data-driven power system planning

---

## 🚀 Future Improvements

The project can be further improved by using a real-world electricity consumption dataset and adding additional forecasting features such as:

* Hour of the day
* Day of the week
* Month/season
* Previous-hour load
* Previous-day load
* Historical demand
* Solar generation
* Wind generation
* Real-time electricity consumption

Future versions can also compare multiple Machine Learning algorithms such as:

* Linear Regression
* Random Forest Regression
* Gradient Boosting
* XGBoost

and evaluate them using:

* MAE
* RMSE
* R²
* Actual vs Predicted plots

---

## 📁 Project Structure

```text
Smart-Electrical-Load-Forecasting/
│
├── Smart Electrical Load Forecasting & Energy Optimization
│   Using Machine Learning.ipynb
│
├── README.md
│
└── requirements.txt
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Smart-Electrical-Load-Forecasting.git
```

Navigate to the project directory:

```bash
cd Smart-Electrical-Load-Forecasting
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Run the Jupyter Notebook:

```bash
jupyter notebook
```

---

## 🧪 Requirements

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
```

---

## 👨‍💻 Author

**Om Dalavi**

B.Tech – Electrical & Computer Engineering

Interested in:

* Data Analytics
* Machine Learning
* Electrical Engineering
* Energy Systems
* Python
* Power Systems

---

## ⭐ Project Highlights

**Domain:** Electrical Engineering + Machine Learning
**Type:** Regression
**Model:** Random Forest Regressor
**Programming Language:** Python
**Level:** Entry-Level / Beginner Machine Learning Project

---

## 📜 License

This project is created for **educational and portfolio purposes**.
