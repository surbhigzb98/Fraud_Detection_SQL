# 🔐 SQL Case Study: Fraud Detection and Customer Transaction Analysis

This repository explores credit card transaction data to identify fraud patterns, customer behavior, geographic trends, and business insights. The project simulates a real-world fraud detection environment and was built using advanced SQL queries on a transactional database schema.

---

### 🧾 Business Case

> The dataset represents millions of credit card transactions from diverse geolocations, including fields like transaction amount, merchant category, latitude/longitude, customer demographics, and fraud indicators.  
> The analysis aims to uncover trends in fraudulent activities, geographic concentration, customer segmentation, and revenue behaviors using only SQL—ideal for enterprise-scale systems with structured databases.

---

### 📌 Key Objectives

#### 🕵️ Fraud Analytics
- Detect merchant categories with highest fraud percentages
- Identify fraud-heavy zip codes and merchant locations
- Compare average amount of fraudulent vs. non-fraudulent transactions
- Understand if merchant proximity influences fraud likelihood

#### 👤 Customer Demographics
- Analyze how gender and job roles influence spending
- Correlate age (from DOB) with category preferences
- Discover which occupations have highest average spend

#### 🗺️ Geographic & Merchant Insights
- Map out fraud density across city, state, and coordinates
- Link city populations to spending volume
- Investigate location-category patterns (e.g., certain cities spending more on electronics)

#### ⏰ Time-Based Trends
- Detect peak hours/days/months of transactional activity
- Compare temporal patterns between fraud and legitimate transactions
- Discover seasonal spikes via Unix time conversions

#### 💵 Revenue & Job-Based Spending
- Rank job titles by overall spend
- Analyze state/city revenue contributions
- Identify category-wise revenue leaders

#### 🧠 Customer Segmentation
- Profile top customers by total spend, frequency, and max transaction
- Estimate lifetime value based on behavior patterns
- Segment customers by gender, job, and age for marketing potential

#### ⚠️ Risk Assessment
- Explore fraud-prone combinations of job, location, and merchant category
- Extract features that characterize high-risk transactions (e.g., amount, geolocation)

---

### ⚙️ Technologies & Techniques

| Tool          | Role                           |
|---------------|--------------------------------|
| **SQL Server**| Query execution & database analysis |
| **T-SQL**     | Advanced analytics using window functions, subqueries, grouping |
| **Excel** *(optional)* | Data export & visualization assistance |

---

### 📂 Repo Structure

- 📄 `Fraud Detection and Analysis` — Contains all query blocks categorized by topic
- 📑 `README.md` — Project overview and insight summary
- 📁 `Documentation/` — Supporting resources and case files


---

### 🌟 Highlights

- Fully SQL-powered—no Python or BI tools involved
- Covers fraud analytics, customer segmentation, and revenue trends
- Applies business logic to database fields using joins, filters, aggregations, and date/time functions
- Excellent primer for Data Analyst or Risk Analyst technical interviews

---

### 🙋‍♀️ About Me

Hi, I’m **Surbhi**—currently working as a Data Analyst at TechnoData Analytics.  
I specialize in building real-time dashboards, cleaning messy datasets, and mastering technical tools like SQL, Power BI, Excel, and Python.

📬 [LinkedIn](www.linkedin.com/in/surbhi-995926161)  
🌐 [GitHub Portfolio](https://github.com/surbhigzb98)

---

### ✨ How to Use

1. Clone the repository  
2. Open the SQL query file using SSMS or any compatible RDBMS  
3. Execute queries on a structured version of the dataset  
4. Review comments for explanations and business reasoning

---

> ⭐ Star this repository or share feedback if you'd like to learn more or contribute!  
> This is part of my journey toward building impactful, query-driven data solutions ✨🔍
