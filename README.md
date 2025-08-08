# Campylobacteriosis Prevalence in California

**Campylobacteriosis** prevalence across California from 2001 to 2014. The data can be found in "CDC Diabetes Health Indicators" from UC Irvine's Machine Learning Repository site. It was pre-processed (i.e. manipulated, filtered, augmented) from Burrows et. al. 2017 for public use. The purpose of this project was twofold - 

1) to explore visual trends in Campylobacteriosis by grouping counties on population size 
2) to examine the limitations of this pre-processed data for epidemiological analyses and conclusions 

![Campylobacteriosis Prevalence and Confidence Intervals](Campy_Rates_Sub.png)

Fig. 1. Campylobacteriosis Prevalence in California by County (2001 - 2014)
---

## Project Overview - Visualization for a Superficial Trend Analysis 

Campylobacteriosis is a enteric infection of public health interest (e.g. for food-borne illness prevention). This project centered on creating concise Python code to create heatmatps of prevalence rates and confidence intervals. These heatmaps may reveal superficial trends and disparities across county groups.

---

## Steps (Preprocessing and Analysis)

- **Grouped County Analysis**: Counties with no missing data are grouped based on population and visualized in 3x3 subplots for comparison.
- **Confidence Interval Visualization**: Confidence intervals provide insights into the reliability of the reported rates.
- **Summary Statistics**: Descriptive tables summarizing population ranges, Prevalence rates, and confidence intervals for each county group.

---

## Data Source

The dataset originates from a preprocessed file :
- **Disease**: Campylobacteriosis
- **Geography**: California counties
- **Metrics**: Prevalence rates, confidence intervals, and population sizes 
- **Timeframe**: 2001–2014

---

## Key Visualizations

1. **Grouped Subplots**: A 3x3 grid showing Campylobacter Prevalence rates for each county group.
2. **Confidence Intervals**: Highlighting variability and trends in disease reporting.
3. **Descriptive Statistics Table**: Overview of population and rate ranges for each group.

