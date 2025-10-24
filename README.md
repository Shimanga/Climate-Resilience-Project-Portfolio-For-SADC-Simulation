## Climate Resilience Project: Southern Africa

**A Python analysis of climate patterns, vulnerability, and future risk in Southern Africa.**

---

**1. Project Overview**

This project examines climate data for ten countries in Southern Africa to understand how temperature, rainfall, and drought patterns are changing.
It evaluates the potential impact on the region and proposes data-based strategies for adaptation and mitigation.

**Goals**

- Track historical temperature and precipitation trends

- Identify regions with higher exposure and vulnerability

- Model possible future climate scenarios

- Suggest practical steps to strengthen climate resilience


*Note: The dataset used in this project was synthetically generated to simulate 30 years of climate patterns for demonstration purposes*

---

**2. Data Collection and Processing**

Code reference: generate_synthetic_climate_data()

Synthetic monthly climate data was generated for the period 1990 to 2020 for ten SADC countries.
Each record includes temperature, precipitation, and a drought index.

After cleaning and aggregation, the dataset contained 3,720 rows with annual averages per country.


---

**3. Exploratory Data Analysis**

Code reference: EDA and Trend Visualization

The analysis explored changes in temperature, rainfall, and drought frequency across the region.

**Main observations**

Temperatures increased steadily across all countries

Arid zones like Namibia and Botswana showed higher rainfall variability

Drought conditions occurred in more than 15% of recorded months


**Charts produced included:**

Annual temperature and precipitation trends

Warming rates per decade

Drought frequency per country

![Temperature Trends](https://github.com/Shimanga/Climate-Resilience-Project-Portfolio-For-Southern-Africa-/blob/main/Temperature%20trends.png)

---

**4. Climate Trend Analysis**

Code reference: calculate_climate_trends()

Linear regression was used to measure temperature, precipitation, and drought trends over time.

**Key results**

- **Average warming rate:** 0.26°C per decade

- **Highest rate: Eswatini** (0.35°C per decade)

- **Declining precipitation** in Namibia and Zambia

- Consistent **drought frequency** above 15 percent


A combined chart visualized each country’s warming rate and drought frequency to show relative risk.

![Percipitation Trends](https://github.com/Shimanga/Climate-Resilience-Project-Portfolio-For-Southern-Africa-/blob/main/Percipitation%20trends.png)

---

**5. Vulnerability Assessment**

Code reference: calculate_vulnerability_index()

A simple Climate Vulnerability Index was developed using three weighted components:

1. Exposure – warming and drought frequency


2. Sensitivity – rainfall dependence as a proxy for agricultural stress


3. Adaptive capacity – inverse of mean temperature



The index was scaled from 0 to 100.

Highest vulnerability

1. Namibia – 100


2. Mozambique – 99.8


3. Zimbabwe – 65



K-Means clustering grouped countries into high, moderate, and low vulnerability categories.


---

**6. Future Climate Projections**

Code reference: generate_future_scenarios()

Using the observed trends, projections were made for three simplified IPCC scenarios:

SSP2-4.5 (moderate)

SSP3-7.0 (high)

SSP5-8.5 (severe)


**Findings**

Expected regional temperature rise between 1.5°C and 3.0°C by 2050

Higher drought risk in Namibia and Botswana

Stronger impact scores for countries in the high vulnerability group



---

**7. Mitigation and Adaptation Strategies**

Code reference: recommend_strategies()

Each country received a set of recommendations based on its vulnerability level.

Level	Countries	Focus	Example Actions

High	Namibia, Mozambique	Immediate	Climate finance access, infrastructure upgrades, emergency response
Moderate	Zimbabwe, Zambia	Medium term	Irrigation, resilient crops, disaster planning
Low	South Africa, Angola	Strategic	Green tech, ecosystem restoration, regional knowledge sharing



---

**8. Implementation Roadmap and Monitoring**

Code reference: create_implementation_roadmap()

A phased plan was outlined to support policy and project execution.

**Short term (2024-2026)**
Policy development, pilot projects, training

**Medium term (2027-2030)**
Infrastructure investment, regional cooperation

**Long term (2031-2040)**
System transformation, sustainable financing

**Monitoring indicators**

90% population covered by early warning systems by 2030

50% farmland under climate-smart practices by 2035

60% renewable energy by 2040

25% drop in vulnerability index by 2035



---

**9. Summary of Results**

Code reference: summary()

Average warming: 0.26°C per decade
Most vulnerable: Namibia, Mozambique, Zimbabwe
Main risks: drought, heat stress, rainfall variability

**Policy focus**

Expand climate-smart agriculture

Improve water storage and management

Strengthen early warning and disaster response

Increase access to adaptation finance



---

**10. Tools and Methods**

Language: Python

Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn

Methods: Linear regression, K-Means clustering, index normalization

Outputs: Time-series charts, radar plots, cluster maps, strategy matrices



---

**11. Next Steps**

Replace synthetic data with satellite datasets (CHIRPS, ERA5)

Add socioeconomic indicators to improve sensitivity scoring

Test predictive models for drought and temperature projection



---

**12. About the Project Files**

File	Description

Climate risk project.ipynb	Main Jupyter Notebook containing all Python analysis, visualizations, and functions.
data/	Folder for climate datasets (synthetic or real data in future versions).
figures/	Contains saved plots and charts generated during analysis.
outputs/	Stores trend tables, vulnerability indices, and future projection summaries.
README.md	Overview of the entire project (this file).



---

Author

Shimanga Mubitana
Focused on linking data, climate, and development insights for Southern Africa.


