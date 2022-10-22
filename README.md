# Statistics for Data Science

## Probability
Probability is the probability of an event. Whether it's an event that will happen or not and how big it is that the event has the chance to happen. <br>
```
P(A) = n(A) / n(S)
```
## Range<br>
To return a range of values along an axis can used statistical function that called <b>numpy.ptp()</b>, "ptp" stands for <b>peak to peak</b>. The range can be calculated using:<br>
```
var = np.ptp(statement)
```
or
```
range = maximum_value - minimum_value
```
## Variance
The variance() method calculates the variance from a sample of data (from a population). A large variance indicates that the data is spread out. A small variance indicates that the data is clustered closely around the mean. <br>
```
var = statistics.variance(statement)
```

## Standard deviation
Standard deviation is a helpful way to measure how <b>spread out</b> values in a data set are. A small standard deviation means that most of the numbers are
close to the mean (average) value. However, a large standard deviation means that the values are further away from the mean.
```
var = statistics.stdev(statement)
```
## Quantile
Quantile can be used as a mapping for arrays. As of now, you cannot use Quantile as a mapping from numpy. But by using its similar library Scipy, you can compute empirical quantiles of an array.
```
var = np.quantile(statement, [0, 0.25, 0.50, 0.75, 1])
```
## Skewness
Skewness is a measure of asymmetry of the probability distribution about its mean and helps describe the shape of the probability distribution. <br>
- Positive : observed when the distribution has a thicker right tail and mode < median < mean.
- Negative : observed when the distribution has a thicker left tail and mode > median > mean.
- Zero (or nearly zero) : observed when the distribution is symmetric about its mean and approximately mode = median = mean
 
## Correlation
One way to quantify the relationship between two variables is to use the Pearson correlation coefficient, which is a measure of the linear association between two variables. It always takes on a value between -1 and 1 where :
- 1 indicates a perfectly negative linear correlation between two variables
- 0 indicates no linear correlation between two variables
- 1 indicates a perfectly positive linear correlation between two variables
The further away the correlation coefficient is from zero, the stronger the relationship between the two variables.

## Handling outlier
When exploring data, the outliers are the extreme values within the dataset. That means the outlier data points vary greatly from the expected values—either being much larger or significantly smaller.

## Handling missing value
Missing Data can occur when no information is provided for one or more items or for a whole unit. Missing Data is a very big problem in a real-life scenarios. Missing Data can also refer to as NA(Not Available) values in pandas.

## Inferential Statistics - Confidence Intervals
The confidence interval is the range of values that you expect your estimate to fall between a certain percentage of the time if you run your experiment again or re-sample the population in the same way.

## Inferential Statistics - Hypothesis Testing
Hypothesis testing is an act in statistics whereby an analyst tests an assumption regarding a population parameter. The methodology employed by the analyst depends on the nature of the data used and the reason for the analysis.

Hypothesis testing is used to assess the plausibility of a hypothesis by using sample data. Such data may come from a larger population, or from a data-generating process.
