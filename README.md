# Campylobacteriosis Prevalence in California

**Campylobacteriosis** prevalence across California from 2001 to 2014. The data can be found on the "California Open Data Portal" website. This dataset was pre-processed (i.e. manipulated, filtered, augmented) from an unknown secondary source on Kaggle. The purpose of this project was twofold - 

1) to explore visual trends in Campylobacteriosis across Californian counties by population size, over time 
2) to examine the limitations of this pre-processed data for epidemiological analyses and conclusions 

![Campylobacteriosis Prevalence and Confidence Intervals](Campy_Rates_Sub.png)

Fig. 1. Campylobacteriosis Prevalence in California by County (2001 - 2014)
---

## Project Overview - Visualization for a Superficial Trend Analysis 

Campylobacteriosis is a enteric infection of public health interest (e.g. for food-borne illness prevention). This project centered on creating concise Python code for heatmatps of the rates and corresponding confidence intervals. These heatmaps may reveal superficial trends and disparities across county groups. This code can be replicated for another exploratory data analyses of this kind. 

---

## Steps (exlporatory Preprocessing and Analysis)

- **Grouped County Analysis**: Counties with no missing data were grouped based on population and visualized in 3x3 subplots for comparison.
- **Prevalence and Confidence Code**: Heat maps of prevalence rates were created by testing various python code in an exploratory analysis. Note, confidence intervals provide insights into the reliability of the reported rates!
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

## Conclusions 

This code has use for creating heatmaps and completing an exploratory data analysis of preprocessed epidemiological data (e.g. a Kaggle dataset). The file highlights limitations of solely using "rates, confidence intervals, year, and population size" for epidemiological analysis. For a statistical comparison we need the following... county population values for standardization (denominators) and case counts (numerators) for recalculating confidence intervals. Without a standard population, we can't adjust for age or remove confounding by demographic structure! As is, we are missing information to make a sound interpretation. Still, these heatmaps will prove valuable for the exploratory data analysis in your epidemiology projects. Happy programming! 
 
Lash, Timothy L., et al., editors. Modern Epidemiology. 4th ed., Wolters Kluwer / Lippincott Williams & Wilkins, 2021.

