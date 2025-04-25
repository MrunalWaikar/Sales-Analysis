# Sales-Analysis
# 📊 Sales Analysis

An end-to-end data analysis project to uncover business insights from sales data using Python. The project explores trends, patterns, and key performance indicators to help stakeholders make data-driven decisions.

---

## 📌 Objective

To analyze sales data over time to answer critical business questions such as:

- Which month had the highest sales?
- Which city had the most sales?
- When should advertisements be displayed for maximum impact?
- What product combinations are frequently bought together?
- What products sell the most and why?

---

## 🧰 Tools & Technologies

- **Programming Language**: Python
- **Libraries**:  
  - `Pandas` – for data manipulation  
  - `NumPy` – for numerical operations  
  - `Matplotlib` & `Seaborn` – for data visualization  
- **Environment**: Jupyter Notebook

---

## 📁 Dataset

- **Source**: Sales data compiled from multiple CSV files (usually monthly reports).
- **Features**:
  - `Order ID`
  - `Product`
  - `Quantity Ordered`
  - `Price Each`
  - `Order Date`
  - `Purchase Address`

---

## 🧠 Key Steps

1. **Data Collection**: Combine all monthly CSVs into one dataset.
2. **Data Cleaning**:
   - Remove NaN entries
   - Fix data types
   - Drop duplicates
3. **Feature Engineering**:
   - Extract month, city, and hour from datetime
   - Calculate total sales per order
4. **Exploratory Data Analysis (EDA)**:
   - Sales per month
   - Sales per city
   - Best time for advertisements
   - Common product pairs
   - Most sold products

---

## 📈 Insights & Visualizations

- 📅 **Best Month**: Month X with $Y in sales  
- 🏙️ **Top City**: City Z generated the most revenue  
- ⏰ **Best Time to Advertise**: Around hour H  
- 🛍️ **Frequent Product Combo**: Product A + Product B  
- 🧺 **Best Selling Product**: Product P with highest volume

*Note: Replace placeholders above with actual insights from your analysis.*

---

## 🚀 Getting Started

### 📦 Install Requirements

```bash
pip install pandas numpy matplotlib seaborn
