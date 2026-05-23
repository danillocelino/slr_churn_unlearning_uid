# slr_churn_unlearning_uid

# SLR — Machine Unlearning × Churn Prediction × Personal Data Identifiers

Systematic Literature Review following Kitchenham (2007) + PRISMA 2020.
**Period:** January 2022 – December 2025 · **Final corpus:** 11 articles from 967 unique records.

---

## Requirements

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

---

## Repository Structure

```
slr-machine-unlearning-churn/
├── databases/
│   ├── scopus.csv
│   ├── springer.csv
│   ├── ieee.csv
│   ├── acm.csv
│   └── webofscience.csv
├── 01_deduplication.ipynb
└── README.md
```

---

## How to Run

```bash
# 1. Clone the repository
git clone https://github.com/your-username/slr-machine-unlearning-churn.git
cd slr-machine-unlearning-churn

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# 3. Launch the notebook
jupyter notebook 01_deduplication.ipynb
```

The notebook loads all five CSVs from the `databases/` folder, merges them, removes duplicates by DOI and title matching, and outputs summary statistics and charts of the deduplicated corpus.

---

## Data Sources

| Database | Raw records | Unique |
|---|---|---|
| IEEE Xplore | 390 | 349 |
| ACM Digital Library | 273 | 261 |
| Springer Link | 250 | 250 |
| Scopus | 83 | 82 |
| Web of Science | 50 | 25 |
| **Total** | **1 046** | **967** |

---


