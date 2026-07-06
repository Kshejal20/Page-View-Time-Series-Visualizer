# 📈 Page View Time Series Visualizer

Analyze and visualize daily freeCodeCamp forum page views using Python, Pandas, Matplotlib, and Seaborn. This project explores long-term trends, monthly averages, and seasonal patterns through multiple data visualizations.

> **Project:** Page View Time Series Visualizer
> **Certification:** freeCodeCamp – Data Analysis with Python

---

# 🚀 Project Overview

This project analyzes the daily page views of the freeCodeCamp forum from **May 2016 to December 2019**.

The dataset is first cleaned by removing extreme outliers and then visualized using three different chart types to better understand traffic patterns over time.

The visualizations help identify:

* Long-term growth trends
* Average monthly page views
* Seasonal variations
* Distribution of page views across years and months

---

# 📂 Dataset

**File:** `fcc-forum-pageviews.csv`

The dataset contains two columns:

| Column | Description                             |
| ------ | --------------------------------------- |
| date   | Date of the recorded page views         |
| value  | Number of forum page views for that day |

---

# 📊 Visualizations

## 1. Line Plot

Displays the daily number of forum page views over time.

**Purpose**

* Visualize overall traffic growth
* Identify peaks and dips
* Observe long-term trends

---

## 2. Monthly Bar Plot

Shows the average daily page views for each month, grouped by year.

**Purpose**

* Compare monthly traffic across different years
* Analyze yearly growth
* Observe changes in monthly averages

---

## 3. Box Plots

Two box plots are generated.

### Year-wise Box Plot

Shows the distribution of page views for each year.

Used to analyze:

* Trend over time
* Spread of data
* Median page views
* Variability

### Month-wise Box Plot

Shows the distribution of page views for each month.

Used to analyze:

* Seasonality
* Monthly traffic patterns
* Consistency across years

---

# 🧹 Data Cleaning

Before visualization, the dataset is cleaned by removing the top and bottom **2.5%** of page view values.

This removes extreme outliers and produces more meaningful visualizations.

---

# 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* NumPy

---

# 📚 Skills Demonstrated

* Data Cleaning
* Time Series Analysis
* Exploratory Data Analysis (EDA)
* Date & Time Manipulation
* Data Aggregation
* Statistical Visualization
* Trend Analysis
* Seasonality Analysis
* Data Visualization with Matplotlib & Seaborn

# ▶️ How to Run

Clone the repository:

```bash
git clone https://github.com/your-username/Page-View-Time-Series-Visualizer.git
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the project:

```bash
python main.py
```

Generated images:

* `line_plot.png`
* `bar_plot.png`
* `box_plot.png`

---

# 📈 Learning Outcomes

Through this project, I learned how to:

* Clean datasets by removing outliers
* Work with time-series data using Pandas
* Aggregate data by month and year
* Build professional visualizations using Matplotlib and Seaborn
* Interpret trends, variability, and seasonality from real-world data

---

# 👩‍💻 Author

**Kshitija Shejal**

Recent B.Tech graduate in Computer Science (AI) with a strong interest in Data Analytics, Machine Learning, and Artificial Intelligence.

---

⭐ If you found this project helpful, consider giving it a **Star** on GitHub!
