# Task_Day_2
Data Visualization and Storytelling
# 📊 Superstore Data Visualization & Storytelling

This project presents a comprehensive visual analysis of the Superstore dataset using Tableau. The goal is to explore relationships between sales, profit, discounts, categories, shipping methods, and regional performance — and communicate insights effectively through data storytelling.

---

## 🔧 Tools Used

- **Google Colab** – For data cleaning and preparation using Python (Pandas)
- **Tableau** – For building interactive visualizations and dashboards
- **GitHub** – For version control and project submission

---

## 📁 Dataset

- **Source**: [Kaggle - Superstore Dataset](https://www.kaggle.com/)
- **File Used**: `Sample - Superstore.csv`

The dataset contains information about customer orders including sales, profit, discounts, categories, shipping details, and regional data.

---

## 🧼 Data Cleaning

The dataset was cleaned in **Google Colab**. Key steps included:
- Handled encoding issues while reading the CSV
- Dropped unnecessary columns (`Row ID`, `Product Name`)
- Combined discount values with profit to assess net profitability (if needed)
- Ensured correct date formatting for time series analysis

---

## 📊 Tableau Dashboard Overview

The final Tableau dashboard contains **7 worksheets** combined into a structured, interactive layout:

1. **Sales vs Profit Scatterplot** – Identifies how sales relate to profit across orders  
2. **Discount vs Profit Analysis** – Shows how discounting impacts profitability  
3. **Sales and Profit by Region** – Visualizes regional performance  
4. **Category Performance** – Highlights sales and profit by product category and sub-category  
5. **Order Time Series Analysis** – Tracks trends in sales and profit over time  
6. **Profit Analysis using Ship Mode** – Compares shipping modes in terms of profitability  
7. **Ship Mode Usage** – Shows the distribution of orders by shipping method

---

## 💡 Key Insights

- High discounts tend to reduce profitability significantly.
- Some regions consistently outperform others in sales and profit.
- Certain product categories drive more profit, while others often operate at a loss.
- First-Class and Standard Class are the most used shipping modes, but not always the most profitable.
- Seasonal trends impact both sales and profits — especially during year-end.

---

## 📤 Output

- The final **dashboard was exported as a PDF** and submitted as part of the project deliverables.
- You can find the dashboard PDF in this repository.

---

## 📎 Folder Structure

