# Incarceration
U.S. Incarceration Rates - Total vs Black Populations

This project studies the difference in the incarceration rates of the Black population vs the incarceration rates of the total population in the U.S. between the years from 1990-2016.

Files in this project include wrangled data in csv format, python scripts and project notes.

### Visualizations of the study can be found on [Tableau Public Incarceration Rates](https://public.tableau.com/app/profile/liz.gewirtz/viz/IncarcerationRates_16280989165760/IncarcerationRates).

### Limitations
Since youth under age 15 and adults over 64 are at very low risk of jail incarceration, Vera removed these groups from the dataset. 

Since there were many null values in the years 1970-1989 and 2017-2018, this study used only data from 1990-2016.

### Data Source
This dataset was sourced from the [Vera Instituite of Justice’s Github Account - Incarceration Trends Dataset](https://github.com/vera-institute/incarceration-trends) [Retrieved 6/27/2021].  It includes County and jurisdiction level jail data (1970-2018) and prison data (1983-2016). 

More information on the Vera Data set can be found on their [Trends About Webpage](http://trends.vera.org/about) and their [Github Account](https://github.com/vera-institute/incarceration-trends).

The shape file for the map in the Tableau viz, cb_2016_us_state_5m_AKHIShift-fauxWebMercator, can be found at https://drive.google.com/drive/folders/1ci8-Ymj8em8YMwY5tX2v6BF6b5EioPQN which you can read about at [The Flerlage Twins blog](https://www.flerlagetwins.com/2021/03/alternative-map-projections-in-tableau.html).





