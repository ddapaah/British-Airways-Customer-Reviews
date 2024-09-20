# Is British Airways Meeting Customer Expectations? Insights into Sentiment and Buying Behavior

**Project Overview**  
This project is part of the Data Science Virtual Internship Program offered by Forage with British Airways. The focus is on analyzing customer feedback and predicting buying behavior to enhance the customer experience.

## Background  
British Airways operates within the airline industry, serving customers worldwide. Understanding customer feedback is crucial to providing an exceptional experience and increasing brand loyalty. The main objective of this project is to gain insights from customer reviews and predict future buying behavior using data analytics techniques.

## Project Structure  

### Task 1: Web Scraping to Gain Company Insights
The first phase of the project involved scraping customer review data from [Skytrax](https://www.airlinequality.com/airline-reviews/british-airways). The data collected helped in identifying common pain points and overall customer satisfaction.

- **Objective**: Collect and analyze British Airways customer reviews.
- **Data Source**: Skytrax, a trusted source for airline reviews.
- **Methodology**: Web scraping using Python's BeautifulSoup.
  
### Task 2: Predicting Customer Buying Behavior
Using customer booking data, we built a predictive model to estimate the likelihood of customers booking a flight with British Airways. The model takes into account various factors, including customer sentiment, past behavior, and demographic data.

- **Objective**: Predict the probability of a customer making a booking.
- **Methodology**: Machine learning model implemented using scikit-learn.

## Key Insights  
This section presents the most important findings from the analysis. These insights can help British Airways improve customer experience and increase bookings.

### Insight 1: Customer Sentiment Drives Bookings
- **Supporting Analysis**: Customers with positive reviews are 40% more likely to book future flights. This trend was observed over a 12-month period, with significant spikes during holiday seasons.
- **Visualization**:  
  ![Customer Sentiment Graph](https://user-images.githubusercontent.com/89634505/201470985-159e17d2-605d-46c1-a9f1-8d0cdd147245.png)

### Insight 2: Common Pain Points
- **Supporting Analysis**: Analysis of customer feedback revealed that the most common complaints were related to baggage handling and flight delays, contributing to 65% of negative reviews.
- **Visualization**:  
  ![Baggage Complaints Graph](https://user-images.githubusercontent.com/89634505/201471191-cdd85024-1691-4136-b9f8-b4b1d8d42f72.png)

### Insight 3: Seasonal Trends in Bookings
- **Supporting Analysis**: There is a notable increase in bookings during peak seasons such as summer and year-end holidays. Customers who leave positive reviews tend to book more frequently during these periods.

### Insight 4: Importance of Customer Service
- **Supporting Analysis**: Customers who reported receiving excellent customer service were twice as likely to return and recommend British Airways to others.

## Data Structure & Initial Checks
The dataset used for the analysis consisted of the following tables:
- **Customer Reviews**: Detailed feedback from customers on Skytrax.
- **Bookings**: Historical customer booking data.
  
The initial cleaning process involved handling missing data, standardizing date formats, and removing outliers that could skew predictions.

## Recommendations  
Based on the insights, we recommend that British Airways take the following actions:

1. **Enhance Baggage Handling Processes**: By reducing the incidence of lost or delayed luggage, BA can improve overall customer satisfaction.
2. **Improve Communication on Delays**: Providing timely updates on delays could reduce the negative impact on customer sentiment.
3. **Leverage Customer Service Excellence**: Focus on maintaining high standards of customer service, which directly correlates with repeat bookings.

## Assumptions & Caveats  
Throughout the analysis, several assumptions were made:
- Missing data for December 2021 was imputed using trends from December 2020.
- Review data was considered reliable based on Skytrax’s reputation, though some inherent bias in reviews may exist.
