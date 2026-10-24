# 🚀 Enquiry Management System (EMS) Analysis

Welcome to the **EMS Dashboard** repository! This project is built using **Power BI** to monitor and analyze customer enquiries, test rides, follow-ups, and retail performance at a dealer and business level.

## 📂 Project Overview

The EMS dashboard helps visualize and interpret large-scale enquiry and retail data to identify performance trends, conversion efficiencies, and regional gaps.

- 🎯 **Objective**: To track, monitor, and improve customer enquiry conversion efficiency across all dealer points.
- 📅 **Data Period**: April to March (FY 2023-25)
- 📊 **Tool Used**: Power BI Desktop

---

## 📃 Dashboard Pages Description

### 🔹 **Page 1: EMS – Business Performance Overview**

Provides a macro-level performance summary of enquiries and retails by month.

- **Filters**: Financial Year, Month, Zone, State, Town, Dealer Code
- **KPIs**:
  - LY/TY Enquiry & Retail
  - Enquiry & Retail GOLY%
  - Conversion Ratios (LY vs TY)
  - Gain/Loss (%) vs Last Year
- **Visuals**:
  - YOY Comparison (Donut Chart)
  - Spartan vs Non-Project Dealer Trends (Line Chart)
  - Gain/Loss by Dealer Type (Bar Chart)

✅ **Key Formulas**:
- `Enquiry GOLY% = (TY Enquiry - LY Enquiry) / LY Enquiry * 100`
- `Retail GOLY% = (TY Retail - LY Retail) / LY Retail * 100`
- `Gain/Loss = TY Conversion% - LY Conversion%`

---

### 🔹 **Page 2: EMS – Dealer-Wise Customer Journey**

Breaks down customer journey insights at dealer level.

- **Filters**: FY, Month, Zone, State, Dealer, Town
- **Metrics**:
  - Total Enquiry, Test Ride Offered/Taken
  - Follow-Up Effectiveness (Same Day, >=3, >=5)
  - Enquiry Status (Open, Progress, Postponed)
  - Final Status (Converted, Lost, Booked, Retailed)

📌 **Highlights**:
- Quick snapshot of total enquiry conversion process
- Follow-up patterns help identify dealer gaps
- Retail data aggregated and mapped with enquiry flow

---

### 🔹 **Page 3: Dashboard Summary**

A professionally written visual summary page explaining:

- Page-wise objective
- KPI calculation logic
- Key insights from visuals
- User guide for filters and interpretations

---

## 🧮 Dataset Structure

Primary data table: `EMS`

| Column Name | Description |
|-------------|-------------|
| Zone, State, Town, Dealer_Code | Dealer Geography |
| Project, Month, Year, Date     | Time Period |
| Walkins_Enquiry, Test_Ride_Offered, Test_Ride_Taken | Initial Interaction |
| Followed_Up, Same_Day_Followed_Up, Followed_Up_>=3, >=5 | Follow-Up Details |
| Open_Enquiry, Enquiry_in_Progress, Enquiry_Postponed | Mid-Funnel Tracking |
| New_Enquiry, Enquiry_Closed_Lost, Enquiry_Converted | Final Funnel Status |
| Booked, Retailed, Same_Day_Retailed, Retails_for_the_Month | Booking & Retail Metrics |

---

## 📸 Dashboard Screenshots

<img width="1300" height="842" alt="Screenshot 2026-10-25 031434" src="https://github.com/user-attachments/assets/c3d96769-2ec6-4f6f-9d40-6b0afedd2f61" />

<img width="1297" height="846" alt="Screenshot 2026-10-25 031456" src="https://github.com/user-attachments/assets/1f83b471-84c7-4445-ac4a-05d24c2eb928" />

<img width="1301" height="847" alt="Screenshot 2026-10-25 031522" src="https://github.com/user-attachments/assets/b51a5948-a649-4d67-9828-b957fcd0e068" />

---

## 🛠️ How to Use

1. Clone or download the repository
2. Open `.pbix` file in Power BI Desktop (file not included here)
3. Use the filters at top to select desired time frame, zone, or dealer
4. Use the summary page for navigation and explanation

---

## 👨‍💼 Created By

- **Name**: Aman Kumar  Shrivastav

