# A Web Application for Manually Tracking Locational Event Data in Ice Hockey

### Abstract

Sometimes, sports data must be tracked by hand, as desired data may not be available through existing sources, if it exists at all. But, manual tracking is often tedious and hard to translate into a useful form for analysis. In ice hockey, manual tracking is often especially necessary in women’s and youth ice hockey as data is often sparser and more difficult to access in those competitions. To aid the process of manual tracking in ice hockey and encourage an increase in the breadth and depth of data available, this work describes an open-source web application designed to reduce the hardships of manually tracking locational event data in ice hockey. The web application distinguishes itself from similar applications by its user-friendliness and high level of customizability. By clicking on a location on a rink, the corresponding coordinates of that event are logged as a table row. Details in additional columns in the table are recorded using a details panel beside the rink. The data is downloadable in \texttt{.csv} format for further exploration and analysis. New details can be created with corresponding widgets in the details panel and columns in the table. The application also provides the ability to record one or two sets of coordinates per event, for tracking events where start and end locations are desired. These custom setups of the application with new details and options can be saved and later loaded into the web application, saving time recreating the environment.

### File Explanation and External Links

The full writeup of the application is in `paper.pdf`, which is generated from `paper.tex`. The `images/` folder contains all the images included in the paper. Citations are generated from `bibliography.bib`.

The web application described in the paper can be found at [shot-plotter.netlify.app](https://shot-plotter.netlify.app/). Its source code can be found in this [GitHub repository](https://github.com/nguyenank/shot-plotter).
