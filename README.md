# Netflix-User-Analytics
End-to-end Power BI dashboard analyzing Netflix user behavior, engagement, and churn risk using synthetic data.
# 🎬 Netflix User Analytics Dashboard (Power BI)

## 📌 Project Overview
This project presents an **interactive Power BI dashboard** built using **25,000 synthetic Netflix user records**.  
The dashboard analyzes **user demographics, subscription behavior, content preferences, engagement levels, and churn risk**.

The objective is to demonstrate **end-to-end data analytics skills** including data cleaning, DAX calculations, and professional dashboard design.

---

## 📊 Dashboard Preview

![WhatsApp Image 2026-02-02 at 1 55 03 AM](https://github.com/user-attachments/assets/fcfbe915-a846-4de5-97b8-9f5b6a8ce030)


> *Dark-themed Netflix-style dashboard with KPIs, subscription analysis, genre popularity, geographic distribution, and churn risk insights.*

---

## 📁 Dataset Description
- **Total Records:** 25,000 users  
- **Data Type:** Synthetic (fictional, safe for public use)

### Key Columns:
- `User_ID` – Unique identifier  
- `Age` – User age (13–80)  
- `Country` – User country  
- `Subscription_Type` – Basic, Standard, Premium  
- `Watch_Time_Hours` – Hours watched in last month  
- `Favorite_Genre` – Preferred content genre  
- `Last_Login` – Last login date  

---

## 🧠 Key Insights Delivered
- 📈 **Subscription Analysis:** Premium and Basic plans dominate the user base  
- 🎭 **Genre Popularity:** Horror, Action, and Documentary lead user preferences  
- 🌍 **Geographic Distribution:** Users spread across multiple regions  
- ⏱ **Engagement Trends:** Older age groups show higher watch time  
- 🚨 **Churn Risk Identification:** Users flagged using low watch time and long inactivity  

---

## ⚙️ Tools & Technologies
- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Power Query**
- **Data Visualization & Analytics**
- **GitHub**

---

## 📐 Key DAX Logic Used

### Days Since Last Login
```DAX
Days Since Last Login =
DATE(2025,3,8) - 'Users'[Last_Login]
