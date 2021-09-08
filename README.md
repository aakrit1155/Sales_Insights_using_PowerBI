# Sales_Insights_using_PowerBI
#A small Data Analytics project using PowerBI

In this mini data analytics project, I have used the PowerBI application from Microsoft.
PowerBI is a free data analytics tool, and it is very popular worldwide.

For this mini project, I took a sql dump file from the internet.
I replicated the database in my localhost MYSQL Server.

Then I explored the data to find any redundancies, misssing data, irrevelant data, and inappropiate data.
After running SQL commands, I encountered various problems with the data:
<ul>
<li>
Some of the rows were repeated.
</li>
<li>
Some rows had values such as -1 under "quantities of items sold" which is obviously an error.
</li>
<li>
Some rows had price in dollars while majority had price in INR.
</li>
</ul>

The next step involved data cleaning.
For this, I imported the data in PowerBI from the database from the localhost MYSQL server.

With the data in the PowerBI, we can see how the tables are related, and in one instance, 
there was no established relations between tables due to a naming error, so I established
a relation manually.

Then I went into the Power Query tool, and applied data filters, and transforms. I addressed all the issues
related to the data that I mentioned above.

Now that the data is cleaned, I saved the modifications and returned to the PowerBI dashboard.
It is now time to build the interactive visualizations in PowerBI dashboard.

I added horizontal bar graphs, line charts, plain cards, and slicers to create important visualizations.
Building the visualizations is all about communicating well with the heads and investors. So I made the 
charts colorful and added appropriate charts which gave insights to the business.

