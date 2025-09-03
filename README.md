# Customer-Segmentation-Using-RFM-Analysis-in-E-Commerce

📌 Project Overview

E-commerce businesses generate vast amounts of transactional data but often fail to fully leverage it for actionable insights. The goal of this project is to segment customers using RFM (Recency, Frequency, Monetary) analysis to:

Identify high-value customers

Detect at-risk and dormant segments

Improve customer retention and lifetime value through targeted strategies

This project uses Python for analysis, a dashboard for visualization, and a presentation for business insights.

📊 Dataset

Source: [Kaggle – E-commerce Dataset](https://www.kaggle.com/datasets/carrie1/ecommerce-data)

Size: 541,909 rows × 8 columns

Timeframe: 01-Dec-2010 to 09-Dec-2011

Key Features:

InvoiceNo – Unique transaction ID

StockCode – Product identifier

Description – Product details

Quantity – Number of items purchased

InvoiceDate – Purchase timestamp

UnitPrice – Price per unit (GBP)

CustomerID – Unique customer identifier

Country – Customer location

🛠 Data Cleaning & Preprocessing

Removed missing values in CustomerID (~25%)

Dropped 5525 duplicate rows

Excluded cancelled orders (InvoiceNo starting with "C")

Filtered out non-product StockCodes

📈 Methodology
RFM Framework

Recency (R): Days since last purchase

Frequency (F): Number of purchases

Monetary (M): Total spending

Each customer is ranked into 5 buckets for R, F, and M, then combined into an RFM score.

Segmentation Results

High Value Customers – Recent, frequent, and high-spending buyers

Strategy: Loyalty programs, exclusives

Loyal Customers – Consistent buyers with moderate activity

Strategy: Upselling & cross-selling

At-Risk Customers – Infrequent purchases, moderate recency

Strategy: Personalized promotions, win-back emails

Dormant Customers – Low activity, high churn risk

Strategy: Re-engagement campaigns, surveys

📊 Dashboard

A dashboard was created to visualize customer segments and RFM distribution.

🚀 Tech Stack

Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly)

Jupyter Notebook for analysis

Dashboard (interactive visualization)

PowerPoint Presentation for business insights- [Analysis](https://docs.google.com/presentation/d/1_kCWJfMuMT_DjQVXmGN-wETCHoTZhhiB/edit?usp=sharing&ouid=117160414401161637688&rtpof=true&sd=true)

📂 Repository Structure
📁 Ecommerce-Customer-Segmentation
│── 📄 Ecommerce_Data_Analysis.ipynb     # Data cleaning, RFM analysis, segmentation
│── 📄 dashboard/                        # Dashboard code/files
│── 📄 README.md                         # Project documentation

📑 Presentation

The detailed presentation summarizing problem statement, methodology, results, and recommendations can be accessed here:

👉 Google Drive Link to PPT
