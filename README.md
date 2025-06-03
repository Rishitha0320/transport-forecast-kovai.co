# 🚌 Public Transport Passenger Forecasting – Kovai.co Internship Task

## 📁 Dataset
This project uses the **Daily Public Transport Passenger Journeys by Service Types** dataset from the ACT Government Open Data Portal:  
🔗 [Dataset Link](https://www.data.act.gov.au/Transport/Daily-Public-Transport-Passenger-Journeys-by-Servi/nkxy-abdj)

---

## 📌 Task Overview

> **Objective:**  
Analyze passenger journeys across multiple public transport types and forecast the number of users for the **next 7 days** using Facebook Prophet.

### Services Forecasted:
- Local Route  
- Light Rail  
- Peak Service  
- Rapid Route  
- School Services

---

## 📊 Key Deliverables

- ✅ Data cleaning & preprocessing  
- ✅ Insights report with 3 observations  
- ✅ Forecasting using Facebook Prophet  
- ✅ Plots for next 7 days  
- ✅ 1-page technical documentation  
- ✅ Clean Jupyter Notebook (`.ipynb`)  
- ✅ Word report file (`.docx`)  

---

## 🔮 Forecasting Model

> **Algorithm Used:** Facebook Prophet  
Prophet is robust for time series forecasting and automatically handles:
- Trends
- Weekly seasonality
- Missing values
- Holiday effects (if any)

Each transport service was modeled and forecasted **individually**.

---

## 📁 Project Structure

```bash
├── forecast_model.ipynb       # Main Jupyter Notebook
├── insights_and_report.docx   # Word report with insights & explanation
├── README.md                  # This file
