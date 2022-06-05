# EXPLORATORY DATA ANALYSIS

It is a critical process of performing initial investigation data to discover patterns, to spot anomalies, to test hypotheses and check assumptions with the help of statistics and graphical representation. It converts raw data to useful data.

Each Column is treated as variables and
earch row is treated as data points/ observations.

For Statistician column as independent variables, mathermatician data point as vectors

vector: n-dim numerica; array


## UNIVARIATE ANALYSIS

Univariate analysis is the technique of comparing and analyzing the dependency of a single predictor and a response variable. The prefix "uni" means one, emphasizing the fact that the analysis only accounts for one variable's effect on a dependent variable. Univariate Analysis is thought to be one of the simplest forms of data analysis as it doesn't deal with causes or relationships, like a regression would. Primarily, Univariate Analysis simply takes data and provides a summary and associated patterns.
You have several options for describing data with univariate data:
1. Frequency Distribution Tables.
2. Bar Charts.
3. Histograms.
4. Frequency Polygons.
5. Pie Charts.


## PROBABLITIY DENSITY FUNCTION

The integral of the probability density function over a particular interval gives you the probability that a random variable takes a value in this interval. This probability is thus given by the area under the curve in this interval.
A function that defines the relationship between a random variable and its probability, such that you can find the probability of the variable using the function, is called a Probability Density Function (PDF) in statistics.

The different types of variables. They are mainly of two types:

### 1. Discrete Variable

A variable that can only take on a certain finite value within a specific range is called a discrete variable. It usually separates the values by a finite interval, e.g., a sum of two dice. On rolling two dice and adding up the resulting outcome, the result can only belong to a set of numbers not exceeding 12 (as the maximum result of a dice throw is 6). The values are also definite.

### 2. Continuous Variable

A continuous random variable can take on infinite different values within a range of values, e.g., amount of rainfall occurring in a month. The rain observed can be 1.7cm, but the exact value is not known. It can, in actuality, be 1.701, 1.7687, etc. As such, you can only define the range of values it falls into. Within this value, it can take on infinite different values.

Now, consider a continuous random variable x, which has a probability density function, that defines the range of probabilities taken by this function as f(x). After plotting the pdf, you get a graph as shown below:                     

![alt text](https://www.simplilearn.com/ice9/free_resources_article_thumb/Probability_Density_Function/Probability_Density_Function_2.png)

In the above graph, you get a bell-shaped curve after plotting the function against the variable. The blue curve shows this. Now consider the probability of a point b. To find it, you need to find the area under the curve to the left of b. This is represented by P(b). To find the probability of a variable falling between points a and b, you need to find the area of the curve between a and b. As the probability cannot be more than P(b) and less than P(a), you can represent it as: 

```P(a) <= X <= P(b).```


## COMULATIVE DENSITY FUNCTION

The cumulative distribution function is used to describe the probability distribution of random variables. It can be used to describe the probability for a discrete, continuous or mixed variable. It is obtained by summing up the probability density function and getting the cumulative probability for a random variable.

The Probability Density Function is a function that gives us the probability distribution of a random variable for any value of it. To get the probability distribution at a point, you only have to solve the probability density function for that point. 

The cumulative distribution function of a random variable to be calculated at a point x is represented as Fx(X). It is the probability that the random variable X will take a value less than or equal to x.


```Differentiate CDF = PDF```

```Integration PDF = CDF```


## Mean

In statistics, the mean is one of the measures of central tendency. Mean is nothing but the average of the given set of values. It denotes the equal distribution of values for a given data set.
If there is an outlier in the data then this will corrupt the mean.


## Variance

According to layman’s words, the variance is a measure of how far a set of data are dispersed out from their mean or average value. It is denoted as ‘σ2’.

### Properties of Variance

It is always non-negative since each term in the variance sum is squared and therefore the result is either positive or zero.
Variance always has squared units. For example, the variance of a set of weights estimated in kilograms will be given in kg squared. Since the population variance is squared, we cannot compare it directly with the mean or the data themselves.


## Standard Deviation

The spread of statistical data is measured by the standard deviation. Distribution measures the deviation of data from its mean or average position. The degree of dispersion is computed by the method of estimating the deviation of data points. It is denoted by the symbol, ‘σ’.

![alt text](https://wumbo.net/formula/sample-standard-deviation/population-standard-deviation-area-650-350.svg)

### Properties of Standard Deviation

It describes the square root of the mean of the squares of all values in a data set and is also called the root-mean-square deviation.
The smallest value of the standard deviation is 0 since it cannot be negative.
When the data values of a group are similar, then the standard deviation will be very low or close to zero. But when the data values vary with each other, then the standard variation is high or far from zero.

![alt text](https://cdn1.byjus.com/wp-content/uploads/2021/03/variance-and-sd-formula.png)

## Median


## Mode


## CENTRAL TENDENCY 

The central tendency measure is defined as the number used to represent the center or middle of a set of data values. The three commonly used measures of central tendency are the mean, median, and mode. A statistic that tells us how the data values are dispersed or spread out is called the measure of dispersion.

![alt text](https://cdn1.byjus.com/wp-content/uploads/2020/01/Relation-Between-Mean-Median-and-Mode-1.png)