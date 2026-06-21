## Coffee-Sales-Analysis
### Project Overview
 
### This report provides a comprehensive analysis of coffee sales from a vending machine. 
It explores revenue trends, customer behaviors, and key sales patterns to support data-driven business decisions.
### 🚀 Features & Analysis Inside

The Jupyter Notebook breaks down the data into key business insights:

### 1. Data Processing & Exploration
* Initial data sanity checks using `.head()` (`image_15e5fd.jpg`) and `.info()` (`image_15e65e.jpg`).
* Handling anonymized unique identifiers for card purchases.

### 2. Product Popularity & Sales Volume
* Identification of the most ordered drinks via item counts.
* **Top Selling Item:** *Americano with Milk* leads the sales volume with **764 orders**, closely followed by *Latte* with **714 orders** (`image_15e65e.jpg`).

### 3. Financial Analysis & Revenue Breakdown
* **Highest Revenue Generator:** *Latte* generates the highest overall revenue bringing in **25,434.62**, followed by *Americano with Milk* at **23,417.52** (`image_15e63e.jpg`).
* **Payment Preference:** A massive share of transactions comes from **Card payments (3,174)** compared to just **Cash payments (89)** (`image_15e63e.jpg`).

### 4. Advanced Visualizations
* **Revenue by Coffee Type and Payment Method:** A grouped bar chart displaying pricing variations/revenue behavior across payment methods (`image_15e61d.jpg`).
* **Customer Loyalty Tracking:** A frequency distribution plot (`image_15e56e.jpg` or `image_15e67e.jpg`) identifying the most frequent coffee buyers based on their anonymized card counts.

---

## 🛠️ Tech Stack & Libraries Used

* **Python 3**
* **Pandas:** For data cleaning, structural exploration, and group-by aggregations.
* **NumPy:** For numerical computing.
* **Matplotlib:** For structuring and rendering customizable plots.
* **Seaborn:** For statistical plotting, count plots, and customized color palettes (`rocket`).

---

## 📈 Key Insights

* **Digital Over Cash:** Over 97% of users prefer paying by card at the vending machine. Adding smoother contactless/NFC systems could optimize this further.
* **The Latte Effect:** Even though *Americano with Milk* is bought more frequently, *Latte* generates more revenue due to a higher price point per unit.

---
