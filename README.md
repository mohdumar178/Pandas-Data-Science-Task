# Pandas-Data-Analysis-Tasks
Set of real world data science tasks completed using the Python Pandas library.
## Background Information:

I started by cleaning my data, which involved several tasks:

- Dropped NaN values from the DataFrame.
- Removed rows based on specific conditions.
- Changed the type of columns using methods like `to_numeric`, `to_datetime`, and `astype`.

Once I had cleaned up the data, I moved to the data exploration section. Here, I explored five high-level business questions related to my data:

1. What was the best month for sales? How much was earned that month?
2. Which city sold the most products?
3. What time should we display advertisements to maximize the likelihood of customers buying products?
4. What products are most often sold together?
5. Which product sold the most, and why do I think it sold the most?

To answer these questions, I used various pandas and matplotlib methods, including:

- Concatenating multiple CSVs together to create a new DataFrame using `pd.concat`.
- Adding columns to the DataFrame.
- Parsing cells as strings to create new columns with `.str`.
- Utilizing the `.apply()` method.
- Performing aggregate analysis using `groupby`.
- Plotting bar charts and line graphs to visualize the results.
- Labeling the graphs for better understanding.

This approach helped me gain valuable insights into the data and address the business questions effectively.
