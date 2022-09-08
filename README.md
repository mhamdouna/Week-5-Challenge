# Week-5-Challenge
Pharmaceutical Challenge

# First, import the dependencies
# Then read the data files and store them into objects
# Merge both data frames created for both files into one data frame

# Check the number of unique mice
# Locate duplicated mice using the .duplicated method
# Create a new data frame with the duplicates removed using the .drop_duplicates method


# Find statistical data for the different regimens using the .groupby method, then using the different .mean(), .median(), .var(), .std(), and .sem()
# Create a new data frame with the information above. 
# Use the .agg() method to do the above in a single line. 
# Create bar charts using Pandas and pyplot for timepoints vs. number of mice. Both charts are idential.
# Geenrated pie charts for female vs. male mice distribution using both pandas and pyplot. Both charts are identical.


# Find the last greatest timpoint by using the .groupby method then using the .max() method 
# Merge above data frame with the cleaned data frame created previously. 
# Find quartiles, iqr, lower and upper bounds by looping through regimens list, and populate tumour data into the empty list created.
# Create box plots with all 4 different regimens outlined above. 

# Create a Capomulion data frame by using booleans on the clean_df created above. 
# Choose a mouse (s185) and draw a line chart for tumour volume vs. timepoints.
# Create a scatter chart for tumor volume vs mouse weight(g)


# Calculate the correlation coefficient and linear regression model, and draw the equation line on the scatter plot created above. 
