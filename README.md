# My Wildfire Analysis Project

This project graphs wildfires across the United States. The dataset shows location (longitude and latitude), reporting, time stamps and more for 1.88 million fires between 1992-2015. The wild_fires.ipynb file loads the large dataset into Postgres SQL. Using SQL queries, the project can parse the data into managable amounts. The code appends the SQL results into pandas dataframe to be used for graphing. 

So far, I've graphed every fire in the United States over 100 acres in size between 1992-2015 and a visualization comparing Native American tribal land in America, to fires reported by Native American agencies. As you can see in the /graphs folder, there is significant overlap.

Further analysis brought up interesting tangents such as the 2005 Biscuit fire (Oregon, ~500,000 acres) subsequent controversy seen here: https://en.wikipedia.org/wiki/Biscuit_Fire_publication_controversy

Also look into my tableau visualization page for additional graphs: https://public.tableau.com/profile/jeremysteele#!/vizhome/wildfires_16118741119020/Sheet1

# Citation

Short, Karen C. 2017. Spatial wildfire occurrence data for the United States, 1992-2015 [FPAFOD20170508]. 4th Edition. Fort Collins, CO: Forest Service Research Data Archive. https://doi.org/10.2737/RDS-2013-0009.4 

https://www.kaggle.com/rtatman/188-million-us-wildfires
