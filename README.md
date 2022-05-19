# UFOs

### Overview

This project focused on utilizing javascript, html, CSS and bootstrap to build a dynamic webpage. The webpage displays a table of data pertaining to UFO sightings and this table can be filtered dynamically. A great way to display the data and make it interactive. 

### Results
Displaying the data in a table makes the data easily digestible and the filters allow a person to be able to search for specific data. There are 5 filters that allow a user to filter the data by date, city, state, country, and shape. Utlizing the search bars on the left, a user can input either a date or text to search the columns in the table. D3.js allows the table to dynamically display the filtered data. 

![Results](/static/images/1.PNG)

For example if a user wanted to search by the shape of a sighting, they could enter the shape (circle) and the table would display the filtered data. 

![Results](/static/images/2.PNG)

This can also be done with city names. The user can enter a city name and the table will display the filtered results. 


![Results](/static/images/3.PNG)


### Summary

Overall, this helps display how javascript can help with displaying data and making it interactive by allowing dynamic filtering. One drawback at the current moment is how capitalization is not currently taken into account. If a user does not enter a string exactly as its displayed then it will not show. 

### Recommendations
One recommendation would be taking care of the capitalization problem by making sure all the text entered in the search bar is first converted to lower case as all the city names, states, countries, and shapes are lowercase. Another recommendation would be adding a search box that allows a user to search the comments by that word. 
