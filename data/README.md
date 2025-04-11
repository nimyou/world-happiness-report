---
output:
  pdf_document: default
  html_document: default
---

# World Happiness Report Dataset

This dataset is derived from the [World Happiness Report](https://worldhappiness.report/),
an annual publication that ranks countries based on their citizens' self-reported happiness levels. 
The report is a collaboration among the Wellbeing Research Centre at the University of Oxford, Gallup, and 
the UN Sustainable Development Solutions Network.

## Dataset Overview

The dataset provides insights into factors influencing happiness across various countries. 
It includes data from multiple years, with each entry representing a country's performance in a given year.

## Data Structure

CSV file contains the following columns:

| Variable | Description |
|----------|-------------|
| `Year` | The year for which the happiness data was recorded. |
| `Rank` | The country's ranking in the happiness index for the given year (1 = happiest country). |
| `Country` | Name of the country in the dataset. |
| `Ladder Score` | The overall happiness score between 0-10. |
| `Upper Whisker` | The upper bound of the confidence interval for the happiness score. |
| `Lower Whisker` | The lower bound of the confidence interval for the happiness score. |
| `Explained by Log GDP per Capita` | The contribution of GDP per capita (log-transformed) to the happiness score. |
| `Explained by Social Support` | The contribution of social support to happiness, measuring the availability of friends or family for support. |
| `Explained by Healthy Life Expectancy` | The contribution of healthy life expectancy to happiness, representing expected years of good health. |
| `Explained by Freedom to Make Life Choices` | The contribution of personal freedom to happiness. |
| `Explained by Generosity` | The contribution of generosity to happiness, reflecting charitable donations and social kindness. |
| `Explained by Perceptions of Corruption` | The contribution of corruption perception to happiness. Higher values indicate less perceived corruption. |
| `Dystopia Residual` | A theoretical lowest happiness score (dystopia) used as a baseline, representing the unexplained portion of the happiness score. |

These variables are used to analyze and explain differences in happiness levels across countries.


## Citation
Helliwell, J. F., Layard, R., Sachs, J., & De Neve, J. (Eds.). (2024). *World Happiness Report*. 
University of Oxford’s Wellbeing Research Centre, Gallup, UN Sustainable Development Solutions Network.
Available at [World Happiness Report](https://worldhappiness.report/).
