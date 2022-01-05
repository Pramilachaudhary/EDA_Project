# EDA_Project Proposal

**What is the framing question of your analysis, or the purpose of the model/system you plan to build?**

The purpose behind this analysis is to help Mr.and Mrs. Cooper who owns a small breakfast place in Newyork city and are planning to install 
vegan/gluten free sandwiches/wraps vending machines in Subways for daily commuters. At most only 8 vending machines are going to be installed 
because of the budget crunch and the best approach to gain the profit out of the machines is by installing them in such stations which are most 
crowded in order to sell more products. 

**Who benefits from exploring this question or building this model/system?**

Mr. and Mrs. Cooper will benefit from the analysis, which determines the best stations to install the vending machines in order to increase 
the monthly profit and future investment scope.

**What dataset(s) do you plan to use, and how will you obtain the data?**

3 months of data from MTA Turnstile Data : http://web.mta.info/developers/turnstile.html


**What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with?**

Features that are included in this analysis would be Station, Date, Time, Entries and Exits.

**If modeling, what will you predict as your target?**
I am planning to target the maximum number of morning commuters between (8am to 10am) on weekdays at a specific station in order to increase the sales.

**Tools:**
Python libraries such as pandas, numpy, sqlalchemy and  matplotlib for visualization. sqlite db browser for data cleaning.

**MVP Goal:**
My goal is to find at most 8 busiest stations in the morning hours on weekdays.


