# tableau
# my tableau public link
https://public.tableau.com/app/profile/roopa1891

#module 3
1) Text Table: 
Create a Text Table that displays profit as a function of Product Sub-Category and Year. Represent the data as Percentage of each cell with respect to the entire table. Display the grand Totals for Rows and Columns. Explain your interpretation of the data.

2) Highlight Table:
 Create a Highlight Table the displays the Sales, Profit, Discount and Quantity for all the Sub-Categories. Highlight the data based on the respective Measure Value. Use different colours for different measures to help understand the data easily
 
 3) Pie Chart: 
Create a Pie Chart showing the Profits of Superstore for different Regions. Compare the pies across different Categories. Which Category has the highest Profit? Further, in the Category with highest profit, identify the region with highest profit.

4) Bar Graph:
The Regional Sales Managers of Coffee Chain is interested in an analysis of profit by product. They will use this data to discuss the possible pricing changes and product cancellations. Create a Bar graph to help in this analysis.
Hint: Use Coffee Chain Data. Create a calculated field to check (profit - Budget Profit). Use this field to colour the Bars.

5) Bar Graph: 
Regional Managers of Coffee Chain want to perform Profit Spotlighting. Indicate the products with profits greater than $10,000 in Green colour, profit below $1000 in Red Colour and rest of the products in Grey Colour. Use Conditional formatting to accomplish this.


#module 4
1) Hierarchy:
Create a Hierarchy to Drill Down through the Location data present in Superstore on the view. (Hint: Country -> Region -> State -> City -> Postal Code)

2) Highlighter: 
Create a Line Chart showing the trends of Monthly Sales and Profits of Superstore, across different Categories. Use Highlighter feature to make the chart readable.

3) Filters:  Create a top five conditional filter that will update the top five Customers by Sales based on the region selected in the “Region” filter

4) Filters: Create a text table displaying the list of Top 3 cities by profit in each state.
Hint:Rank the cities by their profit. Bring “Profit” to the Rows Shelf, and apply Quick Table Calculation “Rank”, this should be “Compute Using -> City”. Change the Sum{Profit) pill to discrete. You will be able to see the cities ranked by profit.

5) Sets: How many customers of the Top 100 list by Profits are also present in Top 100 list by Sales?

#module 6
1) Dual Combination Chart: 
Create a chart to display the Shipping Cost and Profits of superstore for different Months. Use Global Superstore.xls data source.

2) Data Interpreter: 
Using the “AMZN Stock.pdf” input data source, observe the data on the data grid before and after using the “Data Interpreter” Option. Explain the differences.

3) Bullet Graph: 
The Product Manager of Coffee Chain needs a report showing all the products and information on which products could meet the “Sales Target (Budget Sales)”. They will use the report to check how to improve sales.

4) Tree Map: Create a chart to show Profit and Sales information for distinct products available. Use Product Id.	

5) Reference Band: 
Product Manager of Coffee Chain would like to analyse the product sales information. Use reference bands to help him group the data into different categories as “High Sales”, “Medium Sales” and “Low Sales” products.


#module 7
1) Scatter Plot: 
Using the “Wind Mill.xls” data provided, create a Linear Regression Model for different locations data to predict the Wind Speed in different locations

2) Histogram: 
Create the Frequency Distribution Plot to examine the GMAT scores. Explain your interpretation is the chart. Use mba.csv data source.

3) Forecasting: Use Global Superstore to create a visualization predicting the future trends of Sales over the next 6 Quarters for different Categories.

4) Clustering: Using Fisher’s Iris dataset given, create a scatter matrix. Create 3 clusters on each plot in the scatter matrix using the K-Means algorithm.

5) Trend Model: Express Profit as a function of Sales for different Order Id’s. What is the equation of the Linear Trend Model.

6) Parameters: Show the next level of detail in a hierarchy for just a selected attribute.

7) Parameters: Give the user the option to select which Dimension to be used in the view (represent data at selected dimension level).

8) Parameters: Create a chart to display the Top N and Bottom N profitable Customers of Superstore in a single view.

