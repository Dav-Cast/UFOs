# UFOs

## Overview
Create a visualization of the information gathered of various UFOs sightseeings around the world with help of HTML, JS and CSS code in order to convey an easy to read and to search table so that it is accessible, easy to understand and use. 

## Results
The page can be used as follows:
1. First the table will display all the information as it has not been filtered yet, so do not get overwhelmed by it.

![table_start](https://user-images.githubusercontent.com/110573146/220732183-2a23ceaf-5008-4804-a178-ea598b724420.png)

2. There are 5 filters in total for the user to apply to the table: Date, City, State, Country and Shape. Each of these filters are targeted to get specific information from the data. Date for the time period the sightseeing took place, city, state and country are the location where it happened and shape is regarding the description of the "UFO".

3. To use a filter you have to click in the input box below the name of the filter (for example: "Enter a State). **As you can see each box has a placeholder that shows an example of how the input should be submitted.** Failing at typing the information as required will return no data in the table, as it doesn't get an exact match.

![table_start_filters](https://user-images.githubusercontent.com/110573146/220732471-f365edc8-2cf9-4bff-bedc-0a2a8e40d1b6.png)

4. Once you have written the information as asked hit "Enter" and the filter will activate and soon after will display the new table with the new data. In the next examples we will be entering "ca" for California and "mo" for Missouri, so you can see a good examplo of how to search.

![input_state](https://user-images.githubusercontent.com/110573146/220733691-0c5b5f84-6d24-4924-b902-dbc75eae2c3d.png)

![input_state_2](https://user-images.githubusercontent.com/110573146/220733731-a2debb27-123c-4632-be84-d10ea3a213a9.png)

5. You can use more than one filter at once, after using the first one as described before, move to the next filter's input box you require and repeat the same process **(without erasing the other filter)**, after hitting "Enter" you will recieve the new table data. In the next example the filters, state and shape were activated with the information "ca" for california and furthering filtering with "triangle".

![input_state_shape](https://user-images.githubusercontent.com/110573146/220734517-9544e8de-00d8-4100-87e5-5df92d28ca05.png)

6. If a input box was filled with wrong data or if there is no data regarding the user's input the table will only show the headers and no information will follow. So it it important to follow the instructions as to be 100% sure that if no results are given, that it is due to there no being information rather than a wrong input.

Wrong input: typing "California" instead of "ca", or "United States" instead of "us" will give no response.

![input_wrong_state](https://user-images.githubusercontent.com/110573146/220735475-59d16218-67a4-4e4e-9843-cbd66537e426.png)

![input_wrong_country](https://user-images.githubusercontent.com/110573146/220735503-3c6035f8-0d4d-42ac-bb15-4c3c6e2f9e76.png)

No Data: typing "roswell" for city will give no response as there is no data available for the city.

![no_data_roswell](https://user-images.githubusercontent.com/110573146/220735837-9b08df6b-ff24-46ae-bc93-5d1f1bcb9f7c.png)

## Summary
In summary the new design has a lot of advantages in the filter part, as adding 5 different filters makes it so that the users can be more specific about certain UFOs sightseeings, but of course there still room for development. A drawback that is really concerning and even could lure away users is that there is no message at all when a filter is not found even when the input was typed correctly in the format. While the app was in development it was tested with "roswell" in city, but no results were given and it was thought that the app was not working properly, but further testing showed that it was working and that there was just no info regarding to roswell. So a solution feature should be to add an error message with the detail of the error, it could read: "No information was found regarding roswell, make sure you are typing as stipulated".

Another reccomendation as to keep developing the page would be to add a display option menu in each input box as to make sure that a search has an answer and to avoid cofussion when typing the desired information. Adding up to this idea, for the date filter a mini calendar display option would be a good addition as it is easier and faster than typing the date as asked.  
