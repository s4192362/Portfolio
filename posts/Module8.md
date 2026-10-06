# <span style="color:purple">Module 8</span>
28/08/2026

## Map it

### Created Data Visualization
![Reference IMG](../IMG/vizModule8.png)
 

### Summary of the exercise
This exercise served to test data visualization building skills learnt in the previous module task by reverse-engineering a professional data visualization

* Parsed the raw text file, splitting each 4-digit PIN into coordinates
* Pin usage frequency was the value assigned to each coordinate in the 100x100 matrix
* Built the heatmap plot
* Applied logarithmic normalization to the custom heatmap color scale
* Added annotations and labels to the visualization 

---
## Data Card

| Title | Suicide rates across the world |
| ------------ | ------------- |
| Summary      | Estimated annual number of suicides per 100,000 people|
| Data Sources      | World Health Organization (2024) – with major processing by Our World in Data. “Age-standardized death rate from self-harm among both sexes” [dataset]. World Health Organization, “Global Health Estimates” [original data]. https://ourworldindata.org/suicide?insight=suicide-rates-vary-around-the-world#key-insights  |
| Mapping     | •	Spatial map: used natural earth available in plotly <br> • Colour encoding: Viridis(yellow to purple) deaths per 100k from 0 - 30|
| Important Notes      | •	Data was restricted to 2021 and data summary for regions (i.e Europe) was removed <br>•	Data is for both sexes and is age standardized |
| Access      | You can get a copy of the data used to build this visualisation by <br>•	Using the reference above|
