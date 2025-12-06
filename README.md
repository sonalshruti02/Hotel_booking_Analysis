# 🏨 Hotel Booking Analysis

## 📌 Project Overview
This project analyzes hotel booking data to understand booking patterns, cancellations, customer types, and revenue behavior.

All analysis is done in Jupyter Notebook using Python, based on the raw hotel booking data.

---

## 📂 Project Structure

- `data/hotel_raw.csv` – Original raw dataset used for analysis.
- `notebook/hotel_analysis.ipynb` – Complete analysis with data cleaning, EDA, and insights.
- `report/hotel_analysis_report.pdf` – Final summarized report created from the notebook insights.
- `requirements/requirements.txt`-To know which texh stack has been used .
  
---

## 🧮 Analysis Performed

- Data cleaning (handling nulls, duplicates, outliers)
- KPI calculations like:
  - Total bookings
  - Cancellation rate
  - Average daily rate (ADR)
  - Booking trends over time
  - Market segment and customer type analysis
- Visualizations for:
  - Booking trend by month
  - Cancellation behavior
  - ADR distribution
  - Customer segmentation

---

## ⚙️ Tech Stack

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repo
2. Install dependencies from `requirements.txt`
3. Open `notebook/hotel_analysis.ipynb` in Jupyter and run all cells.

---

## 📊 KPIs Analyzed

- Total Bookings
- Cancelled vs Confirmed Bookings
- Cancellation Rate (%)
- Average Daily Rate (ADR)
- Monthly Booking Trends
- Booking Distribution by Hotel Type
- Market Segment Contribution
- Country-wise Cancellation

---

## 🧮 KPI Formulas

Cancellation Rate (%)
= (Total Cancelled Bookings / Total Bookings) × 100

Average Daily Rate (ADR)
= Total Room Revenue / Total Rooms Sold

---

## 📊 KPI Summary (Final Results)

| KPI | Value |
|-----|-------|
| Total Cancellation Rate | **~37%** |
| Confirmed Bookings | **~63%** |
| Highest Booking Hotel Type | **City Hotel** |
| Hotel Type with Higher ADR | **Resort Hotel** |
| Highest Booking Month | **August** |
| Month with Highest Cancellations | **January** |
| Country with Max Cancellations | **Portugal** |
| Top Booking Channel | **Online Travel Agents (46%)** |
| Group Bookings Share | **27%** |
| Direct Bookings | **4%** |

---

## 🔍 Key Insights

- Around **37% of all hotel bookings were cancelled**, creating major revenue leakage.
- **City Hotels** receive more bookings than Resort Hotels, likely due to business and urban travel.
- **Higher prices lead directly to higher cancellation rates** — most cancellations occur in high ADR ranges.
- **January had the highest number of cancellations**, indicating post-holiday demand drop.
- **August recorded the highest confirmed bookings**, showing peak season demand.
- **Portugal recorded the highest number of booking cancellations**, suggesting pricing/service challenges.
- Majority of customers (**46%**) book through Online Travel Agencies, which typically have higher cancellation risks.
- Only **4% of customers book directly**, showing weak hotel-to-customer relationship management.


---

## ✅ Business Recommendations

- Introduce **dynamic pricing** for high ADR periods to reduce cancellations.
- Provide **discount offers during January** to stabilize bookings.
- Reduce resort hotel rates on **weekends and holidays** to match demand sensitivity.
- Improve hotel service and customer experience particularly in **Portugal**.
- Increase **direct bookings** by:
  - Website discounts
  - Member rewards
  - Email loyalty campaigns
- Reduce OTA dependency as they control nearly **half of all bookings**.

---

## 📂 Dataset

Hotel Booking Demand Dataset (Kaggle)

---

## 💼 Business Impact

This analysis enables hotels to:
- Reduce revenue loss due to cancellations
- Improve occupancy rates
- Optimize pricing strategy
- Increase direct booking conversions
- Identify high-risk locations and months

---

## 📌 Analyst Summary

This hotel analysis demonstrates how pricing strategy, seasonality, and booking channels influence customer cancellation behavior and hotel revenue.

The findings provide clear evidence that managing ADR and reducing OTA dependency are critical levers for increasing occupancy and profitability.

---

## 👩‍💻 Author

**Sonal Shruti**  
B.Tech | Data Analyst Aspirant | GDSC Core Member
