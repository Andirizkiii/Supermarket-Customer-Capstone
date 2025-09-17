# Supermarket Customer Analysis – Capstone Project

## 📌 Project Overview
This project is a **Data Analytics Capstone** focused on analyzing supermarket customer behavior.  
The goal is to explore customer demographics, purchasing patterns, and promotional responses to provide insights that can help businesses improve customer engagement, optimize marketing strategies, and increase sales.  

The analysis is based on the **Supermarket Customers dataset**, which contains customer profiles, product spending, promotion campaign responses, and purchase behavior.

---

## 📊 Dataset Description
The dataset includes customer demographics, product spending, promotion campaign responses, and purchase channels. Below are the key features:

### **People**
- `ID` – Unique customer identifier  
- `Year_Birth` – Year of birth  
- `Education` – Education level  
- `Marital_Status` – Marital status  
- `Income` – Yearly household income  
- `Kidhome` – Number of children in household  
- `Teenhome` – Number of teenagers in household  
- `Dt_Customer` – Date of customer enrollment  
- `Recency` – Days since last purchase  
- `Complain` – Complaint in last 2 years (1 = Yes, 0 = No)  

### **Products**
- `MntWines`, `MntFruits`, `MntMeatProducts`, `MntFishProducts`, `MntSweetProducts`, `MntGoldProds` – Amount spent on respective product categories (last 2 years)  

### **Promotion**
- `NumDealsPurchases` – Purchases made with a discount  
- `AcceptedCmp1`–`AcceptedCmp5` – Accepted offers in campaigns 1–5  
- `Response` – Accepted offer in the last campaign  

### **Place**
- `NumWebPurchases` – Purchases via website  
- `NumCatalogPurchases` – Purchases via catalog  
- `NumStorePurchases` – Purchases in store  
- `NumWebVisitsMonth` – Monthly website visits  

---

## 🎯 Objectives
1. **Understand customer demographics** – age distribution, income segmentation, household composition.  
2. **Analyze purchasing behavior** – spending distribution across different product categories.  
3. **Evaluate promotional campaigns** – effectiveness of past campaigns and customer response rates.  
4. **Study purchase channels** – website, catalog, and in-store preferences.  
5. **Generate actionable insights** – to help supermarkets design better marketing and engagement strategies.  

---

## 🛠 Tools & Technologies
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)  
- **Jupyter Notebook** for analysis and visualization  
- **Tableau Public** for interactive dashboards  
- **Excel/CSV** for dataset handling  

---

## 📈 Key Insights (Highlights)
- Spending is concentrated in **Wines and Meat Products**, while categories like Fruits and Gold are less popular.  
- Customers with **higher income** tend to spend more across all categories.  
- Response rates for marketing campaigns vary, with some campaigns performing significantly better than others.  
- Younger customers are more likely to engage in **online purchases**, while older customers prefer in-store transactions.  

---

## 📂 Repository Structure
```
📦 Supermarket_Customer_Capstone
 ┣ 📜 Supermarket_Customer_Capstone_Andi_Rizki.ipynb   # Jupyter Notebook with full analysis
 ┣ 📜 Supermarket Customers.csv                         # Dataset
 ┣ 📜 Supermarket Customers Data Dictionary.pdf         # Dataset dictionary
 ┗ 📜 README.md                                         # Project documentation
```

---

## 🚀 How to Use
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/supermarket-customer-capstone.git
   ```
2. Open the Jupyter Notebook:  
   ```bash
   jupyter notebook Supermarket_Customer_Capstone_Andi_Rizki.ipynb
   ```
3. Run the cells to reproduce the analysis and visualizations.  

---

## 📌 Author
**Andi Rizki Nofentri**  
Capstone Project – Data Analyst Bootcamp  
