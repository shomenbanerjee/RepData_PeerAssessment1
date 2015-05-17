---
# PA1_Template (Reproducible Research, Week 2)

### Author: "SB"
### date: "Tuesday, May 12, 2015"

The first step is to download the .zip file locally into the working directory and load it into a data frame.

- Install 'downloader' package

- download .zip file locally, and unzip it

- read.csv into a dataframe



____________________________________________________________________________________________________

### Let us now sum the steps by each day and create a histogram

![plot of chunk process Data part1](figure/process Data part1-1.png) 

### Calculate the Mean and Median steps taken per day


Mean: 1.0766189 &times; 10<sup>4</sup>

Median: 10765

_____________________________________________________________________________________________________

### Make a plot for Average Daily Pattern of steps taken each day

![plot of chunk averageDaily Pattern](figure/averageDaily Pattern-1.png) 


Highest steps are in 835 Interval

_____________________________________________________________________________________________________

### Take a stock of missing values in the data set



There are a total of 2304 elements that have missing values in the data set


Lets consider filling up the missing values with the mean for that interval

![plot of chunk fillMissingValues](figure/fillMissingValues-1.png) 

Mean Old: 1.0766189 &times; 10<sup>4</sup> 

Mean New: 1.0766189 &times; 10<sup>4</sup>

Shift in Mean: 0

Median Old: 10765

Median New: 1.0766189 &times; 10<sup>4</sup>

Shift in Median: 1.1886792
___________________________________________________________________________________________________


![plot of chunk weekdays](figure/weekdays-1.png) 

As per data seems like there is more physical activity during the weekends, as compared to weekdays.
