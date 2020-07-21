# Ford Gobike Data exploration
## by Ibodullaev Fazliddin


## Dataset

> This project is divided into two major parts. In the first part, you will conduct an exploratory data analysis on a dataset Ford GoBike System Data. I will use Python data science and data visualization libraries to explore the dataset’s variables and understand the data’s structure, oddities, patterns and relationships. The analysis in this part should be structured, going from simple univariate relationships up through multivariate relationships.

> In the second part, I will take my main findings from my exploration and convey them to others through an explanatory analysis. To this end, I will create a slide deck that leverages polished, explanatory visualizations to communicate my results.

> My dateset contains 176799 entries. There are 14 columns which are duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude, end_station_longitude, bike_id, user_type, rental_access_method. Data types of columns are 4 objects, 2 datetimes, 2 integers and 6 floats.

> For clean dataset: changing the data type of start_time, end_time to Datetime.

## Summary of Findings

> It is interesting that amount of values is very large and it is with 600-700 seconds peak. After the peak it starts decreasing rapidly.
> All my plots as you can see, is in big format. Thus we can see the plot deeper. I have changed the data type of start_time, end_time to Datetime. Because it is good for plotting and proper structure of data.
> Start and end stations do not much determine the trip duration which is in seconds. Start and end stations of some are higher. In consequence, we can view the longer trips related to start station and end station.
> Apparently, the customers are more willing to take long trips than subscribers. Besides, if you look at the rental accessing method deeper, you will realize that people who use app takes long trips than clipper.
> Customers use app more often than clipper. Subscribers use app and clipper very often and trip duration is also same.
> Interestingly subscribers take bikes not quite often. Whereas customers take bikes very often and trip duration is also very long.


## Key Insights for Presentation
I will start with plotting three histograms:
> Distribution of Trip Durations with start and end stations
After that I will introduce the box plot:
> Distribution of User type
Afterwards I will go with box plot again. Because my plot is related to categorical and quantitative data.
> Distribution of Renting access method
And then I will introduce you multivariate exploration with cat plot. 
> Trip duration per User type and Rental access method
Last but not least, I plot two separate scatter plots since I can clearly see the plot. 
> Trip Duration, user type, and bike_id