# Statistics

## Summation Notation

- **"Summation notation is shorthand for the addition of many terms."**
- Eg: Avergae can be given by the equation: $\bar{x} = \frac{1}{n} \sum_{i=1}^{n} x_i$

## Using Bar graphs and Histograms to summarize data

- Data can either be summarized visually through bar graphs and histograms or through summary statistics such as mean, mode, median and standard deviation.
- In order to plot the bar graph, data needs to be present in categories. For continuous variables, the data is categorized, also known as bin ranges, and then a frequency table is created which is then used for plotting.

## Measures of Central Tendency

- The section covers three central tendencies: mean, mode and median.
- **"The mean is simply the average of the n numbers. It is usually written as x-bar and expressed as $\bar{x} = \frac{1}{n} \sum_{i=1}^{n} x_i$."**
- **"The median is the halfway mark between the lower and upper extremes of the list of numbers in a data set. To find the median, first order the numbers from smallest to largest. If n is odd, the median is the (n + 1)/2 smallest number. If n is even, the median is the average of the n/2 smallest number and (n + 2)/2 smallest numbers."**
- **"The mode is the most frequently occurring number in a data set. A data set can have more than one mode. If no number occurs more than once in a data set, the data set has no mode."**

## Skewness and Measures of Central Tendency

- **"The mode is rarely used as a measure of central location. In most situations, however, we use the mean or median as a measure of central location for a data set. In general, we use the mean as a measure of central location unless extreme values greatly distort the mean."**
- **"The mode is rarely used as a measure of central location. If a shoe store could only stock one size, it would probably stock the modal shoe size. In most situations, however, we use the mean or median as a measure of central location for a data set. In general, we use the mean as a measure of central location unless extreme values greatly distort the mean."**
- A symmetric data's mean, mode and median are equal to a single value.
- **"A data set exhibits positive skewness (or is "skewed right") if its histogram has a single peak and the values of the data extend much farther to the right than to the left of the peak."**
- **"A data set exhibits negative skewness (or is "skewed left") if its histogram has a single peak and the values of the data extend much farther to the left than to the right of the peak."**
- Mean is used as a measure of central tendency when the data is not distorted by some extreme values. In case of distortion, median is used as a measure of central tendency.
- If SKEW > +1, the data are positively skewed and the median is the better measure of central tendency.
- If SKEW < -1, the data are negatively skewed and the median is again the better measure of central tendency.
- If SKEW is between -1 and +1, the data are relatively symmetric and the mean is the better measure of central tendency.
- **"For positively skewed data sets, the mean is greater than the median. For negatively skewed data sets, the mean is less than the median. For relatively symmetric data sets, the mean and median are usually very close in value."**

## Measures of Variability

- **"Given a set of data the sample variance is the average squared deviation of the data points from the sample mean. The sample variance measures the spread of a data set about its mean."**
- Mathematically, sample variance can be can be expresses as, $S^2 = \frac{1}{n-1} \sum_{i=1}^{n} (x_i - \bar{x})^2$.
- **"If you divide by n instead of n - 1, the sample variance is the average squared deviation of each data point from the average of the data."**
- The dataset in which all the values are same has 0 sample variance.
- **"Sample standard deviation (S) - A measure of a data set's spread about its mean. It is computed as the square root of the data set's sample variance."**
- **"Sample deviation is often used as a measure of spread or dispersion in a data set because the sample standard deviation has the same units as the data."**
- Standard deviation is calculated by taking the square root of the variance.

## The rule of thumb and Outliers

- **"Outlier - A point is a data set that seems "out of the ordinary." Most often a point is considered an outlier if it is more than 2 standard deviations away from the mean of the data set."**
- **"Any data point that is more than 2S from the mean is designated an unusual observation or outlier."**

## Covariance and Correlation

- Relationship between two datasets is measured by covariance and correlation.
- **"Covariance - A measure of linear association between two data sets that depends on the units in which each data set is measured."**
- **"Correlation - A unit free measure of linear association between two data sets."**
- The covariance between datasets $X$ and $Y$ is given by, $Covariance(X,Y) = \frac{\sum_{i=1}^{n} (x_i - \bar{x}) (y_i - \bar{y})}{n-1}$.
- If $X$ and $Y$ covary in the same direction, the covariance is positive and if they covary in the opposite direction then it is negative.
- **"In summary, a positive covariance indicates that X and Y tend to go up or down together whereas a negative covariance indicates that X and Y tend to move in opposite directions (relative to their averages)."**
- **"Note that covariance only measures the strength of a linear relationship and is not useful for detecting nonlinear relationships between variables. Therefore, covariance is a measure of linear association between two variables."**
- **"The Pearson correlation (usually denoted by r) is a unit-free measure of the degree of linear association between two data sets X and Y."**
- Pearson correlation coefficient $r$ can be given by, $r = Correlation(X, Y) = \frac{Covariance(X, Y)}{S_x S_y}$.
- Correlation coefficient is a unit-free quantity.
- Values of r near -1 indicate a strong negative linear relationship between X and Y. When X is larger than average, Y is almost always smaller than average; when X is smaller than average, Y is almost always larger than average.
- Values of r near -.5 indicate a moderate negative linear relationship between X and Y. When X is larger than average, Y tends to be smaller than average; when X is smaller than average, Y tends to be larger than average.
- Values of r near 0 indicate a weak linear relationship between X and Y. When X is larger than average, Y has little or no tendency to be larger or smaller than average. Similarly, when X is smaller than average there Y has little or no tendency to be larger or smaller than average.
- Values of r near +.5 indicate a moderate positive linear relationship between X and Y. When X is larger than average, Y tends to be larger than average; when X is smaller than average, Y tends to be smaller than average.
- Values of r near +1 indicate a strong positive linear relationship between X and Y. When X is larger than average, Y is almost always larger than average; when X is smaller than average, Y is almost always smaller than average.
- For calculating population covariance, replace $n-1$ in the denominator with $n$.
- Correlation does not imply causation. 