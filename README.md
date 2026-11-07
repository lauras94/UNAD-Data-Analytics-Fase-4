# UNAD Data Analytics – Phase 4
## Household Appliance Energy Prediction

### Work Team

Laura Camila Artunduaga.
Santiago Vasquez Sarauz.
Lewis Rafael Susa Peñate.

### 1. Project Overview

This project focuses on the analysis of household appliance energy consumption using data analytics techniques and environmental measurements collected in an Internet of Things (IoT) environment.

The main purpose is to identify consumption patterns, explore relationships between environmental variables and energy usage, and understand temporal variations in household energy consumption.

### 2. Dataset Description

The project uses the Appliances Energy Prediction dataset from the UCI Machine Learning Repository.

- **Number of observations:** 19,735
- **Original variables:** 29
- **Time period:** January 11, 2016 – May 27, 2016
- **Target variable:** Appliances
- **Temporal variable:** date

The dataset includes household appliance energy consumption, lighting consumption, indoor and outdoor temperature, humidity, atmospheric pressure, wind speed, visibility, and other environmental measurements.

Dataset source: https://doi.org/10.24432/C5VC8G

### 3. Methodology

The analysis was developed using Python in Google Colab and included the following stages:

1. Initial dataset loading and inspection.
2. Data cleaning and preprocessing.
3. Dataset structure and data type verification.
4. Descriptive statistical analysis.
5. Energy consumption distribution analysis.
6. Correlation analysis between energy consumption and environmental variables.
7. Temporal analysis of energy consumption.
8. Comparison between weekdays and weekends.
9. Mann-Whitney U statistical test.

### 4. Main Findings

The exploratory analysis identified the following results:

- Average appliance energy consumption: 97.69 Wh.
- Median energy consumption: 60 Wh.
- Standard deviation: 102.52 Wh.
- Minimum consumption: 10 Wh.
- Maximum consumption: 1,080 Wh.
- Highest positive correlation: lights (0.1973).
- Strongest negative correlation: RH_out (-0.1523).

The comparison between weekdays and weekends showed an average consumption of 96.59 Wh and 100.58 Wh, respectively.

The Mann-Whitney U test produced a p-value of 0.148675, indicating insufficient statistical evidence of a significant difference between both groups at the 5% significance level.

### 5. Tools and Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

### 6. Repository Contents

- `Appliances_Energy_Prediction.ipynb`: Python notebook containing the data analysis, statistical procedures, and visualizations.
- `README.md`: Project documentation.

### 7. References

Candanedo, L. M., Feldheim, V., & Deramaix, D. (2017). Data driven prediction models of energy use of appliances in a low-energy house. *Energy and Buildings, 140*, 81–97. https://doi.org/10.1016/j.enbuild.2017.01.083

Candanedo, L. (2017). *Appliances Energy Prediction* [Data set]. UCI Machine Learning Repository. https://doi.org/10.24432/C5VC8G

### 8. Academic Context

Universidad Nacional Abierta y a Distancia (UNAD).

Course: Data Analytics.

Activity: Phase 4 – Solution Implementation and Descriptive Analysis.
