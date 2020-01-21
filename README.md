# Inferential Statistics on Human temperature

Inferential statistics means taking a random sample from a population and then perform inferences which then gives a description to the population as a whole.

Before performing hypothesis tests on this data, first have to check if the distribution is normally distributed and in this case either a box plot which shows their mean of each category or Shapiro-Wilk test is used. 
After implementing these two, temperature was concluded to be normally distributed from the box plot as the mean and medians are equal.

## Boostrap Hypothesis test 

With boostrap hypothesis test, null and alternative hypothesis are defined. In this case the null test is mean of temperature is 98.6 and the alternative hypothesis is the mean is <> 98.6.
Replicates of the data are made and then boostrap replicate mean is calculated from which a p value is finally calculated which is used to determine which hypothesis should be rejected. In this case, since p value is greater then 0.5, the alternative hypothesis is rejected. This therefore confirms that the temperature mean is 98.6.

## Frequentiest Statistical testing

There are two main types of tests here either the Z test or the T test and their usage depends on the sample size. Z test is most suitable for sample size of at most 100 samples and T test goes for sample size of at most 30 samples.

Z score being the most common helps calculate the probability of a score occuring within the normal distribution. For example values gotten from the left z table after the computation shows the probabilty of having a mean lowerthan the sample mean.

## Importance of Inferential Statistics

- From the sample population taken, inferential statistics helps know the probability of having a higher or lower mean than the population mean.
- Another observation is that mean of female temperature is slightly greater than that for male and there is a direct relationship between temperature and heart rate. This therefore means more females are likely to have high heart rates unlike the male.
- Most women have high body temperatures and some extending to abnormally higher temperatures outliering at the right section of the graph
- To conclude, the men have few outliers lower than the mean temperature whereas women have outliers higher than the mean temperature which is the main reason why they mean temperature for women is slightly higher than for men.
