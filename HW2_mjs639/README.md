For HW 2 I worked primarily with Valeria, Davey, and Srikanth.

Assignment 1

For assignment one, I was able to shape the foundation of my script (sys, reading the url) by referencing various notebooks and scripts in the Lab folder. I was able to quickly access the MTA API, however it wasn't until Davey showed me that Firefox automatically formatted the data in an easy-to-navigate way that I was able to parse what I was looking at.

Once the data was understandable, I figured out how to isolate each independent bus in the code (variable 'indbus'). This variable was crucial for the output of my script. I took the length of this variable to determine the number of active busses, and created a for-loop in order to pull the location of each bus within the list. I had a hard time getting the loop to properly print the desired output, but Srikanth was able to help me by showing me how to create a 'busno' counter.

Assignment 2

Assignment 2 began similarly to Assignment 1 -- I was able to use a majority of the script I had previously written in order to kick-start the assignment. I identified the paths to the desired information ('stop' and 'status') and used these to determine the full spread of info for each bus. I knew I wanted to turn these data into a list to populate my dataframe, but had a hard time figuring out how. Shrikanth helped me use my for loop to write the data to an empty list, which I was then able to use to populate my dataframe. Once the dataframe was populated, I was able to write it to a CSV file.

Once we had this part settled, we worked together to include a provision for moments when the 'stop' and 'status' values needed to be N/A. We had a tough time figuring this out, because instances where there was no value for 'stop' and 'status' were so infrequent and seemingly unpredictable. We first came up with an 'if' statement that checked whether the value was None, and assign the value to 'N/A' in these instances. Including this did not prevent the script from running properly, but we were unable to test it in real time because none of the busses we tested every listed 'N/A'. Valeria recommended we use the 'try' and 'except' functions, which might be better at capturing the error in whatever form it may be (we believe the 'if' statement would only catch the error in the instance of the field not existing, and since we did not know the nature of the error, decided this route was safer). The statement we wrote still allowed the script to run properly, so I kept this form. The 'if' statements are nullified at the bottom of my python file, if you would like to view them.

Assignment 3 & Extra Credit

I worked with Matt Dwyer and Kent Pan for Assignment 3 and the Extra Credit. We all worked together to figure out the best datasets to use for the assignemnt, along with the best methods for plotting them. Sam Ovenshine was integral in helping me access the data from http://urbanprofiler.cloudapp.net/ while the CDF was down. 
