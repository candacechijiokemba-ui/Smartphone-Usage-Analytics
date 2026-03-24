# Smartphone-Usage-Analytics

## 📊 Project Overview

This project analyzes smartphone usage patterns and addiction tendencies using a real-world dataset of 7,500 users. The goal is to uncover behavioral trends, screen time habits, and demographic insights through data exploration and visualization.

By leveraging Python data analysis tools, this project provides a structured approach to understanding how different factors (such as age and gender) relate to smartphone usage.

---

## 🧠 Objectives

* Explore and clean smartphone usage data
* Identify missing values and ensure data quality
* Analyze average screen time and demographic trends
* Examine usage patterns across different groups
* Generate insights into potential smartphone addiction behavior

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas** – data manipulation and analysis
* **NumPy** – numerical computations
* **Matplotlib / Seaborn** – data visualization

---

## 📂 Dataset

The dataset used:

* **Smartphone Usage and Addiction Analysis (7500 rows)**
* Includes features such as:

  * Age
  * Gender
  * Daily screen time
  * Behavioral indicators related to smartphone use

---

## 🔍 Key Analysis Steps

### 1. Data Loading

```python
df = pd.read_csv("Smartphone_Usage_And_Addiction_Analysis_7500_Rows.csv")
```

### 2. Data Exploration

* Preview dataset (`head`, `tail`)
* Understand structure and features

### 3. Data Cleaning

* Checked for missing/null values:

```python
df.isnull().sum()
```

### 4. Descriptive Statistics

* Average age:

```python
df['age'].mean()
```

* Average daily screen time:

```python
df['daily_screen_time_hours'].mean()
```

### 5. Demographic Analysis

* Gender distribution:

```python
df['gender'].value_counts()
```

---

## 📈 Insights You Can Derive

* Average screen time trends across users
* Demographic patterns in smartphone usage
* Potential indicators of excessive or addictive behavior
* Distribution of usage across different population groups

---

## 🚀 Future Improvements

* Add advanced visualizations (heatmaps, correlation matrices)
* Build predictive models for addiction risk
* Perform time-series or behavioral clustering analysis
* Create an interactive dashboard (e.g., using Plotly or Streamlit)

---

## 📌 How to Run

1. Clone the repository
2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Run the Jupyter Notebook:

```bash
jupyter notebook
```

---

## 🤝 Contributions

Contributions, suggestions, and improvements are welcome!

---

## Authors
* Candace Chijioke-Mba
* Destiny Kevin
