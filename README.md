# shopping-behavior
Summary:

Within this project, we were tasked with analyzing the shopping behavior of american consumers. We analyzed a given sample dataset in order to observe aggregate descriptive statistics and visualize the data to find insights on american shoppers. The goal of this project was to analyze and understand the seasonality of shoppers, which demographics purchase the most and which outreach strategies we can utilize to maximize purchases.

## Observations 
We were given a dataset with 3900 samples and 15 columns of simulated data. In the 1st step, I conducted exploratory data analysis in which I viewed the dataframe and used the describe method to view the tukey statistics on this dataframe. Then I conducted univariate analysis by generating visualizations to get an idea of any outliers and the distribution of the data. I also conducted bivariate analysis to generate visualizations and understand the relationships between multiple numeric variables in the dataset. Doing this allowed me to take note of any patterns and clusters within the data. I observed that the age column had a right skewed distribution, possibly pointing to the fact that most shoppers in the U.S. are on the lower end of the age range rather than older. I also observed that credit card is the most popular form of payment and cash is the least popular which shows a growing shift towards digital and cashless payments in regards to american consumers.

In the next step, I conducted data transformation. I dropped rows with missing data as well as columns with an overwhelming amount of missing data. I also transformed the review rating column which resulted in all NaN values being replaced with "Missing" and all present values being replaced with "Present". After rechecking the df and ensuring all missing values were removed, I wrote the transformed df to the data processed folder.

In the final step, I analyzed the data in order to answer important questions about the dataset. The first part involved creating pivot tables to analyze the relationshipm between season and color, disocvering what the most popular colors were by season. I also generated a pivot table to view the most purchased item per season. Next, I created 2 new dataframes in order to differentiate shoppers who did and did not use a promo code. Following this, I conducted a ttest. At the end of the final step, I used the pivot tables and analytics to answer important questions about the data. I observed that in both winter and fall, burnt orange is in the top 3 popular colors, while in summer and spring, baby blue and lavender are among the top 3. This might show a preference for darker colors in the colder months and lighter colors in warmer months. I also observed that the most popular item in winter is leggings which is explained by the cold weather while in the summer it is shorts in  order to deal with the warm weather.
