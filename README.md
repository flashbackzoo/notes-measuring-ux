# Measuring UX

Notes on the book [Measuring the User Experience: Collecting, Analyzing, and Presenting Usability Metrics](http://www.amazon.com/Measuring-User-Experience-Interactive-Technologies/dp/0123735580).

## Contents

- [What are UX metrics?](#what-are-ux-metrics)
- [Variables in user testing](#variables-in-user-testing)
- [Data types](#data-types)
- [Descriptive statistics](#descriptive-statistics)

## What are UX metrics?

All UX metrics must reveal something about the interaction between the user and the product. Some aspect of:

- Effectiveness: Being able to complete a task.
- Effciency: The amount of effort required to complete a task.
- Satisfaction: The degree to which the user was happy with their experience while performing the task.

UX metrics must also be quantifiable - they have to be turned into a number or counted in some way.

## Variables in user testing

The are two types of variables in user testing, [independent](#independent) and [dependent](#dependent). When designing a UX study you should have a clear idea of what your variables will be.

### Independent

Things you manipulate, designs, user demographic.

### Dependent

Things you measure, success rates, number of errors, user satisfaction.

## Data types

All variables can be measured using one of four data types:

1. [Nominal](#nominal)
2. [Ordinal](#ordinal)
3. [Interval](#interval)
4. [Ratio](#ratio)

### Nominal

An unordered list of groups / categories. For example - Windows users, Mac users, and Linux users. Or users in different geographical locations. One group is not inherently better than another.

These are typically [independent variables](#independent) used to segment data by different groups.

Individual groups can contain [dependent variables](#dependent). Such as task success rate, number of users who clicked *A* vs *B*, errors encountered.

### Ordinal

An ordered list of groups or categories. For example - A user rating of excellent, good, fair, or poor. Or a user ranked selection of designs.

The most common way to analyze ordinal data is "40% of users rate the site a excellent, 30% rate it good, 20% rate it fair, and 10% rate it poor".

The relative distances between each point is not meaningful i.e. The design ranked 1st is not *twice as good* as the design ranked 2nd.

### Interval

A scale between two endpoints, where the distance between each endpoint is meaningful. For example - a scale from *cold* to *hot*. Also see System Usability Scale (SUS).

### Ratio

A scale between two endpoints, where the distance between each endpoint is meaningful, and one endpoint is absolute zero. Time is an example of how ratio data can be used in UX. Zero seconds left means a user has no time left to complete a task.

Ratio data can be used to say "on average, users complete the task twice as fast, using design 2".

## Descriptive statistics

Describes the data without saying anything about the larger population. Usually [measures of central tendency](#measures-of-central-tendency).

### Measures of central tendency

Central tendency is a single number representative of a set of numbers. Usually a [mean](#mean), [median](#median), or [mode](#mode).

#### Mean

Also know as the *average*. The mean is a sum of all values, divided by the number of values.

#### Median

The middle number if you put the data in order. If there is no middle number, it's half way between the two middle numbers. Sometimes the [mean](#mean) can be skewed by large outlying values, this is where the median can be useful.

#### Mode

The most commonly occuring value in the set. Mode is most useful when there is a limited set of values such as a subjective rating scale.

### Measures of variability

How much the data are spread across the range of values. For example "Do most users have a similar task completion time or is there a wide range". Usually measured by [range](#range), [variance](#variance), or [standard deviation](#standard-deviation).

#### Range

Distance between minimum and maximum values. Useful for decting outliers in a data set which may skew your [mean](#mean). Range is also useful for sanity checking a data set. For example - the range is supposed to be 1 - 5, are there any 7's?

#### Variance

Measures how spread out the data are relative to the [mean](#mean). A variance of zero indicates all values are identical. The greater then variance, the further away the data points are from the mean.

To work out the variance:

- Work out the mean
- For each data: subtract the mean and square the result (the *squared difference*)
- Work out the average of those squared differences

#### Standard deviation

The square root of the [variance](#variance). Standard deviation also measures how spread out the data are, but uses the same units as the [mean](#mean), so it's easier to interpret. For example if the mean is 10 seconds, the standard deviation will be *n* seconds.
