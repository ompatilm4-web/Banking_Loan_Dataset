<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,12,19&height=200&section=header&text=Banking%20Loan%20Dataset%20EDA&fontSize=44&fontColor=ffffff&fontAlignY=38&desc=Exploratory%20Data%20Analysis%20%7C%20Loan%20Default%20Prediction%20%7C%20Python&descAlignY=58&descSize=14&animation=fadeIn" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=16&pause=1000&color=34D399&center=true&vCenter=true&width=650&lines=Analysing+loan+default+patterns+%F0%9F%8F%A6;Raw+data+%E2%86%92+Cleaned+%E2%86%92+Encoded+%E2%86%92+Insights+%F0%9F%92%A1;Who+defaults%3F+Why%3F+When%3F+%F0%9F%94%8D;Built+as+a+portfolio+EDA+project+%F0%9F%93%81)](https://git.io/typing-svg)

<br/>

[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge)](https://matplotlib.org)
[![Seaborn](https://img.shields.io/badge/Seaborn-4c72b0?style=for-the-badge)](https://seaborn.pydata.org)
[![Stars](https://img.shields.io/github/stars/ompatilm4-web/Banking_Loan_Dataset?style=for-the-badge&color=fbbf24&logo=github)](https://github.com/ompatilm4-web/Banking_Loan_Dataset/stargazers)

</div>

---

## 📌 About This Project

This project performs **Exploratory Data Analysis (EDA)** on a real-world banking loan default dataset — starting from raw, uncleaned records and working through to actionable insights on borrower behaviour and default risk.

The core question driving the analysis:

> **What patterns in borrower data are associated with loan defaults — and how can they be identified early?**

The full pipeline covered:

```
Raw Loan Data  →  Cleaning  →  Encoding  →  Analysis  →  Visualization  →  Insights
```

---

## 🗂️ Repository Structure

```
Banking_Loan_Dataset/
│
├── Data/
│   ├── loan_default_raw_dataset.csv   ← Original dataset, unmodified
│   ├── Cleaned_Data.csv               ← After handling nulls, duplicates, type fixes
│   └── Encoded_Data.csv               ← After categorical encoding for analysis
│
├── Notebooks/
│   ├── Analysis.ipynb                 ← Cleaning, EDA, statistical summaries
│   └── Visualization.ipynb            ← Charts, plots, and visual insights
│
├── Conclusion.md                      ← Key findings and business takeaways
├── requirements.txt                   ← Python dependencies
└── README.md
```

---

## 📓 Notebooks

### 🔍 `Analysis.ipynb`

The core EDA notebook — covers the full data preparation and analysis pipeline:

| Stage | What was done |
|---|---|
| **Data Loading** | Loaded `loan_default_raw_dataset.csv`, inspected shape, dtypes, null counts |
| **Cleaning** | Handled missing values, removed duplicates, corrected data types → `Cleaned_Data.csv` |
| **Encoding** | Encoded categorical columns (loan purpose, employment type, etc.) → `Encoded_Data.csv` |
| **Univariate Analysis** | Distribution of loan amounts, interest rates, income, tenure |
| **Bivariate Analysis** | Default rate vs. credit score, income, loan amount, employment length |
| **Statistical Summary** | Correlation matrix, `describe()`, groupby aggregations by default status |

---

### 📊 `Visualization.ipynb`

All visual outputs from the analysis, built with Matplotlib and Seaborn:

| Chart Type | Insight explored |
|---|---|
| Bar charts | Default rate across loan purpose, employment type, home ownership |
| Histograms | Distribution of loan amount, annual income, interest rate |
| Heatmap | Correlation matrix across all numeric features |
| Boxplots | Loan amount and income spread — defaulters vs. non-defaulters |
| Count plots | Class imbalance check — default vs. non-default frequency |
| Scatter plots | Income vs. loan amount coloured by default status |

---

## 📂 Data Pipeline

| File | Description |
|---|---|
| `loan_default_raw_dataset.csv` | Original source data — untouched |
| `Cleaned_Data.csv` | Post-cleaning: nulls handled, types fixed, duplicates removed |
| `Encoded_Data.csv` | Post-encoding: categorical columns converted for numerical analysis |

> Each stage is saved separately so every step of the pipeline is fully reproducible and auditable.

---

## 📋 Conclusion

Key findings from the analysis are documented in [`Conclusion.md`](./Conclusion.md).

Themes covered include:
- Which borrower profiles carry the highest default risk
- How loan amount and interest rate interact with default likelihood
- Features most correlated with default status
- Recommendations for further modelling (classification, risk scoring)

---

## 🚀 Getting Started

**1 — Clone**
```bash
git clone https://github.com/ompatilm4-web/Banking_Loan_Dataset.git
cd Banking_Loan_Dataset
```

**2 — Create virtual environment**
```bash
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
```

**3 — Install dependencies**
```bash
pip install -r requirements.txt
```

**4 — Open notebooks**
```bash
jupyter notebook
```

Start with `Notebooks/Analysis.ipynb`, then move to `Notebooks/Visualization.ipynb`.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| 🐍 Python | Core language |
| 📓 Jupyter Notebook | Interactive analysis environment |
| 🐼 Pandas | Data cleaning, manipulation, aggregation |
| 📈 Matplotlib | Base plotting and chart customization |
| 🎨 Seaborn | Statistical visualizations |

---

## 🤝 Contributing

```bash
git checkout -b improve/analysis-section
git commit -m "Improve: add default rate breakdown by credit score band"
git push origin improve/analysis-section
```

---

<div align="center">

**Built and maintained by [Om Patil](https://github.com/ompatilm4-web)**

[![GitHub](https://img.shields.io/badge/GitHub-ompatilm4--web-181717?style=flat-square&logo=github)](https://github.com/ompatilm4-web)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,12,19&height=120&section=footer&animation=fadeIn" width="100%"/>

> ⭐ If this project helped you understand EDA on financial data, drop a star — it helps others find it.

</div>