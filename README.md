# animated-bar-chart-in-R

What: Animated bar chart in R
How: Using `ggplot2` and `gganimate` 

**Acknowledgment:** The code used here is heavily borrowed (*You can say, inspired and copied*) from the answers of this Stack Overflow Question [Animated sorted bar chart with bars overtaking each other](https://stackoverflow.com/questions/53162821/animated-sorted-bar-chart-with-bars-overtaking-each-other)

### Potential Errors

If you faced this error `Error: The gifski package is required to use gifski_renderer`

Please install `gifski` and `png` package and try again.


### Final Output (GIF):

![GIF](gganim.gif)

### Codes

+ `gdp_data_cleanup.R` - Cleaning up the data downloaded from WorldBank Data Site
+ `animated_bar_plot_in_R.R` - Building Animated Bar Plots 


### Reproducibility 

**Packages used**:

+ `gganimate`
+ `tidyverse`

### Data Source:

The origin input data (`csv`) has been downloaded from [databank.worldbank.org](https://databank.worldbank.org/data/reports.aspx?source=2&series=NY.GDP.MKTP.CD&country=#)
