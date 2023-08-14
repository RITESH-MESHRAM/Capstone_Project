# Capstone_Project
# Content
The dataset below represents weekly 2018 retail scan data for National retail volume (units) and price. Retail scan data comes directly from retailers’ cash registers based on actual retail sales of Hass avocados.

Starting in 2013, the table below reflects an expanded, multi-outlet retail data set. Multi-outlet reporting includes an aggregation of the following channels: grocery, mass, club, drug, dollar and military.

The Average Price (of avocados) in the table reflects a per unit (per avocado) cost, even when multiple units (avocados) are sold in bags. The Product Lookup codes (PLU’s) in the table are only for Hass avocados. Other varieties of avocados (e.g. greenskins) are not included in this table.

# Attribute Information
Unnamed = SNo. Date = The date of the observation AveragePrice = The average price of a single avocado Total Volume = Total number of avocados sold 4046 = Total number of avocados with PLU 4046 sold(PLU 4046: non-organic small/medium Hass Avocados(~3-5 oz)) 4225 = Total number of avocados with PLU 4225 sold( PLU 4225:non-organic large Hass Avocados (~8-10 oz)) 4770 = Total number of avocados with PLU 4770 sold(PLU 4770: non-organic extra large Hass Avocados (~10-15 oz)) Total Bags = Total Number of Bags sold Small Bags = Total Number of Small Bags sold Large Bags = Total Number of Large Bags sold XLarge Bags = Total Number of XLarge Bags sold type = Organic or Conventional year = The year of observation region = The city or region of the observation

# Main Objective
Perform extensive Exploratory Data Analysis(EDA) on Avocado dataset. Build a suitable Machine Learning Model that will help vendors, producers, associations, and companies to predict the future prices of avocado.

# Conclusion
From EDA, we can conclude, the most profit giving area is Hartford Springfield and San Francisco has highest price of Avocado. People prefer large size Avocado and small bag size. There are 2 types of Avocados, 'conventional ‘and 'organic'. Out of which 'conventional' is preferred. Based upon the analysis of the result, we can suggest the company owners to enocurage the people to buy organic type of avocadoes. The vendors, companies need to concentrate on those regions in which the avocados are not sold mostly to increase their profit.

From this Score of Models, we can surely conclude that out of all the models - Linear Regression, Ridge, Decision Tree, SVm, Random Forest, AdaBoost and Gradient Boost the highest r2 score is of Random Forest and also the highest training and test accuracy also is coming from Random Forest which Training accuracy 0.9745600120455488 and Test Accuracy 0.8197808069127722 .

Our Random Forest algorithm yields the highest accuracy,83%. Any accuracy above 70% is considered good, but be careful because if your accuracy is extremely high, it may be too good to be true (an example of Overfitting). Thus, 80% is the ideal accuracy!
