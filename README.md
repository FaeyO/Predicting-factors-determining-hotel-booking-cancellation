# Factors Determining Hotel Booking Cancellation

## Table of Contents
  - Project Overview

  - Tools

  - Data Cleaning
    
  - Exploratory Data Analysis

  - Supervised Machine Learning

  - Recommendations

### Project Overview
I have been enlisted to provide support to a hotel's project aimed at enhancing revenue generated from room bookings. The hotel believes that leveraging data science can effectively minimize booking cancellations. This is where my expertise becomes invaluable.
My task will entail employing suitable methodologies to determine the factors influencing whether a booking will be fulfilled or cancelled. The hotel intends to utilize the insights derived from my analysis to proactively reduce the likelihood of booking cancellations.

### Tools
 - Python - Data Analysis
 - Matplotlib - For Data Visualizations
 - Seaborn - For Data Visualizations
 - Numpy
 - Pandas
 - Scikit-learn
 - Jupyter notebook - Coding Environment 

### Data Cleaning
In the data preparation phase, i performed the following tasks;

1. Data loading
2. Data Validation
3. Data cleaning
4. Handling Missing Values

### Exploratory Data Analysis
Insights from EDA include;

 -The Prices per room over time graph shows that the people who cancelled thier booking where does who had the highest prices for rooms.
 
 -The lead time by prices graph shows that people who had shorter Number of days before the arrival date the booking was made were more likely to not to cancel their booking.
 
 -The count of various Reserved Room Types shows that Room Type1 is the most Reserved room for both persons who canceled and those who did not cancel thier bookings.
 
 -The weekday by booking status graph shows majority of cancelled booking were on sunday, however sunday had majority of bookings.
 
 -The heat map shows that number of special request and booking statuses have moderate relationship, while the number of previous booking not canceled has a weak relationship with booking status. We can also see that Lead time have a negative moderate relationship with booking status.
 
### Supervised Machine Learning
Supervised machine learning is a type of machine learning where the algorithm is trained on a labeled dataset, meaning that the input data is paired with corresponding output labels. The goal of supervised learning is to learn a mapping or relationship between input features and their corresponding output labels, allowing the algorithm to make predictions or classifications on new, unseen data. RandomForestClassifier achieve the highest accuracy scores, indicating their effectiveness in classification tasks.

### Recommendations
From the analysis, It can be seen that factors like :

 1. If an individual made reservations Offline or Online
 2. If individual requested for parking space
 3. If booking was done in the month of January
 4. The number of days before the arrival date the booking was made(lead time).
 5. The average price of the room booked
 6. The number of special request made by the individual. are very important factors to be considered as they most likely will determine if an individual will cancel the booking made .
Further I will recommend for the busines to use these important factors in predicting whether a customer will cancel or not.
