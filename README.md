# Minard-Map

### MODULES AND PACKAGES USED IN THIS PROJECT

**GeoPandas:**
An extension of Pandas designed for working with geospatial data. It simplifies operations like spatial joins and plotting by integrating with geographic data formats like shapefiles and GeoJSON.

**Bokeh:**
A Python library for creating interactive visualizations for web applications. It supports high-performance plots, dashboards, and complex layouts with rich interactivity.

**ColumnDataSource (from Bokeh):**
A Bokeh-specific data structure that bridges Python data (like Pandas DataFrames) with visual elements in Bokeh plots. It allows efficient updates and interaction with plot components.

**LabelSet (from Bokeh):**
A Bokeh model that adds text annotations to plots. It can position labels dynamically based on data in the ColumnDataSource.

**HoverTool (from Bokeh):**
A tool in Bokeh that enhances interactivity by displaying additional information when hovering over plot elements. It uses customizable tooltips to show data from the ColumnDataSource.

**Viridis (from Bokeh):**
A perceptually uniform color palette provided by Bokeh, useful for data visualizations. It is ideal for representing continuous data.

**Category20 (from Bokeh):**
A Bokeh color palette with 20 distinct colors. It is commonly used for categorical data visualizations to ensure color clarity and differentiation.

### NECESSARY FILES TO BE LOAD

**Dataset (minard_fixed.csv):**
This CSV file contains structured data related to Napoleon's Russian Campaign, including details like city names, geographic coordinates, temperature, dates, and survivor counts. It serves as the primary data source for visualizing the advance and retreat paths of Napoleon's army.

**GeoJSON file (rivers.geojson):**
A geospatial file format designed for encoding geographic features like rivers, lakes, and boundaries. It provides detailed geographic coordinates for visualizing and overlaying rivers on interactive maps.
