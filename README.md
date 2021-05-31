# Web Design Homework - Web Visualization Dashboard (Latitude)

## Summary:

* Web Visualization Dashboard of weather in 500+ cities at different latitudes relative to the equator line. The visualizations show temperature, humidity, cloudiness, and wind speed using HTML5, CSS3, and Bootstrap4.

## Files:
* .html files for deployment.
*  .ipynb file for responsive table using pandas.
*  'assets/images' folder includes the graphics used from previous assignment.

## Instructions:

### Latitude - Latitude Analysis Dashboard with Attitude

* Create a visualization dashboard website using visualizations we've created in a past assignment.
* Create individual pages for each plot and a means by which we can navigate between them.

### Website Requirements
The website must consist of 7 pages total, including:
* A landing page containing:
  * An explanation of the project.
  * Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
* Four visualizations, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A comparison page that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A data page that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table must be a bootstrap table component.
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML. Try using a tool you already know, pandas. 
    
The website must, at the top of every page, have a navigation menu that:
* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive.

Finally, the website must be deployed to GitHub pages: https://jrosedavis.github.io/Web-Design-Challenge/

