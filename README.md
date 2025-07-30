<div align="center">
  <img src="https://th.bing.com/th/id/OIP.P5CGJXVwzlPYCbLfL7LEqgHaDt?w=322&h=174&c=7&r=0&o=7&dpr=1.3&pid=1.7&rm=3" alt="Nykaa Banner" width="600"/>
</div>

# Nykaa Cosmetics Data Analysis

### "Your Beauty, Our Passion" - A Deep Dive into the Data

[![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-1.5-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.8-013243?style=for-the-badge&logo=matplotlib&logoColor=white)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.13-024A6D?style=for-the-badge&logo=seaborn&logoColor=white)](https://seaborn.pydata.org/)
[![Plotly](https://img.shields.io/badge/Plotly-5.18-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Lab-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/en-us/)

---

## 📖 Table of Contents
1. [About The Project](#-about-the-project)
2. [Project Objectives](#-project-objectives)
3. [Tech Stack](#-tech-stack)
4. [The Analysis Workflow](#-the-analysis-workflow)
    - [📈 Stock Data Analysis](#-stock-data-analysis)
    - [💬 Sentiment Analysis of App Reviews](#-sentiment-analysis-of-app-reviews)
    - [🛍️ Product Portfolio Analysis (2022-2023)](#-product-portfolio-analysis-2022-2023)
5. [Key Insights & Conclusion](#-key-insights--conclusion)
6. [Future Scope](#-future-scope)
7. [Getting Started](#-getting-started)
8. [Author & Acknowledgments](#-author--acknowledgments)

---

## 📌 About The Project

This project presents a comprehensive data analysis of **Nykaa**, a leading Indian e-commerce company specializing in beauty and wellness products. By leveraging a rich dataset encompassing stock performance, product details, and customer reviews, this analysis aims to extract actionable insights that can inform business strategies, enhance customer engagement, and drive growth.

The analysis delves into customer preferences, purchasing behaviors, product performance, and marketing effectiveness to provide a 360-degree view of Nykaa's market position. The findings are visualized through interactive dashboards and plots to make complex data accessible and understandable.

<div align="center">
  <img src="[https://i.imgur.com/GzU1cHD.png](https://tse2.mm.bing.net/th/id/OIP.LqlibeY8zEcGUXbwSCBsQwHaCa?rs=1&pid=ImgDetMain&o=7&rm=3)" alt="Journey of Nykaa" width="800"/>
</div>

---

## 🎯 Project Objectives

The primary goals of this extensive analysis are:

* **Product Portfolio Analysis:** To evaluate the breadth and diversity of Nykaa's product range, identifying popular categories, pricing strategies, and top-performing items.
* **Brand Performance:** To identify the top-ranked and most influential beauty brands on the platform, understanding their market dominance.
* **Stock Market Insights:** To analyze Nykaa's historical stock performance since its IPO, identifying trends, volatility, and key financial health indicators.
* **Customer Sentiment Analysis:** To gauge public opinion by analyzing thousands of app reviews, categorizing them into positive, negative, and neutral sentiments to understand customer satisfaction and pain points.
* **Customized Recommendation Framework:** To lay the groundwork for a personalized recommendation system by understanding user behavior and product affinities.
* **Interactive Dashboarding:** To consolidate all findings into dynamic and interactive dashboards using Excel and Power BI for effective data-driven decision-making.

---

## 💻 Tech Stack

This project was brought to life using a combination of powerful data analysis and visualization tools:

| Category | Technology |
| :--- | :--- |
| **Programming Language** | `Python 3.12.3` |
| **Data Manipulation** | `Pandas`, `NumPy` |
| **Data Visualization** | `Matplotlib`, `Seaborn`, `Plotly`, `WordCloud` |
| **Natural Language Processing**| `TextBlob` |
| **Development Environment**| `Jupyter Notebook` |
| **Dashboarding** | `Microsoft Excel`, `Power BI` |
| **Data Sourcing** | `yfinance`, `Kaggle` |
| **Hardware** | `Intel Core i7-1355U`, `16 GB RAM`, `64-bit OS` |

---

## 🔬 The Analysis Workflow

The project is segmented into three core analytical modules:

### 📈 Stock Data Analysis

This module focuses on the financial performance of Nykaa's stock (NYKAA.NS) from its market debut on November 10, 2021, to November 24, 2023.

**Process:**
1.  **Data Retrieval:** Historical stock data was fetched using the `yfinance` library.
2.  **Trend Analysis:** Opening Price, Closing Price, and Trading Volume were visualized using Plotly to identify long-term trends.
3.  **Technical Indicators:** 50-day and 200-day moving averages were calculated and plotted to smooth out price data and identify significant market trends.
4.  **Interactive Visualization:** A user-interactive Candlestick chart was created to explore daily price action (Open, High, Low, Close).
5.  **Dashboard Creation:** The cleaned data was exported to create a comprehensive and stylish dashboard in Microsoft Excel.

**Key Visuals:**

* **Closing Price Trend with Moving Averages:**
    <img src="https://imgur.com/a/YOVXwqA" alt="Stock Closing Price" width="700"/>

* **Interactive Excel Dashboard:**
    <img src="https://imgur.com/a/iiubkuv" alt="Excel Dashboard" width="700"/>

### 💬 Sentiment Analysis of App Reviews

This section analyzes customer feedback from the Nykaa mobile app to understand public sentiment.

**Process:**
1.  **Data Collection:** A dataset of app reviews was sourced from Kaggle.
2.  **Sentiment Scoring:** The `TextBlob` library was used to perform sentiment polarity analysis on each review, categorizing it as 'Positive', 'Negative', or 'Neutral'.
3.  **Visualization:**
    * A count plot was generated to show the distribution of sentiment categories.
    * A `WordCloud` was created to highlight the most frequently used words in the reviews, offering a quick glance at the main topics of discussion.

**Key Visuals:**

* **Sentiment Distribution:**
    <img src="https://imgur.com/a/Wj5whjO" alt="Sentiment Count" width="500"/>

* **Review Word Cloud:**
    <img src="https://imgur.com/a/Mdh7j83" alt="Word Cloud" width="700"/>

### 🛍️ Product Portfolio Analysis (2022-2023)

This module dives deep into Nykaa's product listings from 2022 and 2023 to uncover insights about its inventory, pricing, and promotions.

**Process:**
1.  **Data Wrangling:** Datasets for 2022 and 2023 were loaded, cleaned, and pre-processed. This included handling missing values and converting data types.
2.  **Product Categorization:** A custom function was built to categorize products (e.g., 'Serum', 'Mask', 'Moisturizer') based on keywords in their titles.
3.  **Analysis of Key Metrics:**
    * **Pricing:** Identified the most and least expensive products.
    * **Reviews:** Found products with the highest and lowest number of reviews.
    * **Discounts & Gifts:** Analyzed the frequency and type of discounts and free gifts offered.
    * **Brands:** Determined the dominant brands on the platform.
4.  **Visualization:** Bar charts were used to visualize the frequency of product categories, discounts, and brand distribution.

**Key Visuals:**

* **Top Product Categories (2023):**
    <img src="https://imgur.com/a/jNMsBpt" alt="Top Categories" width="700"/>

* **Top 10 Discounts Offered:**
    <img src="https://imgur.com/a/swzegMd" alt="Top Discounts" width="700"/>

---

## ✨ Key Insights & ConclusionThis multi-faceted analysis yielded several critical insights:

* **Stock Performance:** Nykaa's stock has shown a consistent **downward trend** since its IPO, with the price frequently trading below its 50-day and 200-day moving averages, signaling market weakness. However, a slight recovery was noted in the final month of the analysis period.
* **Customer Sentiment:** The overall sentiment towards the Nykaa app is **overwhelmingly positive**. Words like "love," "good," "product," and "app" dominate the reviews, indicating high customer satisfaction with the platform's user experience and product selection.
* **Product Landscape:**
    * **Most Popular Categories:** **Serums** and **Moisturizers** are the most abundant product categories, reflecting high consumer demand.
    * **Dominant Brands:** **Nykaa Cosmetics** and **Nykaa Naturals** have the largest presence, showcasing the success of Nykaa's in-house brands.
    * **Pricing & Promotions:** The most common discount offered is **10% off**. High-value items, like Huda Beauty palettes, represent the upper end of the price spectrum, while affordable daily-use items like Biotique soaps form the lower end.
* **Market Strategy:** A significant number of products are tagged as **"NEW"**, indicating a strategy focused on continuous product portfolio expansion and keeping the inventory fresh and exciting for customers.

---

## 🚀 Future Scope

This project serves as a solid foundation for more advanced analysis. Future enhancements could include:

* **Predictive Stock Analysis:** Implementing time-series forecasting models (like ARIMA or LSTM) to predict future stock prices.
* **Advanced NLP:** Using topic modeling (e.g., LDA) on customer reviews to discover more granular insights about what customers like or dislike (e.g., "delivery," "packaging," "ingredient quality").
* **Recommendation Engine:** Building and deploying a collaborative or content-based filtering recommendation system to provide personalized product suggestions to users.
* **Competitor Analysis:** Scraping and analyzing data from competitor websites to benchmark Nykaa's performance in terms of pricing, product assortment, and promotions.
* **Automated BI Reporting:** Creating a fully automated Power BI dashboard that updates in real-time as new data becomes available.

---

## 🛠️ Getting Started

To explore this analysis on your local machine, follow these steps:

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/your-username/nykaa-data-analysis.git](https://github.com/your-username/nykaa-data-analysis.git)
    cd nykaa-data-analysis
    ```
2.  **Install dependencies:** It's recommended to create a virtual environment first.
    ```sh
    pip install -r requirements.txt
    ```
    *(A `requirements.txt` file would need to be created listing all libraries like pandas, yfinance, textblob, etc.)*
3.  **Launch Jupyter Notebook:**
    ```sh
    jupyter notebook
    ```
4.  **Run the notebooks:** Open and run the analysis notebooks to replicate the findings.

---

## ✍️ Author & Acknowledgments

* **Author:** Nikita Vipul Shah
* **Project Guide:** Mrs. Minal Dive
* **Institution:** SK Somaiya College, Somaiya Vidyavihar University
* **Data Sources:**
    * Product & Review Data: [Google Drive Link](https://drive.google.com/file/d/1bhQcYGYIxMjA-CfnL2y_ewjT4WYi4HyP/view?usp=sharing) , (https://drive.google.com/file/d/1r4wR98VQCyXLD_k89ah2AUTLC2K7t9KE/view?usp=sharing) , 
    * Stock Data: [Yahoo Finance](https://drive.google.com/file/d/16TzUZ8M8auMbYIV-oprwyfHywtCC8ZXJ/view?usp=sharing)
* **Inspiration:** This README was structured and styled to be a professional showcase of the original academic project.
