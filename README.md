# UFOs

##### Background

Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, you’ll add table filters for the city, state, country, and shape.

##### Results

![]()

As you can see on the left side of the scree, there are five possible search criteria we created: date, city, state, country, and shape.

![]()

When we enter a city, in this case el cajon, and hit enter, the table will return all the results for el cajon.

![]()

When we delete el cajon and enter in a new criteria, in this case shape, the table will return all the results that match our criteria. As you can see in this particular case circle.

![]()

We can also search multiple criteria at the same time. This search shows us all the results for circle UFOs in mason.

The website overall allows us to enter different criteria, either a single search criteria or multiple (even all five if we would like), returning our results in the table for us to see.

##### Summary

There are a couple of drawbacks that I would like to mention before recommending some improvements. First, the user cannot enter multiple ids at the same time. For instance, I could not return all the results for UFO sightings in both California and New Mexico in the same search. The second drawback is the user needs to know the correct lower case spelling of the id they are searching. For instance, in our example above the user would need to input el cajon, not El Cajon (see image below), otherwise no results would be returned.

![]()

###### Recommendations

-To remedy the first drawback, I would recommend allowing multiple search criteria for a particular search parameter, like multiple states or cities. 

-To correct the second drawback, I would recommend having the code changed to allow for upper or lower case capitalization of letters. 

-A clear button is needed to clear the search criteria. At the present moment, users need to go and clear/delete the search criteria themselves.

-For users who might not know much or just want to browse, having drop down menus for the search criteria, where users could filter the table would make it easier for either the new user or the user who just wants to see what is out there.

-Last, a much larger project would be adding a scraping file to the table to search out and constantly update the table. The table is limited by the data we already have, but I have little doubt new sightings are occurring all the time and having a way for the table to automatically update to include new sightings would make your website one of the leading websites in UFO sightings--this might also include a way for users to add their own sightings, similar to Wikipedia.
