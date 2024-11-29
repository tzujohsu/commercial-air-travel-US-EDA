## Exploratory Data Analysis on 2023 US domestic Flight statistics

This report examines the primary factors behind flight delays and cancellations, as well as passenger, freight and mail traffic patterns in the US domestic flight sector for 2023. Through exploratory data analysis of US domestic flight data, the study identifies significant trends and provide insights for strategic decision-making. The year 2023 provides a more representative picture of air travel patterns, as it follows the major disruptions caused by the global pandemic.

### Data and Methodology
The study primarily utilizes the TranStats dataset from [the US Bureau of Transportation Statistics](https://data.bts.gov/), supplemented by Wikipedia's "List of Airline codes" for airline name matching. Data processing and analysis were conducted using Python, with pandas for data manipulation, matplotlib and seaborn for visualizations, and plotly.graph_objects for US map representations. Geolocation data (the latitude and longtitude information) was obtained via the geopy package, other geospatial related packages 'geopandas' and 'contextily' were also used. 

[![](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen)](https://www.python.org) [![](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org) [![](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%25dd32.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) [![](https://img.shields.io/badge/Contextily-D83B01?style=for-the-badge)](https://contextily.readthedocs.io/en/latest/) [![](https://img.shields.io/badge/geopandas-74aa9c?style=for-the-badge)](https://geopandas.org/en/stable/) [![](https://img.shields.io/badge/geopy-47A141?style=for-the-badge)](https://geopy.readthedocs.io/en/stable/)



