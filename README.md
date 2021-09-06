# UFOs

## Overview of Project: 
To create a webpage with a table using JavaScript of UFO sightings data that can be filter based on one or multiple stipulations. This allows someone to filter through the larger dataset to narrow down the data for further analysis more quickly, plus displays the data in a way that is user friendly and more visually appealing than just an Excel table of the same data.

## Results: 
This webpage is designed so someone can come to the page, see all the data is an easy to read table or to look for specific data by using the Filter Search. The data for this table can also easily be kept up-to-date by simply updating the data.js file with more data, so long as that data remains in the same format currently in the data file.

To use the Filter Search there were 5 filters created for this dataset:
![image]

 - To filter by Date alone enter a date in the format m/dd/yyyy, then hit enter or click outside the box or click another box
 - To filter by City alone enter the city name all lowercase ex: portland, then hit enter or click outside the box or click another box
 - To filter by State alone enter the state initials also lowercase ex: or for Oregon, then hit enter or click outside the box or click another box
 - To filter by Country alone enter the country us for United States or ca for Canada, then hit enter or click outside the box or click another box
 - To filter by Shape alone enter the shape you are looking for all lowercase ex: circle or rectangle, then hit enter or click outside the box or click another box
 - To filter by multiple fill in two or more filter options, then hit enter or click outside the box or click another box see exmaples:
 ![image]
 ![image]
 ![image]

## Summary: 
While this is a pretty good tool if you already know all the possible shapes and how cities are labeled, a major drawback is that it is not easily searchable without that prior knowledge. For example: there is more than just simple shapes like circle or triangle. Another example: London, Canada is listed as london (canada) in this data set and if you just search london it does not show up. 

Just a few other shapes:
![image]
Seaching 'london' verses 'london (canada)':
![image]
![image]

### Recommendations for further development: 
1. Make the table more searchable:
- allow for a partial text match like 'london' or 'lond' instead of full 'london (canada)'
- account for simple typos like 'londan' instead of 'london' 
- allow for capital letters (out of habit many people might capitalize a city or state abbreviation, because a name of a place is proper noun and typically capitalized)
- add a key with all the shapes that can be searched

2. Allow for more than one search term especially in the same category for example being able to search for both circle and triangle at the same time. 
