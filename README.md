# Web-Design-Challenge 

![HTML_scaled.jpeg](hhttps://github.com/PeiDay/Web-Design-Challenge/blob/main/Resources/assets/HTML_scaled.jpeg)

## Web Visualization Dashboard

Data is more powerful when we share it with others! Let's take what we've learned about HTML and CSS to create a dashboard showing off the analysis we've done.

## Latitude - Latitude Analysis Dashboard with Attitude

We'll be creating a visualization dashboard website using visualizations we've created in a past assignment. Specifically, we'll be plotting [weather data](Resources/weatherpy_cities.csv).

In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page (`index.html`), a page where we can see a comparison of all of the plots, and another `data.html` page where we can view the data used to build them.

### Website 

The website must consist of 7 pages total, including:

* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.

* Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.

* A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.

* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table must be a bootstrap table component.
    * The data came from exporting the `weatherpy_cities.csv` file as HTML, or converting it to HTML with Pandas `to_html` that allows us to generate a HTML table from a pandas dataframe. 