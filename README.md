# web-ab-testing-analysis

A/B Testing Analysis of Website Experiments

## 📌 Project Overview

This project focuses on performing an **A/B test analysis** using real-world website experiment data. The dataset comes from an online controlled experiment where users were split into **control (A)** and **treatment (B)** groups to measure the effect of design/behavioral changes on user interaction.

The goal is to:

* Meet the 
* Run **statistical tests** (t-test, chi-square, bootstrap).
* Visualize the differences between groups.
* Provide insights on whether the treatment group significantly improves performance.

---

## 📂 Dataset Information

**Dataset Name:** [OpenML Website Behavior A/B Testing Dataset](https://www.openml.org/d/44152)

* **Measurement(s):** User behavior
* **Technology Type(s):** Web Site
* **Factor Type(s):** Experimental group
* **Sample Characteristic - Organism:** Homo sapiens
* **Sample Characteristic - Environment:** Internet

**Data Format:** CSV

* `user_id` → Unique identifier for each user
* `group` → A (control) or B (treatment)
* `behavior` → User’s measured behavior (e.g., click, purchase, visit duration)

---

## 📊 Project Workflow

1. **Data Collection**

   * Import dataset from OpenML (or provided CSV).
  
2. **Extract, Transform, Load**
3. **Chi-square test**
4. **Result Interpretation**

   * Does the treatment group (B) significantly outperform the control (A)?
   * Provide confidence intervals and recommendations.

5. **Visualization**

   * Bar plots, histograms, boxplots, confidence intervals.
6. **Experiment Web Application**

---

## ⚙️ Tech Stack

* Python (Pandas, NumPy, SciPy, Statsmodels)
* Matplotlib & Seaborn (visualization)
* Jupyter Notebook (experiments)

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/ab-testing-website-experiments.git
cd ab-testing-website-experiments
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run Jupyter Notebook:

```bash
jupyter notebook
```

4. Open `ab_testing_analysis.ipynb` to explore the results.

---

## 📌 Repository Structure

```
ab-testing-website-experiments/
│── data/                # Dataset (CSV)
│── notebooks/           # Jupyter notebooks
│── src/                 # Python scripts for analysis
│── results/             # Plots, statistical results
│── README.md            # Project documentation
│── requirements.txt     # Dependencies
```

