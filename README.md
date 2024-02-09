# Sales-Data-analysis-project

![Screenshot 2024-02-09 094829](https://github.com/MateusDBaza/Sales-Data-analysis-project/assets/67308258/75a00f9f-1ed8-4342-92f7-fb7ea747bcd5)

In this project I used Python Pandas & Python Matplotlib to analyze and answer business questions about 12 months worth of sales data.
The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc. 


We start by cleaning our data. Tasks during this section include:
- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime, astype)

Once we have cleaned up our data a bit, we move the data exploration section.

In this section we explore 5 high level business questions related to our data:

1- What was the best month for sales? How much was earned that month?

2- What city sold the most product?

3- What time should we display advertisemens to maximize the likelihood of customer’s buying product?

4- What product sold the most? 

5- Most sold product: Why do you think it sold the most?

To answer these questions we walk through many different pandas & matplotlib methods. They include:
- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling our graphs
