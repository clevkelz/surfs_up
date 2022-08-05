# Surfs Up
## Overview

An analysis was conducted to determine if weather patterns in Oahu support the opening of a combined surf and ice cream shop.  The first step was to collect weather and precipitation data from measurement stations in the State of Hawaii for the time period of January 1, 2010 to August 23, 2017.  Weather data from the months of June and December were then reviewed to determine if weather patterns from different types of the year were consistent and favorable to sustain a successful surf and ice cream shop.

## Locations of Weather Stations

The data collected originated from nine weather stations in Hawaii, mostly on the Island of Oahu.  The following table sorts these stations by the frequency of observations made during the time period.

|Station Number[^1]|Location (including island)|Number of Observations[^2]|
|--------------|---------------------------|----------------------|
|USC00519281|Waihee, Maui|2,772|
|USC00519397|Waikiki, Oahu|2,724|
|USC00513117|Kaneohe, Oahu|2,709|
|USC00519523|Waimanalo, Oahu|2,669|
|USC00516128|Manoa, Oahu|2,612|
|USC00514830|Kualoa Ranch, Oahu|2,202|
|USC00511918|Honolulu, Oahu|1,979|
|USC00517948|Pearl City, Oahu|1,372|
|USC00518838|Upper Wahiawa, Oahu|511|

This table shows that there are sufficient data observations from which to draw a conclusion.  Although some stations have more limited data, five of the nine stations have a least 2,500 observations over the time period.

## Results

The following two screenshots show summary statistics for temperature readings, including the average, minimum, and maximum temperatures, in June and December.

_June_

![image](https://user-images.githubusercontent.com/106293233/182980680-4559c66b-1091-47fc-8071-c0a665b98572.png)

_December_

![image](https://user-images.githubusercontent.com/106293233/182980740-643b081f-b86e-4a7f-970a-b5fdca1b434d.png)

The results reveal the following:
- The average temperature for both months tops 70º, indicating that expected temperature throughout the year does not vary much and would likely support the demand for surfing materials and ice cream year round.
- The standard deviation for temperatures is somewhat higher in December than in June which shows that temperatures vary more in the latter part of the year but this difference is not large.  Although there will probably be more inclement days in December, the historical data shows that there are still enough nice days during that time to sustain operations.
- The maximum temperature for both months is almost the same (85º in June and 83º in December).  Extreme temperatures on the high end (for example, greater than 95º) could negatively impact demand but perhaps not to the extent as temperatures on the low-end.  This supports the other two points made in this section; that is, weather around Oahu is consistently nice throughout the year.





[^1]: The metadata related to weather recording stations can be found on the National Centers for Environmental Information, which is part of the National Oceanic and Atmospheric Administration: https://www.ncei.noaa.gov/pub/data/ghcn/daily/ghcnd-stations.txt
[^2]:  The code to obtain the number of observations for each station is found in the Climate Analysis Jupyter Notebook file in this repository.  See: https://github.com/clevkelz/surfs_up/blob/main/climate_analysis.ipynb
