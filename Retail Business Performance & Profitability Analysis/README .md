# Elevate_Labs_Project
# Retail Business Performance and Profitability Analysis

## 📌 Project Overview

This project focuses on analyzing transactional retail data to uncover key insights into business performance and profitability.  
The primary objectives include:

- Identifying profit-draining categories  
- Optimizing inventory turnover  
- Understanding seasonal product behavior  

These insights drive strategic suggestions to improve retail operations.

---

## 🛠 Key Tools Used

- **SQL (SQLite)**: For data import, cleaning, aggregation, and calculating profit margins.  
- **Python (Pandas, Seaborn, Matplotlib)**: For data manipulation, correlation analysis, and trend visualization.  
- **Tableau**: For creating interactive dashboards with dynamic exploration features.

---

## 📁 Project Structure
.
├── Cleaned_Superstore_Dates.csv             # Cleaned dataset after initial processing

├── EDA_and_Correlation (1).ipynb            # Jupyter Notebook for Python EDA and correlation

├── Retail_Business_Performance_Project.PNG  # Screenshot of the Tableau Dashboard

├── Sample - Superstore (1).csv              # Original raw dataset

├── category_profitability.csv               # CSV output of SQL query for category profitability

├── README.md                                # This README file

├── Project_Report.docx                      # Comprehensive project report (MS Word format)

└── Retail_Business_Performance_Project.twb  # Tableau Workbook file


---

## 🧪 Mini Guide: How to Replicate the Analysis

### 1. **Data Acquisition**
- Start with `Sample - Superstore (1).csv` as your raw data.

### 2. **Data Cleaning and Preparation (Python)**
- Open `EDA_and_Correlation (1).ipynb`
- Run the first cell to:
  - Load raw CSV
  - Clean date columns (`Order Date`, `Ship Date`)
  - Save as `Cleaned_Superstore_Dates.csv`

### 3. **SQL Data Import and Analysis (SQLite)**
- In the same notebook, run the final cell to:
  - Create in-memory SQLite DB
  - Load `Cleaned_Superstore_Dates.csv`
  - Run SQL query to compute `Profit_Margin` by Category/Sub-Category
  - Save as `category_profitability.csv`

### 4. **Python EDA and Correlation**
- Run remaining notebook cells to:
  - Inspect data (head, columns, nulls)
  - Engineer time-based features (Year, Month, Quarter, Order_Month)
  - Group and analyze profits
  - Simulate inventory metrics
  - Visualize trends and correlation heatmaps

### 5. **Tableau Dashboard Development**
- Open `Retail_Business_Performance_Project.twb` in Tableau Desktop
- Ensure it connects to `Cleaned_Superstore_Dates.csv`
- Explore filters: Region, Product Type, Season

---

## 📦 Deliverables

- **Interactive Dashboard**:  
  [🔗 Retail Business Performance Dashboard on Tableau Public](https://public.tableau.com/app/profile/bhavishya.priyadarshini.v/viz/Retail_Business_Performance_Project/RetailBusinessPerformanceDashboard?publish=yes)

- **SQL Analysis**:
  - Queries included in the notebook
  - Output in `category_profitability.csv`

- **Project Report**:  
  `Project_Report.docx` contains findings, visualizations, and recommendations.

- **Python Notebook**:  
  `EDA_and_Correlation (1).ipynb`

- **Cleaned Dataset**:  
  `Cleaned_Superstore_Dates.csv`

---

## 📊 Key Insights and Strategic Suggestions

### 🔍 Insights
- **Profit Drainers**: "Tables" and "Bookcases" show consistent negative margins.
- **Seasonal Peaks**: Sales surge during Q4, ideal for targeted campaigns.
- **Discount-Profit Correlation**: Negative impact suggests discounting needs strategy.

### ✅ Strategic Suggestions
- **Re-evaluate Unprofitable Products**: Consider bundling or replacement.
- **Optimize Inventory**: Use data insights to clear overstock and improve turnover.
- **Leverage Seasonality**: Focus on high-performing categories during Oct–Dec.
- **Smarter Discounts**: Value-added deals > blanket price cuts.
- **Region-Specific Strategy**: Utilize Tableau dashboard insights for regional plans.

---

## 🤝 How to Contribute

Feel free to fork this repository, suggest improvements, or submit pull requests.  
Contributions that improve the analysis, visuals, or documentation are welcome!

---

**Author**: Bhavishya Priyadarshini V  
