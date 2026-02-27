# Mexico Real Estate Market Analysis

<p float="left"> <img src="EarthQuake in Nepal1.png" width="30%" /> <img src="EarthQuake in Nepal2.png" width="30%" /> <img src="EarthQuake in Nepal3.png" width="30%" /> </p>


### Introduction
This project analyzes earthquake events in Nepal using seismic data. The goal is to explore whether earthquake magnitudes are influenced more by location or depth. The analysis includes data cleaning, feature extraction, and visualization techniques such as histograms, boxplots, scatter plots, and correlation analysis. Insights are drawn for regional differences, with a special focus on high-risk areas. And this is what I did: cleaned the data, created new features for latitude, longitude, and region, transformed magnitudes and depths to numeric values, explored the data through summary statistics and visualizations, and calculated correlations to understand the relationship between earthquake magnitude, depth, and location:

*Import libraries*

```python
import pandas as pd
import matplotlib.pyplot as plt
import plotly.express as px
```

## Conclusion
The analysis shows that earthquake magnitudes in Nepal are influenced by both depth and regional location. Some regions consistently experience stronger seismic activity, while correlations between depth and magnitude vary across locations. Through data cleaning, visualization, and correlation analysis, clear patterns emerged showing how seismic intensity and depth relationships differ by region. Overall, the project demonstrates how data analysis can uncover meaningful insights into earthquake patterns and support evidence-based risk assessment.
