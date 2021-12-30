# UFOs
Overview - The task was to display a table organizing UFO data stored as a JavaScript array. The client wanted the ability to filter by multiple criteria creating a dynamic website. The table was created using JavaScript, while HTML/CSS and Bootstrap were used to modify the aesthetics of the website.

As illustrated below we can use the date to filter the results and see the sightings for a specific City. The snapshot below shows the results filtered by a specific city.

<img width="1325" alt="By_City" src="https://user-images.githubusercontent.com/92793248/147794942-e6c595a7-d49f-4f02-b3e9-b9ee553324da.png">

As illustrated below we can use the date to filter the results and see the sightings for a specific country. 

<img width="1325" alt="By_Country" src="https://user-images.githubusercontent.com/92793248/147794947-5d7c5ed1-a71c-40bf-8982-3cc9fbf7221c.png">

As illustrated below we can use the date to filter the results and see the sightings for a specific date. 

<img width="1325" alt="By_Data" src="https://user-images.githubusercontent.com/92793248/147794950-30b24870-fd7c-4ab8-a228-180944ceaf9f.png">

As illustrated below we can use the date to filter the results and see the sightings for a specific country.

<img width="1325" alt="By_Shape" src="https://user-images.githubusercontent.com/92793248/147794958-c8a5ffeb-2dc0-4806-aea0-98f4bf99ebc2.png">

As illustrated below we can use the date to filter the results and see the sightings for a specific State.

<img width="1325" alt="By_State" src="https://user-images.githubusercontent.com/92793248/147794965-7305a6ba-bffd-48ad-92b1-8098aa7924f9.png">



Drawback - The user must know specific dates, cities, or shapes to search. Some shapes like "light" might not be as intuitive. More problematically, the filters require exact match against the data being entered (i.e. require correct lower-case spellings, does not address trailing white space.) The city that was used, for example, could not be typed as "elcajon", “el cajon_”, or "El Cajon". The only acceptable input is "el cajon".

Recommendations: The next addition to the filters should be to add a trim function to catch spaces at the end of words. Allow entry using upper case and/or proper case as well exact match. Filter by date range
