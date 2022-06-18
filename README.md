# UFOs #

## Project Overview ##
The client for this project is seeking to create an interactive table to filter through UFO sighting data, which is being stored in a JavaScript array.
![fullsite](https://github.com/TRACIE-F/UFOs/blob/main/static/images/fullsite.png)

## Results ##
Utilizing the interactive table is as simple as entering pertinent serach criteria in the section labeled "Filter Search." 

**Search Function**
  * The users can filter through the UFO sighting date, city, state, country, or sighting shape.
  * The data must match the format outlined in the sample text - for example, users would need to type in *az* instead of *AZ* or the table will not display any results.
  * Users can enter only one search field or multiple fields to narrow down their search.The image below filters the date, state, and sighting shape.
  * ![multi-search](https://github.com/TRACIE-F/UFOs/blob/main/static/images/multi-filter.png)
  * Most importantly, hit "enter" to execute the search!

**Table Results**
Once the user hits "enter" to execute the search, the appropriate data will appear in a table to the right of the search bars, with the headers *Date, City, State, Country, Shape, Duration,* and *Comments*.
![basedata](https://github.com/TRACIE-F/UFOs/blob/main/static/images/basedata.png)

## Summary ## 
Expanding the search functionality creates ample opportunity to seek out very specific information, but unfortunately opened the door for some frustrating limitations for the search functionality.

**Search Functionality Limitations**
There are several steps I would consider taking to solve search frustrations.

1. Expand the capacity to understand various inputs. For the city, state, and country searches, users should be able to get the results for
  * Arizona by typing *AZ* in addition to *az*
  * United States by typing *US* in addition to *us*
  * Fresno by typing *Fresno* in addition to *fresno*
![search_az](https://github.com/TRACIE-F/UFOs/blob/main/static/images/Search_az.png)
![SearchAZ](https://github.com/TRACIE-F/UFOs/blob/main/static/images/SearchAZ.png)

2. Adding a legend for the sighting shapes would be extremely useful. While individuals could utilize the search function to snag data from a specific city, state, or date, guessing potential entries for the sighting shape would be difficult. A drop-down box might be appropriate for the limited data. 

3. A bonus action would be to explore what happens to the search when data from other countries are added and they lack entries for the *State* column. 
