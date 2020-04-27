# 0426-Tracking_Covid19_Sanny-YE

# Tracking Critical Covid-19 Data
## Background 
In this project, we will create an animated data visualization that demonstrates the number of cumulated COVID-19 confirmed cases in US counties, which can help us better understand how the virus is spreading within the United States and which county and state governments, businesses, and other organizations might need support during the pandemic.

### Business Question
How can we visualize and better understand the overall toll of the COVID-19 pandemic on US counties or county equivalents?

### Data Question 
Which data and metrics can we use to answer our question? 

## Data Analysis
By creating bubble charts of the percentage of the population over 60 years old on the x-axis, the percentage of the population under 18 on the y-axis, and the size of the scatter point corresponding to the number of hospital beds available in that county per 1000 people, we can get an idea of what counties might be most vulnerable to becoming overwhelmed by the COVID-19 pandemic.
![](Bed_counts_per_1000.png)

We also created a heatmap that shows the correlation between different factors in our dataset. Based on the heatmap, we can summarize our findings:
1) Hospital count and hospital bed count are closely related to the population of male and female over 60 years old and under 18 years old. 
2) Generally, most counties have around 20%-25% of its population under 18 and around 17%-25% of its population over 60 and those counties have the highest per-capita count for hospitals and hospital beds. 
3) The number of cases is hardly related to the population make-up of counties. As a result, the per capita statistic for cases is also hardly related to the population make-up of counties.
4) The number of deaths is also hardly related to the population make-up of counties and the same for deaths per 1000.
![](Heatmap.png)


## Conclusion
How might our data visualizations help county and state leadership or business owners in the US? What other data might we want to incorporate into an animated choropleth map to better understand the toll of the novel coronavirus in the United States?

## Additional Links
1) Data Source: https://github.com/jhu-business-analytics/covid-19-case-python-data-analysis
2) Tutorial: https://melanieshimano.gitbook.io/merging-data-and-plotly-visualizations/
