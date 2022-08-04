# surfs_up

# Overview
The purpose is to analyze temperature and precipitation data to determine if the surf and ice cream shop business is sustainable year round at Oahu. 

1. Temperature summary statistics for the month of June.
2. Temperature summary statistics for the month of December.
3. Precipitation summary statistics for the months of June and December.

## Resources
- Data Source: hawaii.sqlite
- Software: Jupyter Notebook 4, Python 3.7.13, Visual Studio Code 1.68.1

## Results

### Temperature summary statistics

The link to the queries to create temperature summary statistics for the months of June and December.<br>
[Temperature summary statistics](/surfsup_challenge.ipynb)<br>

#### DataFrame temperature summary statistics for June

<figure>
    <figcaption>Temperature summary statistics for June</figcaption>
    <img src="/Resources/temperature_summary_statistics_june.png" width=1186 height=auto
         alt="Temperature summary statistics for June">
</figure> <br>

#### DataFrame temperature summary statistics for December

<figure>
    <figcaption>Temperature summary statistics for December</figcaption>
    <img src="/Resources/temperature_summary_statistics_december.png" width=1257 height=auto
         alt="Temperature summary statistics for December">
</figure> <br>

### Precipitation summary statistics

The link to the additional queries to create precipitation summary statistics for the months of June and December.<br>
[Precipitation summary statistics](/surfsup_challenge_additional_queries.ipynb)<br>

<figure>
    <figcaption>Query and precipitation summary statistics for June</figcaption>
    <img src="/Resources/precipitation_summary_statistics_query_june.png" width=1077 height=auto
         alt="Query and precipitation summary statistics for June">
</figure> <br>

<figure>
    <figcaption>Query and precipication summary statistics for December</figcaption>
    <img src="/Resources/precipitation_summary_statistics_query_december.png" width=1080 height=auto
         alt="Query and precipication summary statistics for December">
</figure> <br>

## Summary 

1. Average temperature in December is ~3.9 degree F lowered than in June.
2. Minimum temperature in December is ~8 degree F lowered than in June.
3. Maximum temperature in December is ~2 degree F lowered than in June.
4. IQR of temperature statistics for December is ~5 degree F and for June is ~4 degree F.
5. Standar deviation of temperature statistics for December is ~3.75 degree F and for June is ~3.25 degree F.
6. Average precipitation in December is 0.22 inches and in June is 0.14 inches.
7. Maximum precipitation in December is 6.42 inches and in June is 4.43 inches.
8. Overall weather in June and December is similar in terms of temperature and precipitation.