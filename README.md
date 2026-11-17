# PhonePe Pulse Data Visualization and Exploration

## Project Presentation Video

Watch my project presentation here:

[Click here to watch the project presentation](https://drive.google.com/file/d/1sinrnYxUO_kSk3U-Sd7x9BRZkIDpX5kF/view?usp=sharing)

PhonePe Pulse Data Visualization and Exploration

An interactive Power BI dashboard that explores PhonePe Pulse payment data across Indian states and districts, from 2018 Q1 to 2022 Q4.

**Domain:** Fintech | **Tool:** Power BI Desktop | **Language:** DAX

## What the dashboard shows
What the dashboard shows

- A geo map of transaction amount by state
- KPI cards for total transactions, total amount, average transaction value and registered users
- Top 10 charts for states and districts by transaction amount, transaction count and registered users
- Quarterly trend, year-over-year growth and compound annual growth rate (CAGR)
- Breakdowns by transaction type and device brand

## Pages
Pages

1. **Overview:** KPI cards, state map and a metric chart
2. **Top Performers:** top states and districts
3. **Trends & Growth:** trend line, YoY growth, CAGR, transaction types and device brands

## Ten dropdown filters
 Ten dropdown filters

Year, Quarter, Period (YearQuarter), State, District, Metric, Trend Metric, Transaction type, Device brand and Top N.

## Key findings
Key findings

- Transaction amount grew at a CAGR of 150.8% from 2018 to 2022.
- Year-over-year growth: 286.7% (2019), 133.3% (2020), 136.3% (2021) and 85.7% (2022).
- Totals: 72 billion transactions, 121.41 trillion in value, about 1.69K average per transaction and 434 million registered users.
- Telangana, Maharashtra and Karnataka lead the states; Bengaluru Urban leads the districts.
- Merchant payments are the largest transaction type, and Xiaomi, Samsung and Vivo are the top device brands.

## Data
Data

The data comes from the [PhonePe Pulse repository](https://github.com/PhonePe/pulse). The six preprocessed CSV files (aggregated and map tables for transactions and users, plus the top tables) were provided with the project brief and are not included in this repository.

## How the model works
How the model works

The six tables are kept separate and linked through three lookup tables (DimState, DimTime and DimDistrict) using one-to-many relationships. Key measures: Total Transactions, Total Amount, Avg Transaction Value, Registered Users, Amount YoY % and Amount CAGR.
Files <img width="955" height="530" alt="Phonepe Puse Overview page" src="https://github.com/user-attachments/assets/0d53f47e-e4ea-4bad-a816-a094ce4b2699" />
<img width="954" height="531" alt="Phonepe Pulse Trends and Growth" src="https://github.com/user-attachments/assets/8ea30e5e-5ed6-41c3-9759-fe6f516226cd" />
<img width="940" height="531" alt="Phonepe Pulse  Top Perfromance page" src="https://github.com/user-attachments/assets/d107bb42-7be3-4944-a4bf-716d75792a3c" />

## Files


## Power BI Project Report

**Project:** PhonePe Pulse Dashboard

**Author:** Balogun Abdulateef Ayinla

View or download the complete project report in PDF format below.

[View PhonePe Pulse Dashboard Project Report (PDF)](PhonePe%20Pulse%20Dashboard%20Project%20Report%20By%20Balogun%20Abdulateef%20Ayinla.pdf)



## Limitations
 Limitations

- 2018 has no year-over-year figure because there is no 2017 data.
- Registered users are a running total, so the measure uses the latest quarter in the selection.
- The dataset has no app-opens column, so engagement is measured with registered users.

## Author
Balogun Abdulateef Ayinla
