# Project name

### Measuring a healthy life of young adults and teenagers 

Creating a survey about how students and young adults are having healthy life and collecting data on quantitative variables. I analyzed data using SAS tools see if there are any correlation between variables.

# Description & Data

I had a survey of students including middle school, high school, and college students, which the
age ranges from 18 to 30s, the healthy life by measuring how many days they eat breakfast,
drink alcohol, eat out, and eat instant food a week. I pick breakfast and eating out as my two
qualitative variables for my pertinent results. The median of eating breakfast a week was 3.0
with an IQR of 6.0 days. The median of eating out a week was 2.0 with an IQR of 5.0 days. I used
the median and IQR for my center and spread based on the box plot, which shows you the
outliers and correspondingly, the both of distribution doesn’t look normal as you can see the
plot as well. After the survey, I feel like I should have asked in different questions to have some
exclusive relationship so that I can make the more productive conclusion. During the survey,
everyone was cooperative in answering my questions and I felt I asked the appropriate and right
amount of questions.

# Survey Questions

• What age group do you fall in?</br>
• How many days do you eat your breakfast a week?</br>
• How many days do you drink alcohol a week?</br>
• How many days do you eat out your dinner a week?</br>
• How many days do you eat instant food a week?</br>

<img src = images/survey.png>

# Result

I had a survey of students including middle school, high school, and college students, which the
age ranges from 18 to 30s, the healthy life by measuring how many days they eat breakfast,
drink alcohol, eat out, and eat instant food a week. I pick days of eating out and days of eating
instant food to see relationship instead of eating breakfast and eating out sample in project 1.
The correlation coefficient is 0.29870. It means the correlation between eating out and eating
instant food is 0.29870. That is, there is some positive correlation eating out and eating instant
food. Using PROC GPLOT, we can clearly see, again, there is some positive correlation between
eating out and eating instant food.
The following table is ANOVA result.

<p align="center">
  <img src = images/anova.png>
<p>
  
 The p-value indicated from the ANOVA table is 0.0725, which is not quite close to 0.
Furthermore, the F value is not large enough to reject the null hypothesis. Thus, I would fail to
reject the null hypothesis and conclude that there is not at least one of the coefficients of
indicator variables is different from zero.
The equation is: Eating out : 2.44487*eating instant food + 0.45881
The p-value on eating instant food (independent variable) differences is 0.0725 which is larger
than p level (0.05). This p-value indicates that the variable eating instant food is not statistically
significant. Since we have small p-value, we fail to reject the null hypothesis that the coefficient
equals zero.
The normal probability plot clearly shows that there is an outlier, so we do not consider this as
a good model. The residuals for eating out(dependent variable) also shows the outlier. Thus, we
conclude that the residuals are not independent and normally distributed as the residuals have
outliers.
My sample has a moderately positive correlation between two variables. The regression
equation itself looks reliable, but the overall sample is not good because of the outliers on
residuals and p value which is larger than alpha level.

# Output
<p align="center">
  <img src = images/result1.png>
  <img src = images/result2.png>
  <img src = images/result3.png>
  <img src = images/result4.png>
<p>
