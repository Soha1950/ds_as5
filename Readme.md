# Will-a-Customer-Accept-the-Coupon?

The main goal of this project is to utilize Python libraries, particularly Pandas, Seaborn, Matplotlib, and Numpy, to analyze and visualize data. The project specifically focuses on predicting the likelihood of drivers, whether with or without passengers, accepting or rejecting coupons. The analysis relies on conditional probabilities for prediction.

### Python is employed as the primary programming language, enabling a thorough data analysis process.
The Pandas, Seaborn, Matplotlib, and Numpy libraries play a crucial role in visualizing patterns and relationships within the dataset.

A comprehensive analysis, including observations and comments, is meticulously documented in the client's notebook, serving as the primary reference for all completed project tasks.

[Link to Notebook](https://github.com/Soha1950/ds_as5/blob/main/prompt.ipynb)

It's important to note that certain columns (Car, Bar, Cafe, Carry Away, RestaurantLessThan20, Restaurant20To50) contain missing values, indicating potential data gaps that could impact the analysis.

One significant finding from the conditional probability analysis is that drivers who accept the "Coffee House" coupon demonstrate the highest probabilities compared to those accepting "Restaurant (<20)" and "Run and pick up" coupons. This insight is effectively depicted through barplots, providing a clear visualization of the observed conditional probabilities.

![Image of chart 1](https://github.com/Soha1950/ds_as5/blob/main/screenshot/coupon1.png)

### Subsequently, I scrutinized other columns, and the analysis yielded the following insights
The visualization reveals a pronounced trend, indicating that individuals who accept coupons and visit bars between 1 and 3 times a month are more inclined to do so compared to those who frequent bars more than 3 times. This insight suggests a correlation between coupon acceptance and a moderate frequency of bar visits.

The heightened likelihood of accepting coupons within the demographic that engages with bar moderately could be indicative of a balanced engagement with the social setting, making this group more receptive to promotional incentives.

![Image of chart 2](https://github.com/Soha1950/ds_as5/blob/main/screenshot/image2.png)

### Addressing the question about the distribution of coupon recipients across different age groups and their corresponding bar visit frequencies.
#### I employed the Seaborn library to create a Violin chart.
I filtered the data for Bar coupons and coupon acceptance (Y=1) and explored the interaction with two additional columns. The visualization, focusing on the age range of 20 to 30, revealed a distinctive pattern: individuals within this age bracket tend to visit the bar more frequently, particularly in the range of 4 to 8 times. Notably, the chart's significant width in this age group serves as a visual indicator, suggesting a substantial correlation and interconnectedness between the provided data points.

![Image of chart 3](https://github.com/Soha1950/ds_as5/blob/main/screenshot/image3.png)

### In addressing the inquiry regarding the distribution of coupon recipients within various passenger groups—such as those driveing alone, with friends, or with partners—and their corresponding bar visit frequencies
#### I utilized the Seaborn library to generate a countplot.
After filtering the data for bar coupons and coupon acceptance (Y=1), I explored the interaction with two additional columns. The visualization, specifically focusing on solo travelers, revealed a clear trend: individuals who are alone exhibit a higher inclination to visit the bar, followed by passengers accompanied by friends. On the other hand, those with children display a relatively lower inclination towards bar visits.

![Image of chart 4](https://github.com/Soha1950/ds_as5/blob/main/screenshot/Screenshot%202024-02-29%20173851.png)
