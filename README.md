# Campylobacteriosis Prevalence in California

**Campylobacteriosis** prevalence across California from 2001 to 2014 via. a pre-processed CDC dataset. The document can be found under "CDC Diabetes Health Indicators" from UC Irvine's Machine Learning Repository site. It was pre-processed (manipulated, filtered, augmented) from Burrows et. al. 2017 data for public use. The purpose of this project was twofold - 

1) to explore visual trends in Campylobacteriosis by grouping counties on population size 
2) to examine the limitations of this pre-processed data for epidemiological analyses and conclusions 

![Campylobacteriosis Prevalence and Confidence Intervals](Campy_Rates_Sub.png)

Fig. 1. Campylobacteriosis Prevalence in California by County (2001 - 2014)
---

## Project Overview

Campylobacteriosis is a enteric infection of public health interest (e.g. food-borne illness prevention). This project focuses on:

- Visualizing Prevalence rates and confidence intervals across grouped California counties.
- Highlighting trends and disparities in Campylobacter Prevalence over time with heatmaps.
- Exploring the impact of population size and county characteristics on disease rates.

---

## Features (Preprocessing and Analysis)

- **Grouped County Analysis**: Counties with no missing data are grouped based on population and visualized in 3x3 subplots for comparison.
- **Confidence Interval Visualization**: Confidence intervals provide insights into the reliability of the reported rates.
- **Summary Statistics**: Descriptive tables summarizing population ranges, Prevalence rates, and confidence intervals for each county group.

---

## Data Source

The dataset originates from California public health records, providing:
- **Disease**: Campylobacteriosis
- **Geography**: California counties
- **Metrics**: Prevalence rates, confidence intervals, and population sizes 
- **Timeframe**: 2001–2014

---

## Key Visualizations

1. **Grouped Subplots**: A 3x3 grid showing Campylobacter Prevalence rates for each county group.
2. **Confidence Intervals**: Highlighting variability and trends in disease reporting.
3. **Descriptive Statistics Table**: Overview of population and rate ranges for each group.

