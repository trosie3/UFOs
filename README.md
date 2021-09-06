# UFOs

## Overview of Project: 
To create a webpage table of UFO sightings data that can be filtered on one or multiple stipulations. This allows someone to filter through the larger dataset to narrow down the data for further analysis more quickly, plus displays the data in a way that is user friendly and more visually appealing than just an Excel table of the same data.

## Results: 
![image](https://github.com/trosie3/UFOs/blob/main/static/images/imageofwebpage.png)

This above image of the webpage created with JavaScript, D3, and html is designed so someone can come to the page, see all the data is an easy-to-read table or to look for specific data in that table by using the Filter Search. The brightside to this setup is the data for the table on this page can easily be kept up-to-date with the latest sightings by simply updating the data.js file, so long as that data remains in the same format currently in the data file.

<img src="https://github.com/trosie3/UFOs/blob/main/static/images/filters.png" width=20% height=20% align=right>
There were 5 filters options created for the table on this webpage under the Fliter Search section Date, City, State, Country and Shape.

How To Apply Filters:

 - By Date alone enter a date in the format m/dd/yyyy, then hit enter or click outside the box or click another box
 - By City alone enter the city name all lowercase ex: portland, then hit enter or click outside the box or click another box
 - By State alone enter the state initials also lowercase ex: or for Oregon, then hit enter or click outside the box or click another box
 - By Country alone enter the country us for United States or ca for Canada, then hit enter or click outside the box or click another box
 - By Shape alone enter the shape you are looking for all lowercase ex: circle or rectangle, then hit enter or click outside the box or click another box
 - By multiple fill in two or more filter options, then hit enter or click outside the box or click another box see examples below:
 
 <img src='https://github.com/trosie3/UFOs/blob/main/static/images/filledinfiltersex1.png' align=center width=60% height=60%>
 <img src='https://github.com/trosie3/UFOs/blob/main/static/images/filledinfiltersex2.png' align=center width=60% height=60%>
 <img src='https://github.com/trosie3/UFOs/blob/main/static/images/filledinfiltersex3.png' align=center width=60% height=60%>

## Summary: 
While this is a pretty good tool if you already know all the possible shapes and how cities are labeled, a major drawback is that it is not easily searchable without that prior knowledge. For example: there are more than just simple shapes like circle, rectangle or triangle in this dataset. Another example: London, Canada is listed as 'london (canada)' under city in this dataset and if you search 'london' it does not show up. 

Just a few other shapes in the dataset:

<img src='https://github.com/trosie3/UFOs/blob/main/static/images/filterdownsidepart3.png' width=10% height=10%>

Seaching 'london' verses 'london (canada)':

<img src='https://github.com/trosie3/UFOs/blob/main/static/images/filterdownsidepart2.png' width=50% height=50%><img src='https://github.com/trosie3/UFOs/blob/main/static/images/filterdownsidepart1.png' width=50% height=50%>

### Recommendations for further development: 
1. Make the table more searchable:
   - allow for a partial text match like 'london' or 'lond' instead of full 'london (canada)'
   - account for simple typos like 'londan' instead of 'london' 
   - allow for capital letters (out of habit many people might capitalize a city or state abbreviation, because a name of a place is proper noun and typically capitalized)
   - add a key with all the shapes that can be searched

2. Allow for more than one search term in a filter, for example allowing to search for both circle and triangle at the same time rather than only one at a time.

The first recommendation allows for more human error in the input fields as well as making the search criteria simpler, and the second allows for quicker analysis if searching for multiple terms under the same filter.
