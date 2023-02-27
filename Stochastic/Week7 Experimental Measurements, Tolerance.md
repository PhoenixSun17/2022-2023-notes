## Tolerance Interval
Tolerance interval, derived from a sample of N measurements, is a range within which we are C% confident that a certain percentage of the parent population will fall

The interval that would contain Y% of the parent population
with W% confidence is denoted as:

X mean +- Ctw(y) * S(x)
Page 8



## Perdiction Interval
derived from a sample of N measurements, is a range within which we are C% confident that the next K measurements will fall.

The interval around the mean of N measurements, which would contain K
additional measurements is denoted as:

X mean +- Cp,k(N) * S(x)


## Statistical Rejection of Outliers
When dealing with experimental data we often find some data points that don’t “quite fit” the general
trend…
• In experimental environments were data points are scarce, such “outliers” can ruin a small sample.
• Intuitively, many people will disregard such points after a visual inspection of the results.
• However, that is wrong!
• One method that is widely accepted for statistical rejection of outliers is known as Chauvenet’s criterion
which defines an acceptable scatter around the mean value from a given sample of N measurements from the
same parent population.



### Chauvenet’s Criterion for Rejection
Statement: All experimentally measured points that fall within a certain band around the mean of a sample should
be retained. That band is defined by the probability:

Let’s consider a sample of 6 measurements taken at a “constant” test condition.
• According to Chauvenet’s criterion, all points that fall within a probability band of (1 - 1/12) around the mean
must be retained.
• NOTE: Chauvenet’s criterion defines the band using Gaussian probabilities and not the t-distribution, even for
small values of N!
• So from Table A.1, a probability of (1-1/12 = 0.917) corresponds to a non-dimensional deviation (τ) equal to 1.73