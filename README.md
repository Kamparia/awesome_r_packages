# Awesome R packages for Data Science

This is a list of most popular R packages for various task that could be done in Data Science

<img width="1093" alt="screen shot 2016-07-02 at 2 12 14 pm" src="https://raw.githubusercontent.com/Kamparia/awesome_r_packages/master/img/data%20science%20with%20r.jpg">

### Data Manipulation
1. [dplyr](https://cran.rstudio.com/web/packages/dplyr/vignettes/introduction.html) - This package has everything (almost) to accelerate your data manipulation efforts. It is known best for data exploration and transformation. It’s chaining syntax makes it highly adaptive to use. It includes 5 major data manipulation commands : Filter, Select, Arrange, Mutate, Summarise.
2. [reshape2](http://seananderson.ca/2013/10/19/reshape.html) - We all know the data come in many forms. As the name suggests, this package is useful in reshaping data. Usually, the process of reshaping data in R is tedious and worrisome. The reshape package overcome these problems.
3. [tidyr](https://blog.rstudio.org/2014/07/22/introducing-tidyr) - This package can make your data look ‘tidy’. It has 4 major functions to accomplish this task (gather, spread, seperate, unite).  
4. [data.table](https://www.r-bloggers.com/intro-to-the-data-table-package/) - The data.table R package provides an enhanced version of data.frame that allows you to do blazing fast data manipulations. R data.table gives the user an intuitive way to organize, view, and access data.
5. [lubridate](https://cran.r-project.org/web/packages/lubridate/vignettes/lubridate.html) - Lubridate is an R package that makes it easier to work with dates and times. The 'lubridate' package has a consistent and memorable syntax that makes working with dates easy and fun.
6. [stringr](https://cran.r-project.org/web/packages/stringr/vignettes/stringr.html) - Stringr provides an opinionated interface to strings in R. It makes string processing simpler by removing uncommon options, and by vigorously enforcing consistency across functions.
7. [validate](https://cran.r-project.org/web/packages/stringr/vignettes/stringr.html) - The validate package makes it super-easy to check data against domain knowledge. It works by allowing you to define data validation rules independent of the code or data set.

### Data Visualization
8. [ggplot2](http://ggplot2.org/) - Powerful, flexible and well-thought-out dataviz package following 'grammar of graphics' syntax to create static graphics, but be prepared for a steep learning curve.
9. [plotly](https://plot.ly/r/) - Plotly's R graphing library makes interactive, publication-quality graphs online. Examples of how to make line plots, scatter plots, area charts, bar charts, error bars, box plots, histograms, heatmaps, subplots, multiple-axes, polar charts and bubble charts.
10. [googleviz](https://cran.r-project.org/web/packages/googleVis/index.html) - GoogleVis provides an interface between R and the Google Charts Tools, allowing you to create interactive web charts from R without uploading your data to Google.
11. [ggviz](http://ggvis.rstudio.com/) - ggvis is a data visualization package for R which lets you declaratively describe data graphics with a syntax similar in spirit to ggplot2 and create rich interactive graphics that you can play with locally in Rstudio or in your browser.
12. [shiny](https://shiny.rstudio.com/) - Shiny is an R package that provides an elegant and powerful web framework for building web applications using R. Shiny helps turn your analyses into interactive web applications without requiring HTML, CSS, or JavaScript knowledge.
13. [RColorBrewer](http://moderndata.plot.ly/create-colorful-graphs-in-r-with-rcolorbrewer-and-plotly/) - RColorBrewer is an R package that allows users to create colourful graphs with pre-made color palettes that visualize data in a clear and distinguishable manner. There are 3 categories of palettes: qualitative, diverging, and sequential.
14. [rgl](http://rgl.neoscientists.org/about.shtml) - The rgl package is a visualization device system for R, using OpenGL as the rendering backend. An rgl device at its core is a real-time 3D engine written in C++. It provides an interactive viewpoint navigation facility (mouse + wheel support) and an R programming interface.

### Working with web data
1. [jsonlite](https://cran.r-project.org/web/packages/jsonlite/vignettes/json-aaquickstart.html) - A fast JSON parser and generator optimized for statistical data and the web. This is ideal for interacting with web APIs, or to build pipelines where data structures seamlessly flow in and out of R using JSON.
2. [httr](https://cran.r-project.org/web/packages/jsonlite/vignettes/json-aaquickstart.html) - A set of useful tools for working with HTTP connections (GET, PATCH, POST, HEAD, PUT, and DELETE). Configuration functions make it easy to control additional request components (authenticate(), add_headers() and so on).
3. [curl](https://github.com/jeroenooms/curl) - Modern and Flexible Web Client for R. The curl() and curl_download() functions provide highly configurable drop-in replacements for base url() and download.file() with better performance, support for encryption (https, ftps), gzip compression, authentication, and other 'libcurl' goodies.
4. [xml2](https://cran.rstudio.com/web/packages/xml2/index.html) - The xml2 package is a binding to libxml2, making it easy to work with HTML and XML from R. The API is somewhat inspired by jQuery.

### Mapping / Spatial Analysis
1. [rgdal](https://cran.r-project.org/web/packages/rgdal/index.html) - Bindings for the Geospatial Data Abstraction Library.
2. [leaflet](https://rstudio.github.io/leaflet/) - Leaflet is the leading open-source JavaScript library for mobile-friendly interactive maps. Leaflet is designed with simplicity, performance and usability in mind.
3. [ggmap](https://github.com/dkahle/ggmap) - A collection of functions to visualize spatial data and models on top of static maps from various online sources (e.g Google Maps and Stamen Maps). It includes tools common to those tasks, including functions for geolocation and routing.
4. [tmap](https://cran.r-project.org/web/packages/tmap/vignettes/tmap-nutshell.html) - tmap is an actively maintained open-source R-library for drawing thematic maps. The API is based on A Layered Grammar of Graphics by Hadley Wickham and resembles the syntax of ggplot2, a popular R-library for drawing charts.