# PyMaceuticals Matplotlib Analysis

### The Data
In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. Two CSV files were provided (mouse meta data and study results) which I merged using an outer merge and removed duplicates by identifying repeated IDs. 

### Use Pandas to disect the information
Using pandas, I was able to simply print information about the data including number of mice, the drug regimens, and summary statistics. 
![sumstats](https://user-images.githubusercontent.com/74504885/122320801-73795c80-cee8-11eb-87a0-fd8978951754.PNG)

### Use Matplotlib to create charts to display the data
Using matplotlib and pyplot, I was able to create charts to display information such as measurements taken per drug and male vs. female distribution.
![matplotdrugreg](https://user-images.githubusercontent.com/74504885/122321077-eb478700-cee8-11eb-9726-887f9cd399e7.PNG)
