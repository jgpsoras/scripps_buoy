# scripps_buoy



This Jupyter Notebook uses Python, Pandas, and Matplotlib to analyze a text file with various ocean data from an NOAA buoy located at Scripps. 
It contains data from a period of 45 days (February 28th, 2022 through April 14th, 2022), with samples every 30 minutes.

Its given columns are:

    YY - year
    MM - month
    DD - day
    hh - hour
    mm - minute
    WVHT - wave height
    DPD - dominant wave period (time between waves for the swell with the most energy). There are usually multiple different swells in the water at the same time, each swell has its own characteristics of size, period, and direction.
    APD - average wave period (average time between waves for all the different swells in the water)
    MWD - wave direction of the dominant swell. It is measured in degrees, 270 is from due west, 180-270 is from the south, 270-360 is from the north.
    WTMP - water temperature

The text file is in the Github repository. Data source: https://www.ndbc.noaa.gov/station_page.php?station=46254

