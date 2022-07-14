#  :city_sunset: World_Weather_Analysis   :sunrise_over_mountains:

## :palm_tree: Overview

- Weather data from across 500+ world cities was collected and analyzed in real time.
- The data was later set to a parameter of 70-90 degrees in order to recommend ideal hotels based on clients' weather preferences in that temperature range.

  - [Original database](https://github.com/Super-Manda/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database.ipynb)

  - [Original CSV](https://github.com/Super-Manda/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_Database.csv)


## :cactus: Analysis

### :snowman_with_snow: Collect the Data
- **Here is an excerpt from the entire database:**
![Summary_Dataframe](https://github.com/Super-Manda/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database_DF_head.png)

  
###
- **Later, areas with no hotels were dropped.  Goodbye, Albany!**  :statue_of_liberty:
![Drop None](https://github.com/Super-Manda/World_Weather_Analysis/blob/main/Vacation%20Search/Dropped%20the%20rows%20with%20no%20hotels.png)

- **The final CSV file regarding hotels is here:**
[Hotel_CSV](https://github.com/Super-Manda/World_Weather_Analysis/blob/main/Vacation%20Search/Hotel_CSV.csv)


:parasol_on_ground:  **Here is a map of possible vacation destinations from the vacation search that remained...**
![Vacation Search PNG](https://github.com/Super-Manda/World_Weather_Analysis/blob/main/Vacation%20Search/Possible%20Vacation%20Destinations.png)

**in the [Vacation Search File](https://github.com/Super-Manda/World_Weather_Analysis/blob/main/Vacation%20Search/Vacation_Search.ipynb)!**


###  Vacation Itinerary
*Given this overall heat map with markers...**
![Overall heat map with markers](https://github.com/Super-Manda/World_Weather_Analysis/blob/main/Vacation%20Itinerary/optional%20heat%20map%20of%20all%20cities.png)


**Four cities in Mexico were selected on this bicycle route along unnamed roads:**
![Mexico Map](https://github.com/Super-Manda/World_Weather_Analysis/blob/main/Vacation%20Itinerary/WeatherPy_travel_map.png)


###  Visualization of this Travel Data
- **Here is a heat map with pop-up markers that shows specific cities' information based upon the travel preferences.**
![Mexico heat map with markers](https://github.com/Super-Manda/World_Weather_Analysis/blob/main/Vacation%20Itinerary/WeatherPy_travel_map_markers.png)
