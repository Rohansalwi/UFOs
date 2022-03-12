# UFOs
UFO Sightings data population using JavaScript

### Purpose
Describe JavaScript syntax and ideal use cases.
Build and deploy JavaScript functions, including built-in functions.
Convert JavaScript functions to arrow functions.
Build and deploy forEach (JavaScript for loop).
Create, populate, and dynamically filter a table using JavaScript and HTML

### Overview
The client requested to display a table organizing UFO data stored as a JavaScript file. The client wanted the ability to filter by multiple criteria creating a dynamic website. The table was created using JavaScript, while HTML/CSS and Bootstrap were used to modify the aesthetics of the website.

### Results:
Welcome to UFO Sightings!

<img width="1405" alt="Screen Shot 2022-03-10 at 11 38 11 AM" src="https://user-images.githubusercontent.com/96554223/157711114-9d6b2bbc-1e79-4c3d-ad67-7b270b1ebca3.png">

How the filters appear when first landing on the page:

<img width="1416" alt="Screen Shot 2022-03-10 at 11 39 09 AM" src="https://user-images.githubusercontent.com/96554223/157711279-9e7da131-9722-4e27-89df-124247520c0e.png">

How the filters appear after being used:
By typing in the suggested placeholder elements as the filters, the result returns 2 matches. Make sure to type everything in lower case letters and do not have spaces at the end of the text. Click off the input box or press enter to initiate the filter. To reset the filter criteria, click the UFO Sightings at the top left of the website.

<img width="1407" alt="Screen Shot 2022-03-10 at 11 40 26 AM" src="https://user-images.githubusercontent.com/96554223/157711527-d29f0a4f-1805-4b74-98d9-359468b80617.png">

### Summary:
Drawback:
The user must know specific dates, cities, or shapes to search. Some shapes like "light" might not be as intuitive. The filters require correct lower-case spellings and cannot include spaces at the end. The city that was used, for example, could not be typed as "elcajon", “el cajon_”, or "El Cajon". The only acceptable input would be "el cajon".

### Recommendations:
The next addition to the filters should be to add a trim function to catch spaces at the end of words as well as allow for upper and lower cases.

<img width="1412" alt="Screen Shot 2022-03-10 at 11 41 58 AM" src="https://user-images.githubusercontent.com/96554223/157711832-d353c472-06c7-4f3a-b05a-f1b68ba9ca93.png">

A filter on a date range might be preferable than a singular date. Typing 1/2010 did not bring up all the dates from January as hoped. Perhaps, the UFO Sightings occur more frequently in a specific month instead of a specific day within the month. It is recommended to add in a filter function to include a date range as the filter to aid in the investigation of UFO Sightings.

<img width="1419" alt="Screen Shot 2022-03-10 at 11 42 48 AM" src="https://user-images.githubusercontent.com/96554223/157712000-93f69749-a85f-483d-b6ad-76356651bfe5.png">
