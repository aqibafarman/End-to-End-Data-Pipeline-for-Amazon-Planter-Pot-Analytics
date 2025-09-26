# End-to-End Automated Data Pipeline for Amazon Planter Pot Analytics

## 📌 Project Overview

This project simulates a real-world **e-commerce retail analytics** scenario. I built a complete **end-to-end automated data pipeline** to analyze the planter pot market on Amazon.

The goal was to answer key business questions for sellers and store owners:

* ✅ What is the **competitive price range** for planter pots?
* ✅ Which **product types** are most popular?
* ✅ Which products received the **highest ratings**?

By combining **web scraping, automation, data cleaning, database management, and visualization**, this project demonstrates both **technical expertise** and **business problem-solving**.

---

## 🛠️ Tech Stack

* **Web Scraping** → BeautifulSoup, Selenium
* **Data Cleaning & Processing** → Python (Pandas, NumPy)
* **Database Management** → MySQL
* **Automation** → Windows Task Scheduler (scheduled ETL pipeline)
* **Visualization & Reporting** → Power BI

---

## 🔄 Automated Workflow / Pipeline

1. **Data Extraction**

   * Scraped Amazon planter pot product listings using **BeautifulSoup & Selenium**.
   * Collected product name, type, price, rating, and reviews.

2. **Data Cleaning & Processing**

   * Used Python (Pandas) for:

     * Removing duplicates
     * Handling missing values
     * Standardizing categories (e.g., indoor/outdoor, material type)
     * Creating price ranges

3. **Database Creation**

   * Stored cleaned dataset into **MySQL database**.
   * Designed schema to handle product attributes efficiently.

4. **Automation**

   * Automated the pipeline using **Windows Task Scheduler**.
   * The entire process (**scraping → cleaning → database update**) runs **after 15 days without manual intervention**.

5. **Data Visualization & Insights**

   * Connected MySQL to **Power BI**.
   * Built interactive dashboards to uncover insights:

     * **Distribution of planter pot types**
     * **Price vs. rating patterns**
     * **Top highest-rated products**

---

## 📊 Key Insights

* **Most Common Types** → Plastic & ceramic indoor/outdoor pots dominated listings.
* **Price Range** → Majority of products were priced between **₹21–40**, making it the competitive sweet spot.
* **Customer Preference** → Highest-rated products were **ceramic and plastic pots**, especially those suited for both indoor and outdoor use.

---

## 📁 Project Structure

```
├── data/                 # Raw & cleaned datasets  
├── notebooks/            # Python scripts & Jupyter notebooks  
├── sql/                  # Database creation & queries  
├── powerbi/              # Power BI dashboard files  
├── automation/           # Task Scheduler XML / batch files  
├── images/               # Screenshots of dashboards  
└── README.md             # Project documentation
```

---

## 🚀 Future Improvements

* Deploy pipeline on **cloud orchestrators** (Airflow / Prefect)
* Expand analysis to include **competitor categories**
* Add **sentiment analysis** from product reviews
* Deploy Power BI dashboard online (Power BI Service)

---

## 📌 Dashboard Preview

![Dashboard Screenshot](images/dashboard.png)

---

## 👩‍💻 Author

**Aqiba Farman**

* Data Analyst | Excel | SQL | Power BI | Python | Automation
* [LinkedIn](#) | [Portfolio](#)
