<div align="center">

# 🏥 Medical Data Visualizer

### *Cardiovascular Risk Analysis with Pandas, Matplotlib & Seaborn*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:E74C3C&height=120&section=header" />

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)](https://seaborn.pydata.org/)
[![freeCodeCamp](https://img.shields.io/badge/freeCodeCamp-0A0A23?style=for-the-badge&logo=freecodecamp&logoColor=white)](https://www.freecodecamp.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

</div>

---

## 📖 Overview

**Medical Data Visualizer** analyses a dataset of **70,000 patient examinations** to uncover patterns linking lifestyle, body measurements, and cardiovascular disease.

Built as part of the **freeCodeCamp Data Analysis with Python** certification, this project demonstrates end-to-end data analysis: from raw CSV cleaning to publication-ready visualisations.

> 🎯 **Goal**: Identify how factors like cholesterol, glucose, activity, alcohol, and BMI relate to cardiovascular disease incidence.

---

## 📊 Visualisations

### 1. Categorical Plot — Health Indicators by Cardio Status

Compares 5 binary health indicators (cholesterol, glucose, smoking, alcohol, activity, overweight) between patients **with** and **without** cardiovascular disease.

![Categorical Plot](catplot.png)

**Key insight**: Patients with cardiovascular disease show notably higher rates of elevated cholesterol and glucose levels.

---

### 2. Correlation Heatmap — Variable Relationships

Visualises the **Pearson correlation matrix** between all variables, with the upper triangle masked for clarity.

![Correlation Heatmap](heatmap.png)

**Key insight**: Strong correlations between **weight & BMI**, and meaningful associations between **cholesterol, glucose, and cardiovascular disease**.

---

## 🎯 Key Features

- 🧹 **Data Cleaning** — Removes invalid blood pressure readings, normalises body measurements
- 📏 **Feature Engineering** — Computes BMI and creates the `overweight` binary indicator
- 🔄 **Data Normalisation** — Rescales cholesterol & glucose to binary (`0` = normal, `1` = elevated)
- 📊 **Categorical Analysis** — Aggregated counts visualised with Seaborn's `catplot`
- 🔥 **Correlation Analysis** — Triangular heatmap to avoid redundancy
- ✅ **Reproducible** — Single command to regenerate both plots

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- pip

### Installation

```bash
# Clone the repository
git clone https://github.com/The-Special-One1/medical-data-visualizer.git
cd medical-data-visualizer

# Install dependencies
pip install pandas matplotlib seaborn numpy

# Run the visualiser
python main.py
