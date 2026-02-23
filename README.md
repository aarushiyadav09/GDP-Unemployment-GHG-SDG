# 📊 GDP, Unemployment and Greenhouse Gas Emissions from the Frame of SDGs

> A data-driven forecasting study analyzing India's macroeconomic and environmental indicators through the lens of the United Nations Sustainable Development Goals (SDG 8 & SDG 13).

---

## Project Info

| Field | Details |
|---|---|
| **Degree** | Master of Science in Operations Research |
| **University** | Aligarh Muslim University, Aligarh (202002), U.P., India |
| **Department** | Statistics and Operations Research |
| **Supervisors** | Dr. Irfan Ali & Dr. Ahmad Yusuf Adhami |
| **Authors** | Aarushi Yadav (24ORMSA103), Umme Habiba (24ORMSA115), Ishika Garg (24ORMSA116) |

---

## 📌 Overview

This project investigates India's progress toward two critical Sustainable Development Goals:

- **SDG 8** — Decent Work and Economic Growth (via GDP & Unemployment analysis)
- **SDG 13** — Climate Action (via Greenhouse Gas Emission analysis)

Using historical state-wise data, the study applies statistical and time-series forecasting techniques to project key indicators up to **2030**, providing data-driven insights for policymakers.

---

## 🎯 Objectives

1. Analyze historical trends in India's GDP, unemployment rates, and GHG emissions
2. Perform state-wise Exploratory Data Analysis (EDA) across all Indian states and UTs
3. Identify regional disparities and structural patterns
4. Forecast 2030 values using ARIMA and Exponential Smoothing models
5. Align findings with SDG 8 and SDG 13 targets and policy implications

---

## 🗂️ Datasets

| Dataset | Period | States/UTs | Source |
|---|---|---|---|
| State-wise GDP | 2011–12 to 2021–22 | 34 | MoSPI, Govt. of India |
| Unemployment Rate | 2018–19 to 2022–23 | 30 | PLFS (Periodic Labour Force Survey) |
| GHG Emissions | 2015–2023 | 21 | MoEFCC, India |

---

## 🔬 Methodology

### Exploratory Data Analysis (EDA)
- Descriptive statistics and distribution analysis
- State-wise comparison bar charts and line graphs
- Correlation heatmaps (year-over-year)
- Box plots for convergence and disparity analysis
- Top-15 fastest growing states and regional insights

### Forecasting Models
| Indicator | Model Used | Forecast Horizon |
|---|---|---|
| GDP | ARIMA | 2022 → 2030 |
| Unemployment Rate | Exponential Smoothing + ARIMA(1,1,1) | 2023 → 2030 |
| GHG Emissions | ARIMA | 2023 → 2030 |

---

## 📈 Key Findings

### GDP
- **Maharashtra** leads with the highest GDP (27.1 lakh crore)
- High GDP states projected to grow from ~12–13 lakh crore to **20+ lakh crore by 2030**
- **Mizoram** shows the highest long-term growth rate (16.9%) among all states
- Significant regional disparity — Western & Southern states dominate output

### Unemployment
- National average unemployment declined from **6.0% (2018–19) to 4.3% (2022–23)**
- **Nagaland, J&K, and Haryana** projected to have highest unemployment by 2030
- **Assam, Gujarat, and Goa** projected to achieve near-zero unemployment by 2030
- Year-over-year correlation (r > 0.98) confirms deep structural inertia in regional patterns

### GHG Emissions
- National emissions rose from **194 MtCO₂e (2015) to 240 MtCO₂e (2023)** — a 23.4% increase
- Top 5 states (Gujarat, Andhra Pradesh, Uttar Pradesh, Maharashtra, Tamil Nadu) account for ~50% of emissions
- **Tamil Nadu** projected to grow emissions to **20.2 MtCO₂e by 2030** (+17.2%)
- Most top emitter states show structural persistence — high emitters remain high

---

## 🌍 SDG Alignment

| SDG | Indicator | Finding |
|---|---|---|
| SDG 8 (Decent Work) | GDP & Unemployment | Growth is strong but jobless; informality persists at ~80% |
| SDG 13 (Climate Action) | GHG Emissions | Emissions growing 23.4%; top states need urgent decarbonization |

---

## 🛠️ Tech Stack

| Library | Purpose |
|---|---|
| Python 3.x | Core programming language |
| pandas | Data manipulation and analysis |
| numpy | Numerical computing |
| matplotlib | Static visualizations |
| seaborn | Statistical visualizations |
| scikit-learn | ML utilities and metrics |
| statsmodels | ARIMA and time-series modelling |

---



## Sample Visualizations

| Chart | Description |
|---|---|
| All States GDP Comparison | Bar chart comparing latest GDP across 34 states |
| GDP Growth Trends (2012–2021) | Line graph for all states over the decade |
| GDP Forecast to 2030 | ARIMA projections by GDP tier (High/Medium/Low) |
| Unemployment Box Plot | Distribution and convergence across fiscal years |
| GHG Emissions Trend | National total emissions 2015–2023 |
| ARIMA GHG Forecast | Top-5 state emissions forecast to 2030 |

---

## References

- Ministry of Statistics and Programme Implementation. *Periodic Labour Force Survey 2022–23*. Govt. of India.
- NITI Aayog. *SDG India Index 2023–24*. Govt. of India.
- Ministry of Environment, Forest and Climate Change. *India's Climate Action Report 2022*.
- World Bank. *World Development Indicators 2023*.
- International Labour Organization. *World Employment and Social Outlook 2022*.
- United Nations. *Transforming Our World: The 2030 Agenda for Sustainable Development*. UN, 2015.
- IPCC. *Climate Change 2021: The Physical Science Basis*. Cambridge University Press.

---

## License

This project is submitted for academic purposes under Aligarh Muslim University. All rights reserved by the authors.

---

## Acknowledgements

We sincerely thank **Dr. Irfan Ali** and **Dr. Ahmad Yusuf Adhami** for their invaluable guidance and supervision throughout this project. We also acknowledge the Department of Statistics and Operations Research, AMU, for providing the academic framework and resources.

---

<p align="center">
  <b>Department of Statistics and Operations Research</b><br>
  Aligarh Muslim University, Aligarh — 202002, U.P., India
</p>
