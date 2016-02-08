# Reproducible Research: Peer Assessment 1


## Loading and preprocessing the data

```r
activity = read.csv("activity.csv")
```

## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values
Total number of Missing Values:

```r
length(which(is.na(activity$steps)))
```

```
## [1] 2304
```


## Are there differences in activity patterns between weekdays and weekends?
