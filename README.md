# 🏦 Banking Loan Dataset — Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python) ![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter) ![Pandas](https://img.shields.io/badge/Pandas-EDA-green) ![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📦 Dataset

- **Domain:** Banking & Financial Services
- **Key Columns:** Employment Type, Age Group, Loan Amount, Annual Income, Interest Retained, Risk Score, Customer Segment (High-Value / Low-Value)

> The dataset is stored in the `/Data` folder of this repository.

---

## ❓ Business Questions Answered

| # | Question |
|---|----------|
| 1 | Who are our most profitable customers? |
| 2 | Which customer segments are the riskiest? |
| 3 | What drives interest generation? |
| 4 | Who should the bank target for upselling? |

---

## 📊 Key Insights

> **1. Employed customers are the most profitable** — Employed customers contribute the highest total interest retained, followed by self-employed customers.

> **2. Risk is uniform across all segments** — All employment segments show nearly identical risk scores, ranging from 3.94 to 4.01 per customer — a difference of only 1.8%. No single group is significantly riskier.

> **3. High-value customers borrow 6.4× more** — High-value customers take loans averaging **$71,115** vs **$11,160** for low-value customers — a 537% difference. They don't differ in age, income, or debt; they simply borrow more, pay higher rates, and commit to longer terms.

> **4. Income and loan size are strongly correlated** — Customers with higher annual incomes consistently take larger loans, forming a clear positive trend across all segments.

---

## 🗂️ Project Structure

```
Banking_Loan_Dataset/
├── Data/                  # Raw dataset
├── Notebooks/             # Jupyter analysis notebooks
├── Conclusion.md          # Business questions & key findings
├── requirements.txt       # Python dependencies
└── README.md
```

---

## 🛠️ Tools & Libraries

| Library | Purpose |
|---------|---------|
| `pandas` | Data loading, cleaning, aggregation |
| `numpy` | Numerical operations |
| `matplotlib` | Base visualizations |
| `seaborn` | Statistical plots & heatmaps |
| `scikit-learn` | Correlation & segment analysis |

---

## 📸 Sample Visualizations

> 📌 **Loan Amount: High-Value vs Low-Value Customers**
> *(Add your chart screenshot here — e.g., `![Loan Comparison](Data/charts/loan_segment_comparison.png)`)*

> 📌 **Interest Retained by Employment Type**
> *(Add your chart screenshot here)*

> 💡 **How to add screenshots:** Export your best notebook chart using `plt.savefig('chart.png', dpi=150, bbox_inches='tight')`, upload to the `/Data` folder, and replace the placeholders above.

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/ompatilm4-web/Banking_Loan_Dataset.git
cd Banking_Loan_Dataset

# Install dependencies
pip install -r requirements.txt

# Open the notebook
jupyter notebook Notebooks/
```

---

## 👤 Author

**Om Patil** · [GitHub](https://github.com/ompatilm4-web)