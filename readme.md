# 🎬 Netflix Data Analysis | EDA using Python & Seaborn

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-1.5+-darkblue?style=flat&logo=pandas)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12+-teal?style=flat)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.6+-orange?style=flat)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)
![Level](https://img.shields.io/badge/Level-Beginner%20Friendly-yellow?style=flat)

---

## 📌 About the Project

This is a personal data analysis project where I explored the **Netflix Movies and TV Shows dataset** from Kaggle using Python.

The goal was to practise real-world data analysis skills — cleaning messy data, finding patterns, and telling a story through visualisations.

> 🗂️ Dataset Source: [Kaggle — Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)

---

## 🎯 What I Did

- Cleaned and prepared a dataset of **8,800+ Netflix titles**
- Handled missing values, parsed dates, and engineered new features
- Performed **Exploratory Data Analysis (EDA)** across genres, countries, ratings, and years
- Built **15+ visualisations** to uncover trends and patterns
- Summarised findings into simple **business insights**

---

## 📊 Key Findings

| Finding | Insight |
|---------|---------|
| 🎬 Content Split | ~70% Movies, ~30% TV Shows |
| 🌍 Top Country | United States is #1, India is #2 |
| 📈 Growth | Netflix content grew rapidly after 2015 |
| 🎭 Top Genre | Dramas and International Movies dominate |
| ⭐ Top Rating | TV-MA is the most common content rating |
| 🕐 Peak Month | October sees the most content additions |

---

## 🛠️ Tools & Libraries Used

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data loading and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Base visualisations |
| Seaborn | Statistical charts and styling |
| SciPy | Statistical hypothesis testing |
| Jupyter Notebook | Development environment |

---

## 📁 Project Structure

```
netflix-data-analysis/
│
├── Netflix_Content_Analysis.ipynb   ← Main notebook
├── requirements.txt                 ← All dependencies
├── README.md                        ← You are here
└── netflix_titles.csv               ← Dataset (download from Kaggle)
```

---

## 🚀 How to Run

**Step 1 — Clone the repository**
```bash
git clone https://github.com/yourusername/netflix-data-analysis.git
cd netflix-data-analysis
```

**Step 2 — Install dependencies**
```bash
pip install -r requirements.txt
```

**Step 3 — Download the dataset**
```bash
# Option A: Kaggle CLI
kaggle datasets download -d shivamb/netflix-shows
unzip netflix-shows.zip

# Option B: Download manually from
# https://www.kaggle.com/datasets/shivamb/netflix-shows
```

**Step 4 — Open the notebook**
```bash
jupyter notebook Netflix_Content_Analysis.ipynb
```

---

## 📸 Visualisations Included

- 🍩 Movies vs TV Shows — Donut Chart
- 📈 Content Growth Over Years — Stacked Area Chart
- 🌍 Top 15 Countries — Horizontal Bar Chart
- 🎭 Genre Popularity — Bar + Bubble Chart
- ⭐ Rating Distribution — Count Plot
- ⏱️ Movie Runtime — Histogram + Box Plot
- 🗓️ Monthly Trends — Heatmap
- 🎬 Top Directors — Bar Chart
- 📊 Executive Dashboard — 4-Panel Summary
- 🔗 Correlation Matrix — Heatmap

---

## 📐 Statistical Analysis

- One-sample **t-test** — Movie runtime vs 90-min benchmark
- **Chi-square test** — Rating vs Content Type independence
- **Spearman correlation** — Release year vs Movie runtime
- **95% Confidence Interval** — Mean movie runtime

---

## 💡 Business Insights

1. India and South Korea are fast-growing content markets
2. Mature-rated (TV-MA) content dominates the catalogue
3. Most TV Shows have only 1 season — mini-series strategy
4. October is the best month for big content drops
5. Dramas and International content are the fastest-growing genres

---

## 🙋 About Me

**Ishita Sharma**  
First Year Student | Aspiring Data Analyst  

📧 kimishita226@gmail.com 

🔗 [LinkedIn](https://www.linkedin.com/in/ishita-sharma-2151a438b/)

🐙 [GitHub](https://github.com/ishshsh21)

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

> ⭐ If you found this project helpful, please give it a star on GitHub!