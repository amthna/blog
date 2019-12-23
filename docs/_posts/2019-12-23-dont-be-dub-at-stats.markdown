# Don't be dumb at stats

## Covariance

### Central tendencies

- mean is straight avg sum(set) / len(set)
- median is middle value: in python, sort list, find value in index length //2
	- if the list has even num elements, gotta midpoint plus midpoint-1 divided by 2.
- apparently we're not doing mode yet

### Quantile
- since mean is sensitive to outliers, can generalize with quantiles
- represents the value under which a certian percentile of data lies"
	- median is the value under which 50% lies

#### how to do in python
take the list of data, and a "p" value (the pth percentile)

### What is covariance?
> "Measures how two variables vary in tandem from their means."

<code>
def covariance (xs: List[float] yys: List[float]) -> float:
	assert len(xs) == len(ys), "xs and ys must have same number of elements"

	return dot(de_mean(xs), de_mean(ys)) / (len(xs) - 1)
<code>

> "dot sums up the products of corresponding pairs of elements."



Here's how to do covariance in python:

## Slime suck's...
A lot...
