# Air Quality Data Analysis in Maharashtra (2015)

## Project Overview

This project analyzes air quality data from Maharashtra for the year 2015, focusing on three key pollutants: SO2, NO2, and RSPM/PM10. The analysis aims to assess pollutant levels, identify trends, and provide insights into potential pollution hotspots and implications for public health.

## Data Source

The dataset used in this analysis is sourced from the Central Pollution Control Board (CPCB) and contains daily air quality measurements for various locations in Maharashtra.
![image](https://github.com/user-attachments/assets/d5234988-a677-45c8-abc1-b3e3a32cfdc5)


## Key Features

### 1. Data Preparation
- **Handling Null Values:** Columns with excessive null values (like PM 2.5) were removed, and rows with null values in critical columns (SO2, NO2, RSPM/PM10) were dropped to ensure data integrity.
  
### 2. Descriptive Analysis
![image](https://github.com/user-attachments/assets/61d5b0a1-7bea-453f-a353-da9232dc574f)

- **Statistical Summary:**
  - **SO2:** Mean = 16.09 µg/m³, Median = 13 µg/m³ (majority of observations below 20 µg/m³)
  - **NO2:** Mean = 34.80 µg/m³, Median = 32 µg/m³ (majority of observations below 46 µg/m³)
  - **RSPM/PM10:** Mean = 101.24 µg/m³, Median = 97 µg/m³ (majority of observations below 128 µg/m³)
  
- **Insights:**
  - The mean concentrations indicate moderate pollution levels.
  - Medians slightly lower than the means suggest most data points are in lower concentration ranges.
  - Occasional high spikes indicate pollution episodes, possibly from localized sources.

- Further analysis, including temporal and spatial trends exploration, as well as comparison with air quality standards and guidelines,
  is necessary to assess the overall air quality status and potential implications for public health and environmental management.

### 3. Temporal Analysis

### Yearly:
![image](https://github.com/user-attachments/assets/59e5f5ce-1d30-452f-aee1-9b0c5cc0088f)
### Weekday
![image](https://github.com/user-attachments/assets/b49e2f05-805b-41e6-b296-3fd4784cbedf)

- **Trends Over Time:**
  - Seasonal spikes in pollutants were observed, with significant increases in late February 2015.
  - Possible causes: international events (e.g., wars) and local activities (e.g., festivals), suggesting factors like fireworks contributed to short-term pollution spikes.

### 4. Spatial Analysis (Potential)
![image](https://github.com/user-attachments/assets/a441dcc0-7bb0-4608-a32a-78591522254e)
![image](https://github.com/user-attachments/assets/b50505ec-6b08-4273-8470-b9515e96ac58)

- **Insights on Metropolitan Areas:**
  - Metropolitan areas show significantly higher pollutant concentrations, likely due to urban activities and traffic.
  - Limitations: Lack of detailed geographic coordinates in the dataset.

### 5. Correlation Analysis
- **Relationships Between Pollutants:**
  - Positive correlations were observed between SO2, NO2, and PM10, suggesting shared pollution sources, likely industrial or vehicular emissions.

### 6. Agency Contributions
![image](https://github.com/user-attachments/assets/b2fefc16-5482-4e7d-84b3-e764163e0c91)

- The data highlights contributions from various agencies, especially the Maharashtra State Pollution Control Board, which plays a key role in environmental monitoring.

### 7. Recommendations
- **Air Quality Management:**
  - Increase monitoring efforts and implement targeted interventions to reduce key pollutants.
  - Public awareness campaigns about pollution sources and impacts.
  - Strengthen collaboration among local and national agencies.
  - Support green infrastructure, such as more green spaces and sustainable transportation.
  - Invest in research and innovations for pollution control technologies.
