# Web-Design-Challenge 

![HTML_scaled.jpeg](https://github.com/PeiDay/Web-Design-Challenge/blob/main/Resources/assets/HTML_scaled.jpeg)

## Web Visualization Dashboard

Weather Dashboard webpage: https://peiday.github.io/Web-Design-Challenge/index.html

## Latitude - Latitude Analysis Dashboard with Attitude

We'll be creating a visualization dashboard website using visualizations we've created in **Python-API-Challenge/WeatherPy**.  Specifically, we'll be plotting [weather data](Resources/weatherpy_cities.csv).

In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page (`index.html`), a page where we can see a comparison of all of the plots, and another `data.html` page where we can view the data used to build them.

### Weather Dashboard

The website must consist of 7 pages total, including:

* A **[landing page](#Visualizations/pages/landing_lg)** containing:
  * An explanation of the project.
  * Links to each visualizations page with a sidebar containing preview images of each plot, and clicking an image would take you to that visualization.
![landing_lg.jpg](https://github.com/PeiDay/Web-Design-Challenge/blob/main/Visualizations/pages/landing_lg.jpg)

* Four **[visualization pages](#Visualizations/pages)**, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison with a paragraph describing the plot and its significance.
![temp_lg.jpg](https://github.com/PeiDay/Web-Design-Challenge/blob/main/Visualizations/pages/temp_lg.jpg)
![humid_lg.jpg](https://github.com/PeiDay/Web-Design-Challenge/blob/main/Visualizations/pages/humid_lg.jpg)
![cloud_lg.jpg](https://github.com/PeiDay/Web-Design-Challenge/blob/main/Visualizations/pages/cloud_lg.jpg)
![wind_lg.jpg](https://github.com/PeiDay/Web-Design-Challenge/blob/main/Visualizations/pages/wind_lg.jpg)

* A **["Comparisons" page](#Visualizations/pages/comparison_lg)** that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
![comparison_lg.jpg](https://github.com/PeiDay/Web-Design-Challenge/blob/main/Visualizations/pages/comparison_lg.jpg)

* A **["Data" page](#Visualizations/pages/data_lg)** that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table is a bootstrap table component.
    * The data came from exporting the `weatherpy_cities.csv` file as HTML, or converting it to HTML with Pandas `to_html` that allows us to generate a HTML table from a pandas dataframe. 
![data_lg.jpg](https://github.com/PeiDay/Web-Design-Challenge/blob/main/Visualizations/pages/data_lg.jpg)

#### Weather Dashboard works at all window widths/sizes

#### Tools used: HTML, CSS, Pandas, JupyterNotbook