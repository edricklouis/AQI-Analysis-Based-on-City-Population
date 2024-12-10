# Air Quality Analysis Based on City Population

This research project aims to explore the relationship between air quality and city population size by analyzing air pollution data from cities worldwide. Air quality is measured using the Air Quality Index (AQI), which indicates the level of pollution in the air and its potential health effects. The study categorizes cities into five groups based on population size: small, medium, large, very large, and giant cities, providing insights into how population density may influence air pollution levels.
<br><br>
<b>View in Tableau Dashboard version :</b>

## Dataset
2024 Population by Cities Dataset : https://www.kaggle.com/datasets/ibrarhussain123/world-largest-cities-by-population-2024
<br>
Global Air Pollution Dataset : https://www.kaggle.com/datasets/hasibalmuzdadid/global-air-pollution-dataset?select=global+air+pollution+dataset.csv

## Features 
- country_name<br>
- city_name<br>
- aqi_value<br>
- population_2024<br>
- population_category (Small, Medium, Large, Very Large, Giant)

## Research Results
<div style="display: flex; justify-content: center;">
  <img src="/AQI Analysis Results/Treemaps.png" style="width:100%; height:auto;">
</div>
The treemap illustrates cities worldwide based on their population sizes, with larger rectangles representing more population. The color gradient within each rectangle reflects the air quality index (AQI), 
where redder tones indicate poorer air quality and bluer tones represent better air quality. This visualization effectively highlights the relationship between population density and air quality, showing 
that many densely populated cities, such as Delhi and Chengdu, tend to have worse air quality. In contrast, smaller or less densely populated cities generally exhibit better air conditions.
<br><br>

<div style="display: flex; justify-content: space-between; align-items: center;">
  <img src="/AQI Analysis Results/categoryPercentage.png" style="width:36%; height:auto;">
  <img src="/AQI Analysis Results/avgAQIEachCategory.png" style="width:60%; height:auto;">
</div>
The analysis of air quality across population categories reveals that "Giant" cities exhibit the highest average AQI, indicating significantly poor air quality, while "Medium" cities have the lowest average 
AQI, suggesting better air quality in comparison. The distribution of city categories shows that "Medium" cities dominate with 64.83%, followed by "Small" cities at 25.21%, while "Giant" and "Very Large" 
cities represent only 1.06% and 3.18% respectively. This proves that the smaller the population, the better the air quality tends to be. This is proven by the fact that even though the medium population 
category dominates all categories, the average air quality is the lowest.

## Conclusions
- Cities in the "Giant" population category have the highest average AQI (202.80), indicating the worst air quality, while "Medium" cities have the lowest average AQI (107.11), reflecting better air conditions
- Most cities fall under the "Medium" (64.83%) and "Small" (25.21%) categories, while "Giant" cities make up only 1.06% of the data, and "Very Large" cities account for 3.18%
- Larger population sizes are strongly associated with higher pollution levels, highlighting the significant impact of urbanization on air quality
- Effective pollution management strategies are crucial for cities with larger populations, especially those in the "Giant" and "Very Large" categories, to minimize health risks
