# Belong Test

In this jupyter notebook code, I mainly focused on the following several questions which have been solved.

Before solving the questions, I have investigated the data the following ways:
- Overall summary
- Missing values
- Range of the year in the data
- Sensor_ID and Sensor_Name matching

In this part, I found that the Sensor_ID and Sensor_Name are not one-to-one relationship. There are some Sensor_IDs have more than one names which are actually same locations but with inconsitent descriptions. Then I fixed this issue before solving the questions.

The first two questions are sovled in a similar way.

I have developped two functions which allow user to input the date or month they are interested, so that, the function will return the top n most pedestrains locations by that day or month along with the graph displayed.

1. Top 10 (most pedestrians) locations by day
2. Top 10 (most pedestrians) locations by month


The last two questions are solved in a similar way
For question 3, I have investigate the count for the last 5 years, and found that there is big drop from 2019 to 2020. I calculate the decline in the last 3 years as the count(2019) - average(count(2020-2022)). There could be other ways for this, but current ways can achieve the purpose. 
3. Which location has shown most decline due to lockdowns in last 3 years
4. Which location has most growth in last year.

TODO:
If time allows, there could add more input validation, and more statistics analysis for the data. 