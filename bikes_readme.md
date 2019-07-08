# FordGo Bike System
## by Maviane Ribeiro


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The period chosen for analysis was the last year of the system use, that is between May 2018 and May 2019. The datasets were by month. So, it was necessary concatenate the months wanted into just one data frame.



## Summary of Findings

> After cleaning, the variables seem to be well distributed.
About gender, it was found three of them: male, female and others.
About the type of user, we found two: customer and subscriber.
Related to the birth year of the user, there is a range of 71 years, unimodal and left skewed. People younger than 39 years are the majority of users. But a decrease can be seen from 24 years, followed by a steep decline from 19 years old. About unusual findings, there are some elderly users with birth years as 1930, 1940. In a society with physically active elderly, it's hard to say if a year as 1930 is an invalid data. But, it seems to be an outlier. To provide information about the user's generation, it was necessary to bin the member_birth_year in order to create a new column generations.
In terms of user's features, a prevalence of gender is male, with a birth year between 1985 and 1995 (Millennials generation), and was found more subscribers than customers.
Looking at the duration of the rides in minutes, the distributions showed to be largely wide, unimodal and right-skewed. The majority of the rides are between 1 and 20 minutes. Outliers present.<br>   
> Looking at the distribution of the features of interest through the years, it's possible to see that all the categories of gender and user type seem to present a wide increase from 2017 to 2018. From the data that we have in 2019 (until May), it appears that we'll have an increase from 2018 to 2019 too. About the feature generation, it was observed the same pattern as in the others categorical variables above, except for the Silent and New Silent generation. While the Silent generation seems has tried the system in 2018, it hasn't appeared in 2019 yet. Also, the New Silent Generation doesn't appear to have significant presence in the chart.
About the relationship between the features of the user and the duration of the rides, we found that gender doesn't seem to make a huge difference in the duration of the rides. Their medians don't vary much. It was possible to see that female's rides, followed by other's, tend to be a little bit longer than the male's. That is about 2 minutes in average. Although the male takes more rides as we saw in the univariate plots. Related to the user type, we could see that the median of the duration of the rides is higher for casual customers than for the subscribers. That is about 2 minutes in average. But the last ones take more rides, as we've seen before. Observing differences in ride's duration associated to generation, we could see that just the New Silent generation, the youngest one, showed differences in duration. They tend to take longer rides, around double than the others (12 minutes+), showing a higher variance. But they don't show a strong presence in quantity between the users.
The quantitative variables that we could explore were the duration of the rides and member birth year. Although we see a concentration of rides between 1-10 minutes for members born between 1985-1995, we couldn't find a correlation between those two variables.
What is more important to the company, more rides or longer ones? Maybe it should be interesting to analyze the profit related to the duration and frequency of the rides.<br>   
> Looking at the relationship between member_birth_year, duration_min, and gender, we can see that there is a lot of overlap in all three genders, with male and short rides dominating the distribution. But it's possible to observe that the description other for gender starts to appear from the 1950's and it seems to be more concentrated from the 1980's. There is an increase of longer rides for female from the 1980's. There are a few older female with shorter rides. Male and members born between 1980 and 1995 are the predominance in short rides. Related to user type, it seems that longer rides are characteristic of older customers, while shorter rides are characteristic of younger subscribers. Customers almost don't appear in short rides (<= 10 min) in all spectrum of years. But, when young, they're a considerable presence in long rides (>= 30 min). Analyzing the variation of the ride's duration through the years, it's possible to see variations happening. For female, it there has been a decrease. For male, just a slight increase in 2019. While for other there is an increase comparing to 2018. Related to the type of the user, we can see that for the customers there is a decrease in 2019 related to the past years. What we don't observe with the subscribers who have maintained their duration of the rides stable through the years analyzed. About the generations, we observe that Millennials, Generation X and Baby Boomers seem to keep their ride's duration stable. The Silent generation shows a decrease in the duration, while the New Silent generation shows data just for 2019.


## Key Insights for Presentation

> Who Are Our Users?<br> Male, subscribers and Millennials.
> Are They Changing Through the Years?<br> Not much.
> Do these characteristics impact the duration of the rides? Some differences seen in user types and generations.
