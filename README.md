# 12-Month Sales Data Analysis

## Project Overview

This project conducts a comprehensive analysis of 12 months of sales data from an electronics store. The goal is to clean and preprocess the raw data, and then explore it to uncover key insights and answer pressing business questions.

The analysis is performed using Python with the **Pandas** and **Matplotlib** libraries within a **Jupyter Notebook**.

---

## Key Questions & Insights

This analysis answers several key business questions, with the main findings and visualizations summarized below.

### 1. What was the best month for sales?
The data shows a clear trend, with sales peaking in **December**. This is likely due to holiday shopping. The lowest sales month was **January**.

![Monthly Sales Chart](images/monthly_sales.png)

### 2. What US city had the highest number of sales?
**San Francisco, CA** generated the most revenue, likely due to its status as a major tech hub with high purchasing power.

![City Sales Chart](images/city_sales.png)

### 3. What time of day is best for advertising?
To maximize the likelihood of customers buying products, advertisements should be targeted just before the peak purchasing hours. The data suggests the best times are around **11 AM** and **7 PM**.

![Hourly Sales Chart](images/hourly_sales.png)

### 4. What products are most often sold together?
By analyzing orders with multiple items, we found that the most common product pairings are often an expensive primary product (like a phone) and a cheaper accessory (like a charging cable or headphones).

**Top 3 Most Commonly Sold Together (3 items):**
1.  Google Phone, USB-C Charging Cable, Wired Headphones
2.  iPhone, Lightning Charging Cable, Wired Headphones
3.  iPhone, Lightning Charging Cable, Apple Airpods Headphones

### 5. What product sold the most?
**AAA Batteries (4-pack)** and **AA Batteries (4-pack)** were the most sold products by quantity. An analysis of product price vs. quantity ordered suggests a strong correlation: cheaper products tend to sell in higher volumes.

![Product Sales Chart](images/product_sales.png)

---

## How to Use

To run this analysis on your own machine, please follow these steps:

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/your-username/sales-data-analysis.git](https://github.com/your-username/sales-data-analysis.git)
    cd sales-data-analysis
    ```

2.  **Set up a Virtual Environment (Recommended)**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Download the Data**
    * The dataset for this project is not included in the repository.
    * You can download it from Keith Galli's GitHub repository here: [Sales-Data](https://github.com/KeithGalli/Sales-Analysis/tree/master/Sales_Data)
    * Create a folder named `Sales_Data` in the root of this project and place all 12 `.csv` files inside it.

5.  **Run Jupyter Notebook**
    ```bash
    jupyter notebook
    ```
    Now you can open `Sales Analysis.ipynb` and run the cells.

---

## Libraries Used
* Python 3
* Pandas
* Matplotlib
* Jupyter Notebook
