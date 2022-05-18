Overview of Project:
	For this week’s analysis we are aiming to build a frontend framework for UFO sightings.  The primary focus was for DOM manipulation on building said frontend.
Results:
To search simply type in a date, city, state, country, or shape to begin.  After navigating away from the previously selected text box the table will automatically update with the new result set.  To filter more granularly just add additional filter fields and the table will automatically update.  Here is an example filter query that uses all of the filter fields Date: 1/1/2010 (see image), 

![This is an image]( https://github.com/BMoreland20/UFOs/blob/main/Resources/Step1.png)

City: san diego (see image),

![This is an image]( https://github.com/BMoreland20/UFOs/blob/main/Resources/Step2.png)

State: ca (see image),

![This is an image]( https://github.com/BMoreland20/UFOs/blob/main/Resources/Step3.png)

Country: us (see image), 

![This is an image]( https://github.com/BMoreland20/UFOs/blob/main/Resources/Step4.png)

and Shape: triangle (see image).

![This is an image]( https://github.com/BMoreland20/UFOs/blob/main/Resources/Final_Step_Results.png)

Summary:
One current drawback to this design is that changes in spelling i.e., San Diego or CA or any combination in between will result in no results populating.
My first recommendation would be to implement regex expressions to allow for multiple ways to spell the various filter fields.  This will allow for the table to be filtered by valid data points regardless of capitalization.  Another option to address this problem is to create the fields as drop-down menus so no matter what data will be present and ready to be pulled.
My second recommendation would be to remove Country as a filter field.  As it stands there is no other country in this current data set.  So, by leaving this filter in the webpage a user will continuously “break” the webpage when looking for another country that isn’t the US.  If the plan is to add more data to the data set then it would be fine to leave this field in.
