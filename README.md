# KTMB Mobility Analysis

## 📝 Project Overview
Explore how ridership on KTMB train services in Malaysia has changed in response to fuel prices and the MCO (Movement Control Order) phases implemented during the COVID-19 pandemic.

## 📊 Dataset Summary
This analysis uses publicly available data from [data.gov.my](https://data.gov.my):
- **KTMB Monthly Ridership** (by service type: Komuter, ETS, etc.)
- **Monthly Petrol and Diesel Prices**
- **MCO Timeline and Types** (from Wikipedia)

### ⚠️ Caveats and Limitations

- The starting dates vary between different KTMB services due to the phased rollout of KITS (from which this data is sourced).
- Ensure this is accounted for when comparing ridership across services over time.


Each dataset has minimal cleaning, allowing for direct time series visualization and comparison.

## 🔍 Objectives
- Analyze how ridership trends changed during different MCO phases
- Compare ridership trends with fluctuations in fuel prices
- Identify which KTMB services were most affected

## 📂 Project Structure
- `data/` — CSV files for ridership, fuel prices, and MCO timeline
- `ktmb_mobility_analysis.ipynb` — main analysis notebook
