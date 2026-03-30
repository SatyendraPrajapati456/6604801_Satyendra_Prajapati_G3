# 🚗 Used Cars Data Analysis — Major Project

**Author:** Satyendra Prajapati
**Student ID:** 6604801
**Group:** G3

---

## 📌 Project Overview

This project is a comprehensive **Exploratory Data Analysis (EDA)** and **Machine Learning** study on a used cars dataset. The goal is to extract meaningful insights from real-world automotive data, apply data preprocessing techniques, and demonstrate key Data Science concepts using Python.

The notebook walks through the full data science workflow — from raw data ingestion to statistical analysis and interactive visualization.

---

## 📂 Repository Structure

```
6604801_Satyendra_Prajapati_G3/
│
├── major_project_used_cars.ipynb   # Main Jupyter Notebook with full analysis
├── used_cars.csv                   # Dataset used for analysis
├── requirements.txt                # Required Python libraries
└── README.md                       # Project documentation
```

---

## 🎯 Key Concepts Covered

- **Data Cleaning & Formatting** — Converting raw data into a structured, analysis-ready format
- **Exploratory Data Analysis (EDA)** — Extracting useful insights and patterns from the dataset
- **Encoding** — Converting categorical/string columns into numerical values for ML compatibility
- **Statistical Analysis** — Understanding data distribution using Skewness and Kurtosis
- **Data Visualization** — Presenting data clearly using plots and charts
- **Insight Communication** — Answering data-driven questions with well-presented outputs

---

## 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Jupyter Notebook / Google Colab | Development environment |
| Pandas | Data manipulation and CSV reading |
| NumPy | Numerical computations |
| Seaborn | Statistical data visualization |
| Plotly | Interactive visualizations |

---

## ⚙️ Installation & Setup

### Prerequisites

Make sure you have Python installed. Then install the required libraries:

```bash
pip install pandas numpy seaborn plotly
```

> **Note:** This project was originally developed on **Google Colab**. Specific library versions may vary. The above command will install the latest compatible versions.

### Running the Notebook

**Option 1 — Google Colab (Recommended)**

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload `major_project_used_cars.ipynb` and `used_cars.csv`
3. Run all cells

**Option 2 — Local Jupyter Notebook**

```bash
# Clone the repository
git clone https://github.com/SatyendraPrajapati456/6604801_Satyendra_Prajapati_G3.git

# Navigate into the directory
cd 6604801_Satyendra_Prajapati_G3

# Install dependencies
pip install pandas numpy seaborn plotly

# Launch Jupyter Notebook
jupyter notebook major_project_used_cars.ipynb
```

---

## 📊 Dataset

The dataset `used_cars.csv` contains records of used/second-hand cars with various attributes such as make, model, year, mileage, price, and more.

Data is loaded using:

```python
import pandas as pd
df = pd.read_csv("used_cars.csv")
```

> If working with an Excel file instead, use:
> ```python
> df = pd.read_excel("your_file.xlsx")
> ```

---

## 📈 Analysis Highlights

- Identifying and handling missing/null values
- Converting string data to numerical format for ML pipelines
- Analyzing **Skewness** (asymmetry of data distribution) and **Kurtosis** (tail heaviness) to understand the shape of data
- Creating visualizations (histograms, scatter plots, correlation heatmaps, etc.) using Seaborn and Plotly
- Presenting data answers to business questions in a clear and interpretable format

---

## 📚 Learning Outcomes

By going through this project, you will understand:

- How to approach a real-world dataset from scratch
- Best practices for data preprocessing and feature engineering
- How statistical measures like skewness and kurtosis guide data decisions
- How to choose the right visualization for the right insight

---

## 🤝 Contributing

This is an academic project. Feel free to fork and build upon it for learning purposes.

---

## 📄 License

This project is open for educational use. Please credit the author if you use or reference this work.

---

*Built with ❤️ as part of a Data Science curriculum project.*
