# SQLALCHEMY

**Step 1 - Climate Analysis and Exploration**

Start, BY Python and SQLAlchemy to do climate analysis and data exploration of your climate database. 

The following analysis should be completed using SQLAlchemy ORM queries, Pandas, and Matplotlib.

By providing starter notebook and hawaii.sqlite files to finish the climate analysis and data exploration.

Use SQLAlchemy create_engine to attach to sqlite database.

Use SQLAlchemy automap_base() to consider your tables into classes and save a reference to those classes called Station and Measurement.


Note: Mindful to close out your session at the end

**Precipitation Analysis**

Get back the last 12 months of precipitation data by querying the 12 preceding months of data. Note you don't miss the date as a variable to the query.

Select only the date and prcp values.

Fill up  the query results into a Pandas DataFrame and set the index to the date column.

Classify the DataFrame values by date.

Plot the results using the DataFrame plot method.

By using Pandas to print the summary statistics for the precipitation data.

**Station Analysis**

Plan a query to calculate the total number of stations in the dataset.

Plan a query to find the most active stations

List the stations by observing counts in descending order.

Which station id has the highest number of observations?

Using the most active station id, calculate the lowest, highest, and average temperature.

Plan a query to retrieve the last 12 months of temperature observation data (TOBS).

Filter by the station with the highest number of observations.

Query the last 12 months of temperature observation data for this station.

Plot the results as a histogram with bins=12.

Finish the session.

**Step 2 - Climate**

After completion of initial analysis, Plan a Flask API based on the queries that has just developed. Use Flask to create your routes.