9) Parameters: Create a Parameter to retrieve a ‘Selection’s Average Sales’ value. Display the average on the worksheet title. 

10) Parameters: For the above question, display the Selection’s Average Sales using a Reference Line.

#module 8
1) Create a Symbol Map showing the Sales of Super store. Display the Population Data of US as the Data Layer.

2) Divide United States into 3 different territories using the selection tools and Visual Grouping concept. Display the profit of each territory as a Label. Hint: Group using (Country,State)

3) Create a Map of United States showing different states on the WMS map. Link to the WMS Map: http://ows.terrestris.de/osm/service

4) Using the “Bank of China Branches.csv” file given, plot all the branches of “Bank of China” on a world Map. Hint: Use Custom Geo coding to import the new geographic role for “Branch”. CSV file with the Latitude and Longitude information for all the branches is given (Bank of China Branches - Custom Geocoding.csv)

5) Use the “hong_kong_mtr.png” image and generate coordinates for all the stations on the “Island Line” and “Kwun Tong Line”. Hongkong MTR.xlsx data source is provided.

#module 9
Create an interactive dashboard to display the Sales of Superstore. Use Filter, Highlight and URL Actions.

Steps to be performed:
a)	Create a Map showing the “Sales” of all the states present in Sample Superstore Data Source.
b)	Colour the states by the region they belong to.
c)	Create a detailed Text table showing all the measure values.
d)	Create a Pie Chart showing the Sales of Super store across different regions.
e)	Create a URL action to show the Wiki page of the states that are selected (Run the Action from “Menu” option).
f)	Use highlight and filter actions to analyse the sales.
g)	Display the Top 5 Customers for each state on the”Tooltip” when the state mark is selected.

#module 10
1) Numeric Calculation: What is the profit ratio of $22,000 bin of Sales in year 2012?

2) String Calculation: The “Names.xlsx” input data source provided contains the names of a few customers, however, the names are not in proper case. Using string calculations bring all the names to “Proper Case”.

3) Date Calculation: In the Names.xlsx data source, the “Residing Since” column contains the date since the customer has been residing in the given city. However, Tableau could not interpret the Date field properly. It is being treated as a “Numeric” field as shown in the picture below. Using the Date functions, convert “Residing Since” into a Date field.

4) Date Calculation: The Shipping Manager of Superstore needs a report of the “Average number of days” taken to ship an order placed, for different states by different ship modes.

5) Logic Calculation (CASE-WHEN-THEN-END): The “Products.xls” data source contains the product id’s of different products sold by superstore and their Sales information. The customers are not able to identify the type of the product due to the codes used. Create a report with the list of product id’s and mention the full form of the codes used.
Codes are as follows
AP - Appliances
AR - Art
BI - Binders
EN - Envelopes
PA - Paper
ST - Storage

6) Quick Table Calculations: Create a view to display the Sales, Running Sum of Sales and Moving Average of Sales of Superstore (use 45 days before and 45 days after including the current day as the interval for moving average) for different categories.

#module11
1) LOD Calculations:
a)	In business, cohort analysis is most often used to study customer retention. A cohort is a group of customers or subjects that have a common characteristic. 
Determine the Cohorts by the date at which customer made their first transaction at superstore (The minimum order date per customer will give the first purchase date). 
Create a chart showing the Sales of Super store over different years and identify whether longer tenured customers make a larger contribution to sales? 

Hint: Since the data in the view is displayed by year (not by customer), we must use an LOD Expression to fix the minimum order date per customer.
b)Display the number of customers in each year from different Cohorts

2)LOD for Percent of Total (Absolute): This is the Sales of Superstore for different Categories
Create a view to Display the Sales as Percentage. The Percentage value should be the Absolute value (not relative), it should not change even when the categories in the chart are filtered out.

3) LOD Sales corresponding to Maximum Profit: Create a chart to display the Maximum profit from all the customers. Show the corresponding Sales value.

#module12
1) Pareto Chart: Create a Pareto Chart to show what percentage of products (use product id) sold by Superstore contribute to 80% of its sales.

2) Waterfall Chart: With the help of Waterfall chart show how sales start, end and get incremented over a period of time. 











