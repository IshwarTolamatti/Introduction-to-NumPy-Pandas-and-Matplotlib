# Introduction-to-NumPy-Pandas-and-Matplotlib

CaseStudy-1

1. Extract data from the given SalaryGender CSV file and store the data from each column in a separate NumPy array
2. Find: 1. The number of men with a PhD 2. The number of women with a PhD
3. Use SalaryGender CSV file. Store the “Age” and “PhD” columns in one DataFrame and delete the data of all people who don’t have a PhD
4. Calculate the total number of people who have a PhD degree from SalaryGender CSV file.
5. How do you Count The Number Of Times Each Value Appears In An Array Of Integers?
[0, 5, 4, 0, 4, 4, 3, 0, 0, 5, 2, 1, 1, 9]
Answer should be array([4, 2, 1, 1, 3, 2, 0, 0, 0, 1]) which means 0 comes 4 times, 1 comes 2 times, 2 comes 1 time, 3 comes 1 time and so on.
6. Create a numpy array [[0, 1, 2], [ 3, 4, 5], [ 6, 7, 8],[ 9, 10, 11]]) and filter the elements greater than 5.
7. Create a numpy array having NaN (Not a Number) and print it.
array([ nan, 1., 2., nan, 3., 4., 5.])
Print the same array omitting all elements which are nan
8. Create a 10x10 array with random values and find the minimum and maximum values.
9. Create a random vector of size 30 and find the mean value.
10. Create numpy array having elements 0 to 10 And negate all the elements between 3 and 9
11. Create a random array of 3 rows and 3 columns and sort it according to 1st column, 2nd column or 3rd column.
12. Create a four dimensions array get sum over the last two axis at once.
13. Create a random array and swap two rows of an array.
14. Create a random matrix and Compute a matrix rank.
15.
Phase 1 - Data Collection
Phase 2 - Group data by school ratings
Phase 3 – Correlation analysis
Phase 4 – Scatter Plot
Phase 5 – Correlation Matrix

CaseStudy-2

Domain – Education
focus – Data analysis
Business challenge/requirement
You are a data analyst with University of Cal USA (Not a machine learning expert yet as you still have not completed ML with Python Course :-)).The University has data of Math, Physics and Data Structure score of sophomore students. This data is stored in different files. The University has hired a data science company to do analysis of scores and find if there is any correlation of score with age, ethnicity etc. Before the data is given to the company you have to do data wrangling.

Key issues
Ensure students identify is not revealed to the agency and only relevant data is shared
Considerations

Approach to Solve
You have to use fundamentals of Numpy and Pandas covered in module 4.
1. Read the three csv files which contains the score of same students in term1 for each Subject
2. Remove the name and ethnicity column (to ensure confidentiality)
Module 4 – Introduction to NumPy, Pandas & Matplotlib
3. Fill missing score data with zero
4. Merge the three files
5. Change Sex(M/F) Column to 1/2 for further analysis
6. Store the data in new file – ScoreFinal.csv

CaseStudy-3

1. You are given a dataset, which is present in the LMS, containing the number of hurricanes occurring in the United States along the coast of the Atlantic. Load the data from the dataset into your program and plot a Bar Graph of the data, taking the Year as the x-axis and the number of hurricanes occurring as the Y-axis.
2. The dataset given, records data of city temperatures over the years’ 2014 and 2015. Plot the histogram of the temperatures over this period for the cities of San Francisco and Moscow.
3. Create csv file from the data file available in LMS which goes by the name ‘M4_assign_dataset’ and read this file into a pandas data frame
4. Let the x axis data points and y axis data points are
X = [1,2,3,4] y = [20, 21, 20.5, 20.8]
5.1: Draw a Simple plot
5.2: Configure the line and markers in simple plot
5.3: configure the axes
5.4: Give title of Graph & labels of x axis and y axis
5.5: Give error bar if y_error = [0.12, 0.13, 0.2, 0.1]
5.6: define width, height as figsize=(4,5) DPI and adjust plot dpi=100
5.7: Give a font size of 14
5.8: Draw a scatter graph of any 50 random values of x and y axis
5.9: Create a dataframe from following data
'first_name': ['Jason', 'Molly', 'Tina', 'Jake', 'Amy'],
'last_name': ['Miller', 'Jacobson', 'Ali', 'Milner', 'Cooze'],
'female': [0, 1, 1, 0, 1],
'age': [42, 52, 36, 24, 73],
'preTestScore': [4, 24, 31, 2, 3],
'postTestScore': [25, 94, 57, 62, 70]
Draw a Scatterplot of preTestScore and postTestScore, with the size of each point determined by age
5.10: Draw a Scatterplot from the data in question 9 of preTestScore and postTestScore with the size = 300 and the color determined by sex

CaseStudy-4

Domain – Retail
focus – Visualize the sales data
Business challenge/requirement
BigMart is one of the biggest retailer of Europe and has operations across multiple countries. You are a data analyst in IT team of BigMart. Invoice and SKU wise Sales Data for Year 2011 is shared with you. You need to prepare meaningful charts to show case the various sales trends for 2011 to top management.

Key issues
Data should be displayed pictorially to capture the attention of top management

Approach to Solve
You have to use fundamentals of Matplotlib covered in module 5 and plot following 4 chart/graph
1. Plot Total Sales Per Month for Year 2011. How the total sales have increased over months in Year 2011. Which month has lowest Sales?
2. Plot Total Sales Per Month for Year 2011 as Bar Chart. Is Bar Chart Better to visualize than Simple Plot?
3. Plot Pie Chart for Year 2011 Country Wise. Which Country contributes highest towards sales?
4. Plot Scatter Plot for the invoice amounts and see the concentration of amount. In which range most of the invoice amounts are concentrated
