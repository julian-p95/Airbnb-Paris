# Airbnb-Paris

This is a sample code to analyze and visualize Airbnb data in Paris, France. The code uses the libraries pandas, pylab and geopandas to import, manipulate and visualize the data.

The data is first read from a .csv file into a pandas dataframe and some new columns are created to calculate the duration of stay and the benefits for each listing. The data is then filtered to only include listings with positive durations and grouped by neighborhood to calculate the average benefit for each neighborhood.

A choropleth map is created using plotly's px.choropleth function and the average benefits of each neighborhood is displayed using a color scale. A heatmap is also created using px.density_mapbox to show the density of listings in each location.

The code demonstrates the power of data analysis and visualization in understanding patterns and trends in the data. By visualizing the data, we can gain a better understanding of the benefits of Airbnb listings in Paris and identify areas with higher demand.
