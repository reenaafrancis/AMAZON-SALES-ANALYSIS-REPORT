# AMAZON-SALES-ANALYSIS-REPORT
A data analysis project exploring Amazon sales trends, product performance, and fulfillment efficiency using Python (Pandas, Matplotlib, Seaborn).
# 📊 Amazon Sales Data Analysis

## 📌 Project Overview
This project analyzes a dataset of **128,000+ Amazon sales transactions**. The goal is to extract actionable insights regarding sales trends, product popularity, fulfillment methods, and customer geographical distribution to help optimize business strategies.

## 📂 Dataset
The dataset contains transaction details including:
- **Order Details:** Order ID, Date, Status
- **Product Details:** Category, Size, Quantity, Amount
- **Customer Details:** City, State, B2B vs. Retail
- **Logistics:** Fulfillment Method (Amazon vs. Merchant)

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Libraries:**
  - `Pandas` (Data Manipulation & Cleaning)
  - `NumPy` (Numerical Operations)
  - `Matplotlib` & `Seaborn` (Data Visualization)
- **Environment:** Google Colab / Jupyter Notebook

## 🔍 Key Workflow
1. **Data Cleaning:**
   - Handled missing values in `Amount` and `currency`.
   - Dropped unrelated columns (`index`, `New`, `PendingS`).
   - Standardized `ship-state` names (e.g., converting "Goa" and "GOA" to a single format).
   - Converted `Date` column to proper datetime format.
2. **Exploratory Data Analysis (EDA):**
   - Analyzed monthly sales trends.
   - Segmented data by Product Category and Size.
   - Investigated fulfillment methods (FBA vs. Merchant).
3. **Visualization:** Created bar charts, line graphs, and pie charts to present findings.

## 📈 Key Insights
- **Total Revenue:** ~₹78.5 Million.
- **Top Category:** **T-shirts** are the highest-selling product category.
- **Top Sizes:** M, L, and XL account for the majority of sales.
- **Geographical Hotspots:** Maharashtra, Karnataka, and Uttar Pradesh are the top 3 states driving demand.
- **Fulfillment:** A significant portion of orders is fulfilled by Amazon (FBA), ensuring better delivery efficiency.

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR-USERNAME/Amazon-Sales-Analysis.git](https://github.com/YOUR-USERNAME/Amazon-Sales-Analysis.git)
   
