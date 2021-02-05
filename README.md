# My Wildfire Analysis Project

This project graphs wildfires across the United States. The dataset shows location (longitude and latitude), reporting agency codes, time stamps and more for 1.88 million fires between 1992-2015. The wild_fires.ipynb file loads the large dataset into Postgres SQL. Using SQL queries, the project can parse the data into managable amounts. The code appends the SQL results into pandas dataframe for graphing. 

I've graphed every fire in the United States over 100 acres in size between 1992-2015. The largest fires over 5000 acres centralize in the Northern Rocky Mountains. The remote area and lack of population most likely contributes to this. In the graph, you can see fires over 5000 acres in a line across Eastern Florida. What the infrastructural causes of this? You see a lack of large fires across the north midwest around Illinois and Ohio. There is a interesting corridor going north from Lousisana that mirrors the Mississipi river. The fire repressing nature of the Missipipi river is impressive, and deserves further research.

The next visualization compares Native American tribal land, to fires reported on by Native American agencies. There is significant overlap across tribal lands, except in Western Oklahoma. Looking at the total fires map, there are still large fires in Western Oklahoma. There must be jurisdiction changed or issues in the area. 

Further analysis brought up interesting tangents such as the 2002 Biscuit fire (Oregon, ~500,000 acres). The later controversy can be seen here: https://en.wikipedia.org/wiki/Biscuit_Fire_publication_controversy

My tableau visualization page has more graphs. https://public.tableau.com/profile/jeremysteele#!/vizhome/wildfires_16118741119020/Sheet1

# Citation

Short, Karen C. 2017. Spatial wildfire occurrence data for the United States, 1992-2015 [FPAFOD20170508]. 4th Edition. Fort Collins, CO: Forest Service Research Data Archive. https://doi.org/10.2737/RDS-2013-0009.4 

https://www.kaggle.com/rtatman/188-million-us-wildfires
