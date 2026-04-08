# [Project Title]
*E-commerce-Store-Analysis.*

## 📖 Table of Contents
- [Project Overview](#-project-overview)
- [Tools & Technologies](#-tools--technologies)
- [Data Cleaning & Preparation](#-data-cleaning--preparation)
- [Key Insights](#-key-insights)
- [Visualization]_(#-visualization)
  
## 📊 Project Overview
-This project focuses on transforming raw, multi-dimensional e-commerce data into a functional business intelligence tool. By merging customer demographics, product details, and store locations, the analysis uncovers critical trends in regional sales, inventory movement, and customer loyalty. The final dashboard provides actionable insights.
 
## 🛠️ Tools & Technologies
- Software: Microsoft Excel (Advanced)
- Core Functions: VLOOKUP, HLOOKUP, INDEX, IFISBLANK, TRIM, PROPER
- Analysis Tools: Pivot Tables, Data Formatting (Currency, Text, Date)
- Visualization: Interactive Charts (Line, Bar, Pie) and Dashboard Design

## 🧹 Data Cleaning & PreparationQuantity Sold: A bar chart ranking top-performing products.

- Customer_Dim: Standardized naming conventions using TRIM and PROPER and unified Customer IDs.
- Product_Dim: Calculated average/total costs and handled missing stock data using IFISBLANK.
- Store_Dim: Integrated geographic data into the main sales table via lookups.
- Sales_Fact: Cleaned order dates, imputed missing quantities/prices using MODE and AVERAGE, and calculated total prices after discounts.
- Merging: Consolidated all dimensions into a single master table for Pivot Table generation using VLOOKUP and INDEX.

## 💡 Key Insights

- Regional Performance Imbalance: Identified a significant sales drop-off in the West region, while the East, North, and South maintain stable, high performance.
- Top Product Performance: Confirmed that "Amazon Echo Dot" and "Apple iPhone" are the primary volume drivers for the store.
- Regional Variety: The East region consistently leads in both the variety and volume of products sold across all categories. 
  

## Visualization
- Quantity Sold: A bar chart ranking top-performing products.
- Products Sold in each Region: A horizontal bar chart showcasing inventory distribution.
- Sales in each Region: A line chart highlighting the geographic performance gap.
