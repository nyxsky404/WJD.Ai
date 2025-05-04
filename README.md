# 📊 Twitter Dataset EDA & Benford's Law Analysis

A data analysis project using a real-world Twitter dataset to explore user statistics, visualize patterns, and test for conformity with Benford's Law.

---

## 📁 Project Overview

This project focuses on:
- Exploratory Data Analysis (EDA) of a Twitter dataset
- Visualizing trends in user followers, language usage, and relationships
- Evaluating the applicability of **Benford’s Law** using statistical methods
- Providing key insights through meaningful charts and comparisons

---

## 📂 Dataset Information

- **File:** `twitter_data.csv.gz`
- **Size:** ~185MB (compressed)
- **Source:** Benford’s Datasets Collection

---

## 📊 Techniques Used

- Data Cleaning and Parsing (`pandas`, `ast`)
- Data Visualization (`matplotlib`, `seaborn`)
- Statistical Analysis (Benford’s Law, Chi-square test)
- Feature Understanding and Distribution Plots

---
If you're working with the compressed `.csv.gz` file, you can load it directly in Python:

```python
import pandas as pd

df = pd.read_csv("twitter_data.csv.gz", compression='gzip')
```
Or, extract it using:
- gunzip twitter_data.csv.gz (Linux/macOS/WSL)
- 7-Zip (Windows)
---

## 🔍 Key Visualizations

- Histogram of Followers Count
- Boxplots by Language
- Scatter Plot (Friends Count vs Followers Count)
- Benford's Law: Expected vs Observed First Digit Distribution

---

## 📈 Key Insights

- **Benford's Law** closely matched the distribution of follower counts.
- Most users speak a small set of dominant languages.
- Clear log-scale correlation between friends and followers for most users.
- Some users deviate significantly in friends/followers ratio, hinting at bots or influencers.

---

## 🧠 Team: WJD.Ai

- **Harshit Gupta** – harshit.k@adypu.edu.in  
- **Sumit Kumar** – sumit.kumar@adypu.edu.in  
- **Sahil Khan** – sahil.khan@adypu.edu.in  
- **Chiranjeev Agarwal** – chiranjeev.agarwal@adypu.edu.in  

---

## 👥 Member Contributions

- **Harshit Gupta** – Performed the initial data exploration and pre-processing.
- **Sumit Kumar** – Led the Benford's Law analysis, wrote the chi-square test logic, and plots.
- **Sahil Khan** – Designed and prepared the final PowerPoint presentation.
- **Chiranjeev Agarwal** – Developed visualizations and extracted insights from boxplots and scatterplots.

---

## 📌 Requirements

```bash
pandas
numpy
matplotlib
seaborn
scipy
```

## 🛠 How to Run

1. **Clone this repository**
2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Place twitter_data.csv.gz in the root directory**
4. **Run WJD.Ai.ipynb using Jupyter Notebook or Google Colab**

## 📘 License
- This project is for academic and research purposes only.

