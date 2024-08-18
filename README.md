**Project Summary**
This project focuses on enhancing data visualizations in R by customizing plots with the ggplot2 package and creating interactive maps with the leaflet package.

**1. Customizing Plots with ggplot2:**

**Labels and Titles**: Used the labs() function to add or customize axis labels, plot titles, subtitles, and captions. Alternatively, xlab(), ylab(), and ggtitle() can be used for simpler label updates.

**Example**: Improved the clarity of a scatter plot from the mtcars dataset by adding descriptive labels to the x-axis, y-axis, and plot title.

**2. Creating Maps with leaflet:**

**Adding Rectangles**: Highlighted areas of interest on maps using the addRectangles() function, specifying the coordinates of the rectangle's corners.

**Adding Circles and Legends**: Visualized data points with circles colored based on a numeric variable. Added a color legend to represent the magnitude of each circle.

**Key Functions and Techniques**:

**ggplot2 Functions**: labs(), xlab(), ylab(), ggtitle()

**leaflet Functions**: addRectangles(), addCircles(), addLegend()

**Color Palettes**: colorNumeric() to define color schemes for visualizing numerical data.

**Example Application:**
Created a map to visualize earthquake magnitudes from the quakes dataset, using colored circles to represent different magnitudes and a legend to explain the color coding.

This project demonstrates the application of advanced plotting techniques and interactive map features to enhance data visualization and interpretation.
