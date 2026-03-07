# E-Commerce Sales Performance Analysis: Amazon India Case Study

##  Project Overview

In the highly competitive e-commerce landscape, data-driven decision-making is the key to operational excellence and revenue growth. This project performs an extensive **Exploratory Data Analysis (EDA)** on a dataset of **128,000+ transactions** from Amazon India.

As the **Data and Business Analyst**, my objective was to analyze sales trends, evaluate fulfilment efficiency, and understand customer purchasing patterns across various product categories and geographic regions.

---

##  Business Problem & Objectives

The primary goal of this analysis is to provide the management team with a clear picture of the business health and identify bottlenecks in the supply chain.

### Key Research Questions:

1. **Sales Performance:** Which product categories (e.g., Kurta, Western Dress, Set) are the primary revenue drivers?
2. **Order Status Analysis:** What is the ratio of successful deliveries vs. cancellations, and what are the potential causes for the latter?
3. **Fulfilment Strategy:** How does the performance of "Merchant-fulfilled" (Easy Ship) compare with "Amazon-fulfilled" orders in terms of reach and status?
4. **Geographic Demand:** Which states and cities represent the highest demand hubs for specific apparel styles?
5. **B2B vs. B2C:** What is the contribution of B2B transactions to the overall sales volume?

---

##  Dataset Description

The dataset consists of **128,949 rows** and **23 columns**, providing a granular view of every order.

| Feature | Description |
| --- | --- |
| `Order ID` | Unique identifier for each customer order. |
| `Date` | Transaction date (covering a 3-month period in 2022). |
| `Status` | Current state of the order (Shipped, Cancelled, Delivered, etc.). |
| `Fulfilment` | Method of fulfilment (Amazon vs. Merchant). |
| `Category` | Type of product (Kurta, Set, Western Dress, Top, etc.). |
| `Size` | Product size (S, M, L, XL, XXL, etc.). |
| `Amount` | Total transaction value in INR. |
| `Ship-City / State` | Geographic destination of the order. |
| `B2B` | Boolean indicator for Business-to-Business transactions. |

---

##  Tech Stack & Methodology

### Technologies Used:

* **Python 3.x:** Core analysis and automation.
* **Pandas:** Data wrangling and complex transformations.
* **Matplotlib & Seaborn:** Statistical data visualization.
* **Jupyter Notebook:** Interactive development and documentation.

### Analysis Workflow:

1. **Data Integrity Check:** Handled missing values in `Amount` and `Courier Status`, and cleaned up redundant columns like `Unnamed: 22`.
2. **Temporal Analysis:** Analyzed sales volume over time to identify peak shopping days and seasonality.
3. **Product Profiling:** Segmented sales by `Category` and `Size` to determine inventory velocity.
4. **Geospatial Analysis:** Visualized the distribution of orders across Indian states to identify logistics hotspots.
5. **Fulfilment Benchmarking:** Evaluated delivery success rates across different shipping service levels.

---

##  Key Insights (Executive Summary)

* **Category Dominance:** 'Sets' and 'Kurtas' account for the majority of the revenue, indicating a high demand for ethnic wear.
* **Fulfilment Efficiency:** Over **70% of orders** are fulfilled by Amazon, which correlates with a higher percentage of "Shipped - Delivered" statuses compared to merchant fulfilment.
* **Regional Hotspots:** Maharashtra and Karnataka emerge as the top-performing states, with cities like Mumbai and Bengaluru leading in order volume.
* **Cancellations:** A significant portion of 'Cancelled' orders occurs before shipping, suggesting a need for better "checkout-to-shipment" conversion strategies.

---

## 🚀 How to Run

1. **Clone the Repository:**
```bash
git clone https://github.com/vnandini879/E-commerce-Amazaon-sale-analysis/.git

```


2. **Install Dependencies:**
```bash
pip install pandas matplotlib seaborn

```


##  Author

**[Nandini Verma]**

* **Role:** Data and Business Analyst
---

*Note: This analysis is based on a public dataset and is intended for portfolio and business demonstration purposes.*
