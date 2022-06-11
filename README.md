# ETL-Project

Our goal of this project was to look at the relationship between minimum wage and hate crimes frequency using the ETL process. By using Kaggle we were able to find two CSV files containing this information for each US state over a number of years. 

The first step in this project was to extract the data. As mentioned, we were able to find these files on Kaggle. We downloaded the files then uploaded them to our Jupyter Notebook. From here, we started on the Transform process; we cleaned both sheets by selecting which columns we'd like to keep, then grouping the data by state by year. Since the hate crimes dataframe included information between 1991 to 2018, we needed to make sure the minimum wage dataframe did the same. 

Once our two dataframes were cleaned and organized, we were able to begin the loading process. We chose to use Postgres to load in our data to create a merged table.

For more information, please see the ETL Technical Report file. 
