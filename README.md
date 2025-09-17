# Supermarket Customer Capstone

A complete capstone project analyzing supermarket customer behavior: demographics, spending patterns, promotion responses, and channel preferences. Includes a fully English Jupyter Notebook and reproducible workflow.
  
## 📦 Repository Structure

```
supermarket-customer-capstone-github/
├─ notebooks/
│  ├─ Supermarket_Customer_Capstone_English.ipynb
├─ data/
│  └─ supermarket_customers.csv
├─ docs/
│  └─ Supermarket_Customers_Data_Dictionary.pdf
├─ reports/
├─ requirements.txt
├─ .gitignore
├─ LICENSE
└─ README.md
```

## 🧰 Tech Stack
- Python, Jupyter Notebook
- pandas, numpy, matplotlib, seaborn
- scikit-learn (optional, if you do modeling/segmentation)

## 🚀 Getting Started

1. **Clone** this repo and move into it:
   ```bash
   git clone <your-repo-url>.git
   cd supermarket-customer-capstone-github
   ```

2. **Create and activate** a virtual environment (recommended):
   ```bash
   python -m venv .venv
   # Windows: .venv\Scripts\activate
   # macOS/Linux:
   source .venv/bin/activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter** and open the notebook:
   ```bash
   jupyter notebook notebooks/Supermarket_Customer_Capstone_English.ipynb
   ```

## 🗂️ Dataset
- File: `data/supermarket_customers.csv`
- Dictionary: `docs/Supermarket_Customers_Data_Dictionary.pdf`
- Source columns include: demographics (age, income, family), product spends (wines, meats, fruits, fish, sweets, gold), promotions (campaigns, deals), and channels (web, catalog, store, web visits).

## 📊 What’s Inside the Notebook
- Problem framing & business objectives
- Data cleaning & feature engineering (e.g., age, family size, recency buckets)
- EDA & visualizations
- Marketing insights & customer segments (optional)
- Recommendations & next steps

## 🧪 Reproducibility
- All plots and analyses run using `requirements.txt`.
- Data used is included in `data/` for easy execution.

## 📄 License
This project is licensed under the MIT License — see `LICENSE` for details.
