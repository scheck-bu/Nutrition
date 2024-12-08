# Nutrition
This notebook provides a means to search for recipes, using an API, and show how much of the suggested daily nutrients it provides.

The project accesses three different data sources: a flat file, web page, and an Web API. The data from the three data sources are cleaned and transformed, using techniques such as removing records that contained missing values, splitting information in a single column into multiple columns, and removing unnecessary columns. From there, the data is imported from each of the data sources into three separate database tables, using SQLite, which shared a common attribute. The data was then queried from the tables, using SQL, to create visualizations.
