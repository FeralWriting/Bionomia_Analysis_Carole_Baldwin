# Bionomia_Analysis_Carole_Baldwin

## Overview

Visual representations of the specimens collected or identified over the career of Carole Baldwin, a zoologist who works for the smithsonian. Created during an internship with the [Smithsonian Institution's Data Science Lab](https://sidatasciencelab.github.io/). This project uses data from the [Bionomia](https://bionomia.net/) database. The project contains a [bar graph](###-Bar-Graph) of specimens collected each year, a [pie chart](###-Pie-Chart) of the different countries visited to collect specimens, and an interactive [leaflet](#leaflet) of collected specimens. The bar graph and pie chart sections have an example of what each graph looks like; to view the leaflet, download and run [this](/Leaflet/CBLeaflet.html) HTML file. This project incorporated R and gave me experience with R, RStudio, graphs, charts, data analysis, and problem solving.

## Features

### Bar Graph

The bar graph depicts how many specimens Baldwin either solely collected or both collected and identified each year during her career. The former is presented in blue and the latter in orange, as shown in the legend. The x axis contains the year and the y axis is the frequency.

![image](https://github.com/FeralWriting/Bionomia_Analysis_Carole_Baldwin/assets/69817846/bca65289-bcd7-4faa-97ff-9474b54b9b26)

### Pie Chart

The pie chart shows the proportions of how frequently each country was visited to collect specimens. The slices are in ascending order starting at the positive x axis and increasing counterclockwise, with an "Other" slice at the end. They are also color coded according to the rainbow in the same order. Countries with a frequency below a certain threshold are collated into the "Other" slice.

![image](https://github.com/FeralWriting/Bionomia_Analysis_Carole_Baldwin/assets/69817846/0a3822df-f917-44f8-9c17-9733b83a9cbd)

### Leaflet

The leaflet is a map of where exactly each specimen was collected, using longitudinal and latitudinal coordinates to place each marker. It can be dragged, clicked, and zoomed in or out. The map displays more detail the more it is zoomed in, showing countries, states, cities, lakes, and rivers. Each marker shows the exact coordinates when clicked. Due to the amount of detail, the leaflet may be slow to run on certain machines.
