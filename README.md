# COVID-19 Policy Effectiveness in Malaysia: A Mobility-Based Analysis

## 🧭 Overview

This project examines the effectiveness of Malaysia’s COVID-19 response by evaluating how movement control strategies (MCOs) influenced infection trends. Using KTMB ridership as a proxy for public mobility and daily COVID-19 case counts as an outcome measure, the analysis investigates whether restrictions on population movement helped reduce virus transmission.

## 🎯 Objectives

- Assess the impact of MCO phases on active COVID-19 cases  
- Use KTMB ridership trends to evaluate behavioural responses to policy interventions  
- Determine whether reductions in public mobility correlated with reductions in case numbers  
- Observe how these relationships changed during the transition to endemic management  

## 📊 Datasets

All data was sourced from [data.gov.my](https://data.gov.my) and public repositories:  

- `covid_cases.csv`: Daily COVID-19 case data by state  
- `ktmb_ridership.csv`: Monthly ridership statistics by service type (Komuter, ETS, etc.)  
- `mco_timeline.csv`: Annotated timeline of MCO, FMCO, and NRP phases  

## 🛠️ Methodology

- Cleaned and corrected active case counts by handling anomalies and invalid values 
- Filtered data for West Malaysian states only  
- Visualised trends with time-series plots, dual-axis comparisons, and annotated policy timelines  
- Interpreted patterns around case surges and mobility drops during major policy phases  

## 🔍 Key Findings

- KTMB ridership consistently dropped during major MCO phases, especially during FMCO and the Delta wave  
- These declines were followed by reductions in active COVID-19 cases, suggesting MCOs were effective in suppressing transmission through mobility control  
- The Omicron wave showed high case numbers despite stable ridership, reflecting Malaysia’s shift to endemic management and public adaptation  
- By 2023, ridership stabilised and decoupled from case trends, indicating long-term behavioural change  

## ⚠️ Limitations

- Case data reflects report dates, not symptom onset  
- KTMB ridership is a proxy for mobility; actual movement patterns may vary  
- Economic and social context (e.g. informal work, policy fatigue) was not quantitatively assessed  
- Vaccination and hospitalisation data were not included but would improve future analysis  

## 🗂️ Repository Structure

- `COVID_Cases_Analysis.ipynb`   # Main notebook with full analysis  
- `data/`                        # CSV files for COVID-19 cases, ridership, and MCO timeline  
- `plots/`                       # Optional folder for exporting key charts as PNGs  
- `README.md`                    # Project overview and summary  

## 🔭 Future Work

- Add time-lagged correlation to model delays between ridership drops and case declines  
- Integrate vaccination rates, hospital data, and Google Mobility Reports  
- Extend the analysis to other transport modes or include sentiment data to assess compliance  

