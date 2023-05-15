# Instagram-analysis
Analysis of instagram reach over a period of time to get useful insights that drive decision making

# Steps
1. Import the necessary libraries
2. Read the data
3. Convert the dtype of the date column to datetime
4. Analyse the trend of the instagam reach over time using a line chart
5. Analyse the instagram reach for each day using a bar chart 
6. Using a boxplot, analyse the distribution of the instagram reach
7. Create a day column so we can analyse reach based on the day of the week. We do this by using dt.day_name() to extract the day of the week from the date column
8. Move on to the analysis proper using days of the week. Using the groupby function via the day column we can calculate the mean, median and standard deviation of the instagram reach for each day.
9. Visualize the above information using a bar chart (For each day of the week)


# Conclusion:
1. From the above we can ascertain that the best days to post content are on Tuesday, Sunday and Monday respectively according to the bar chart above.
2. The month of September is the month where content gets the highest reach as seen from the line chart above.
3. Therefore Tuesdays, Sundays and Mondays of september should be maximized to get enough reach that in turn will hopefully generate    desired end results.     
