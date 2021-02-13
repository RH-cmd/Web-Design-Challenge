# Web Design Homework - Web Visualization Dashboard (Latitude)

## Background

Data is more powerful when we share it with others! Let's take what we've learned about HTML and CSS to create a dashboard showing off the analysis we've done.

## Latitude - Latitude Analysis Dashboard with Attitude

For this homework we'll be creating a visualization dashboard website using visualizations we've created in a past assignment. Specifically, we'll be plotting [weather data](Resources/cities.csv).

In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Requirements

The website will consist of 7 pages total, including:

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
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table must be a bootstrap table component. [Hint](https://getbootstrap.com/docs/4.3/content/tables/#responsive-tables)
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called `to_html` that allows you to generate a HTML table from a pandas dataframe. See the documentation [here](https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.to_html.html)


The website must, at the top of every page, have a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.

### Screenshots

This section contains screenshots of each page that must be built, at varying screen widths. These are a guide; you can meet the requirements without having the pages look exactly like the below images.

#### <a id="landing-page"></a>Landing page



![Landing Page](https://github.com/RH-cmd/Web-Design-Challenge/blob/main/Website%20Screenshots/landing_page.png?raw=true)


#### <a id="comparisons-page"></a>Comparisons page



![Comparsisons](https://github.com/RH-cmd/Web-Design-Challenge/blob/main/Website%20Screenshots/comparison.png?raw=true)



#### <a id="data-page"></a>Data page


![data page](https://github.com/RH-cmd/Web-Design-Challenge/blob/main/Website%20Screenshots/data_page.png?raw=true)



#### <a id="visualization-pages"></a>Visualization pages


![Max Temp](https://github.com/RH-cmd/Web-Design-Challenge/blob/main/Website%20Screenshots/max_temp.png?raw=true)


![Humidity](https://github.com/RH-cmd/Web-Design-Challenge/blob/main/Website%20Screenshots/humidity.png?raw=true)


![Cloudiness](https://github.com/RH-cmd/Web-Design-Challenge/blob/main/Website%20Screenshots/cloudiness_page.png?raw=true)


![Wind Speed](https://github.com/RH-cmd/Web-Design-Challenge/blob/main/Website%20Screenshots/wind_speed.png?raw=true)



#### <a id="navigation-menu"></a>Navigation menu


![nav bar large](https://github.com/RH-cmd/Web-Design-Challenge/blob/main/Website%20Screenshots/nav_bar_large.png?raw=true)

![nav bar small](https://github.com/RH-cmd/Web-Design-Challenge/blob/main/Website%20Screenshots/nav_bar_small.png?raw=true)







