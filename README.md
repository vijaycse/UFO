# UFOs
Click here to view the HTML file and JavaScript file: [index.html](https://github.com/vijaycse/UFOs/blob/master/index.html) | [app.js](https://github.com/vijaycse/UFOs/blob/master/static/js/app.js)

## Overview of Analysis
The goal of this analysis is to create a webpage with a dynamic table that shows the filtered results of the UFO sightings data. The original webpage that was created only provided users with a date filter. However, for this project, we want to allow users to filter the data with more than just the date. Additional filters for the table will include city, state, country, and shape.

## Results
Previously, the webpage included only a date filter in which users needed to click on a button for the filter to be applied. With the new updated version, users will be able to filter data, simply by inputting a criteria into one of the filter fields. The webpage will then automatically filter the table to display relevant data. The first image ilustrates the table without filters. Users can see the type of format that is required for the filter to function in the text box. Upon input, the table will automatically filter the results accordingly.

![unfiltered_table](https://github.com/vijaycse/UFOs/blob/master/resources/unfiltered_table.PNG)

![filtered_table](https://github.com/vijaycse/UFOs/blob/master/resources/filtered_table.PNG)

## Summary of Analysis
A small improvement possible is that it is not responsive right now. Some portion of the webpage, such as the image, is able to resize if the user magnifies the webpage, however, the webpage as a whole is unable to do so. Thus, one recommendation for further development would be to add formatting that readjusts the sections and margins when the page is viewed on a mobile device or tablet using something like bootstrap.js, react frameworks that natively provides response sites.
