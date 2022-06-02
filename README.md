## Calories-Burning-Calculator-and-Physical-Exercise-Optimization-Dashboard
Notice: For security purpose, all the files needed are under "master" branch.


### Brief Introduction:

In this project, I use data-driven approaches such as linear optimization (with Gurobipy in Python) and interative dashboard (with Plotly in Python) to help users control the inject of calories and live a better and healthier life. 

The dashboard has 3 tabs. For the first tab, I use Python to collect info of fast food restaurants and their corresponding menus from unofficial website, and combining with users’ choices, present total calories and other nutritions they take with various tables and charts. For the second tab, based on the results of the first tab, users' preferences of exercises and maximum time they can allocate to exercise, I construct an abstract linear optimization function with gurobi package in Python and provide them the optimized combination of exercises. For the last tab, I design a table that includes additional information about the calories of fast food. This project includes whole steps of data processing: web scraping, data cleaning, data exploring, data analysis, data modeling and data visualization.



### File Explanation:

This project divides the whole process into three steps: data gathering, data cleaning and data visualization.

(1) Web Scraping and Data Merging:
- Restaurant Web Scraping: The codes needed for scraping 154 restaurants information from website.
- Data Merging: Merging 154 files into a single CSV file.

(2) Data Cleaning (includes all materials needed):
- Final Cleaning Code: The codes needed for cleaning the merging dataset.
- restaurantfinalmerge: CSV file that are used for this step. (includes all information of restaurant, the result of previous step)

(3) Visualization Dashboard (includes all materials needed):
- Fast Food Nutrition Calculator Dashboard: The codes needed for constructing interative dashboard.
- TAB1 SCREENSHOT: Screenshot for tab1.
- TAB2 SCREENSHOT: Screenshot for tab2.
- TAB3 SCREENSHOT: Screenshot for tab3.
- CleanedRestaurant: CSV file that includes cleaned information of restaurants.(the result of previous step)
- exercise_data: CSV file that includes different kinds of exercise and calories they can consume. (data source: Kaggle)
- junk: Picture that will be used in the dashboard.
- optimal_ex: Picture that will be used in the dashboard.
- single_ex: Picture that will be used in the dashboard.
