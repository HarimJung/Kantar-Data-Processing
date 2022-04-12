# Kantar-Data-Processing
How to load Kantar meta files all together to read the B5 information to parse into 3 added columns and then merge them into one huge file

# goal: 3 months newly updated dataset preprocessing before the SQL workload

1. Set the B5 row as a Key values with Measure, Duration, and Outlet
2. Extract the B5 row information and then parse them using | 
3. extracting 1st, 3d and the last one into Appended columns as "measure", "outlet", and "duration.
4. getting all rows and columns from b9 to last filled ones into another frame
5. set the header and body seperately
6. merge all the list into a frame and then add the 3 added columns
