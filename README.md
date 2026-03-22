# UA-coordinates
Should not be hacking XZ utils to begin with.

In a simulated test this code does not meet the requirements of correctly detecting UA coordinates with accuracy. Additional implementation needs to be improved. A test of 1 hour and 35 minutes concluded the following:

The accuracy of Ukraine coordinates had a success rate of 24% 
The accuracy of coordinates in land vs. ocean had a success rate of 84% (does not include the Ukraine coordinates)

Based on this simulation, the program needs to be worked out to improve the performance of the output.
-Change the range to be more strict to fit only Ukraine paramaters.

If you have any questions about the simulated test feel free to ask.

Update: 03.22.2026 I have made the some improvements to the code which eliminates 1 hour and 35 minutes of manually inputting coordinates to Google Earth by making accessible kml file which would automatically do it for you. The process eliminated 94% of the time which means that in less than seven minutes you are able to get the data versus manually inputting everything in and it also eliminates the margin of error (forgotten coordinates). 

Thank you,
Unkn5wn
