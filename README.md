# SalesAnalysis_Project
This project answer some of the questions relating to random-created sales in 12 months of 2019.

I created random sales data using ./DataGeneratingScript/data_generating.py. The script utilizes random modules to both selecting random data from static input and generating new data with random class.There are 12 files which represents 12 months of the 2019 sales. I will combine all 12 to one file for this analysis.

I use Python Pandas & Python Matplotlib to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

I also used Tableau - a data visualization tool - to obtain a bigger understanding about this dataset before analyzing.
**Tableu public link**: https://public.tableau.com/views/SalesAnalysis2019/Dashboard1?:language=en&:display_count=y&:origin=viz_share_link

**We start by cleaning our data. Tasks during this section include:**

-Concatenating multiple csvs together to create a new DataFrame.

-Drop NaN values from DataFrame

-Removing rows based on a condition

-Change the type of columns (to_numeric, to_datetime)


**Once we have cleaned up our data a bit, we move the data exploration section. In this section we explore high level business questions related to our data:**

-What was the best month for sales? How much was earned that month?

-What city sold the most product?

-What time should we display advertisemens to maximize the likelihood of customer’s buying product?
**Aditional question: At that time/hour(s), what city orders the most quantity of product?**

-What products are most often sold together?

-What product sold the most? Why do you think it sold the most?


**To answer these questions we walk through many different pandas & matplotlib methods. They include:**

-Adding columns

-Parsing cells as strings to make new columns (.str)

-Using the .apply() method

-Using groupby to perform aggregate analysis

-Plotting bar charts and lines graphs to visualize our results

-Labeling our graphs

