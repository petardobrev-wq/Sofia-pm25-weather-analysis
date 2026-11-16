# Sofia PM2.5 and Weather Analysis

## Overview

This project investigates the relationship between daily PM2.5 concentrations and weather conditions in Sofia, Bulgaria.

I apply descriptive statistics, Pearson correlation, and conditional probability to explore associations between air pollution and temperature, relative humidity, wind speed, and atmospheric pressure.

The analysis addresses two research questions:

1. How is daily PM2.5 associated with individual meteorological variables?
2. How do PM2.5 concentrations and the frequency of high-pollution days differ across combinations of temperature and wind speed?

## Data

The dataset combines air-quality observations from [OpenAQ](https://openaq.org/) with historical weather data from [Open-Meteo](https://open-meteo.com/).

The combined dataset contains 595 daily records from 2 January 2025 to 4 November 2026. The main mathematical analysis uses 419 observations from 12 September 2025 to 4 November 2026.

The data collection and preparation procedures are documented in the appendix.

## Repository Contents

- `sofia_pm25_analysis.ipynb` — Mathematical analysis, visualizations, and conclusions.
- `Appendix_A_Data_Collection.ipynb` — Data collection and preparation.
- `all_sofia_air_quality_weather_daily.csv` — Combined dataset used in the analysis.

## How to Run

1. Download the repository.
2. Install Python and Jupyter Notebook or JupyterLab.
3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn requests notebook
   ```

4. Open `sofia_pm25_analysis.ipynb` in Jupyter and run the cells in order.

Keep the CSV file in the same folder as the main notebook. The main analysis does not require an API key. Re-running the data collection appendix requires an OpenAQ API key.

## Limitations

The study uses observations from one monitoring location and is observational rather than causal. Seasonal patterns and unmeasured factors may influence the results.

## AI Assistance Disclosure

AI-assisted tools were used to support selected writing tasks, code review, debugging, and the exploration and development of ideas initially proposed by the author. The author reviewed the analytical methods, verified the calculations and results, and takes responsibility for the final interpretations and project content.


