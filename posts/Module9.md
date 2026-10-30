# <span style="color:purple">Module 9</span>
"30/10/2026"

## Make it interactive

### Created Data Visualization

<iframe src="https://01a18b2f-1a85-e85c-2525-b4c9afe4a084.share.connect.posit.cloud/" width="100%" height="600px"></iframe>


### Summary of the exercise
This exercise served to explore adding interactivity to data visualizations

* Added interactivity to the suicide choropleth map in the form of a slider for the years of the data and a hover for individual country stats


## Data Card

| Title | Suicide rates across the world |
| ------------ | ------------- |
| Summary | Estimated annual number of suicides per 100,000 people |
| Data Sources | World Health Organization (2024) – with major processing by Our World in Data. “Age-standardized death rate from self-harm among both sexes” [dataset]. World Health Organization, “Global Health Estimates” [original data]. [Our World in Data Source](https://ourworldindata.org/suicide?insight=suicide-rates-vary-around-the-world#key-insights) |
| Mapping | - Spatial map: used natural earth available in plotly which provides a less distorted view of the globe than typical maps <br> - Colour encoding: Viridis(yellow to purple) deaths per 100k from 0 - 30. This clamping prevents extreme global outliers from compressing the contrast |
| Important Notes | - Data summary for regions (i.e Europe) was removed <br> - Data is for both sexes and is age standardized which allows for better comparisons across regions. As it accounts for differences in population age breakdown between countries |
| Access | You can get a copy of the data used to build this visualisation by using the reference above |
