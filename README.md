# sleep-debt-public-health-analysis
# 😴 The Sleep Debt: A Public Health Analysis

**Author:** Precious Ayoola  
**Track:** Data Science  
**Domain:** Public Health & Lifestyle Analytics  
**Dataset:** Sleep Health and Lifestyle Dataset (Kaggle)

---

## 📌 Project Overview

In high-performance professional environments, sleep is often sacrificed in pursuit of productivity. But is this trade-off sustainable?

This project explores the **Sleep Health and Lifestyle dataset** to investigate whether occupational stress contributes to measurable sleep disruption and potential health risk patterns — using exploratory data analysis and storytelling through visualisation.

---

## 🎯 Research Questions

1. Does sleep quality improve consistently with longer sleep duration?
2. How do stress levels vary across different occupations?
3. Do lifestyle and health factors influence sleep outcomes?

---

## 📂 Repository Structure

```
sleep-health-public-analysis/
│
├── README.md
├── notebooks/
│   └── sleep_health_eda.ipynb        # Full EDA, visualisations & narrative insights
├── reports/
│   └── sleep_health_analysis.pdf     # Full project report
```

---

## 📊 Dataset

**Source:** [Sleep Health and Lifestyle Dataset](https://www.kaggle.com) via Kaggle

Key features include sleep duration, sleep quality, stress levels, BMI category, occupation, and diagnosed sleep disorders.

---

## 🔬 Methodology

### Data Cleaning & Preprocessing
- Handled null values in the `Sleep Disorder` column — NaN values replaced with `'None'` to represent individuals without diagnosed sleep conditions
- Consolidated `'Normal'` and `'Normal Weight'` BMI categories to remove redundancy and improve visualisation clarity

### Visualisation Design Principles
- Applied **minimalist aesthetics** using `sns.despine()` to remove unnecessary borders
- Used **neutral grey** for most professions with **red (#e74c3c)** highlighting Healthcare roles to draw attention to elevated stress levels
- Applied **sequential colour palette** for sleep quality trend charts to reflect natural progression
- Increased font sizes for titles and labels to enhance readability

---

## 💡 Key Findings

**The 7-Hour Threshold**
Sleep quality increases noticeably as individuals approach approximately seven hours of sleep. Beyond eight hours, improvements begin to plateau — suggesting the existence of an optimal recovery window.

**Occupational Stress Differences**
Healthcare professionals report the highest average stress levels compared to all other occupations analysed. This pattern suggests that professional environment plays a substantial role in sleep health outcomes.

---

## 🛠️ Tools & Libraries

- **Python** (Pandas, NumPy)
- **Visualisation:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

---

## ⚙️ How to Run

1. Clone this repository:
```bash
git clone https://github.com/spring-geek/sleep-health-public-analysis.git
```

2. Install dependencies:
```bash
pip install pandas matplotlib seaborn jupyter
```

3. Download the dataset from [Kaggle](https://www.kaggle.com) and place it in the project folder

4. Open and run the notebook:
```
notebooks/sleep_health_eda.ipynb
```

---

## 📄 License

This project was completed as part of the AltSchool Africa Data Science programme (Baraka 2025 Cohort).  
Dataset credit: Kaggle.
