README
# Practical Application Assignment 5.1: Will the Customer Accept the Coupon?

This repo contains practical application assignment 5.1 from Berkeley Engineering & Berkeley Haas Professional Certificate in Machine Learning and Artificial Intelligence.

## File Navigation
A Jupyter notebook named ["PracticalApplication5.1.ipynb"](https://github.com/ohmjoh/BerkeleyML/blob/main/PracticalApplication5.1.ipynb) contains the code for this analysis.
[data folder](https://github.com/ohmjoh/BerkeleyML/tree/main/data) contains the data used for this analysis.

## Data
The data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’. There are five different types of coupons -- less expensive restaurants (under $20), coffee houses, carry out & take away, bar, and more expensive restaurants ($20 - $50).

## Analysis
The analysis is composed of two parts:
* Answering the prompts of the assignments
* Independant investigation

## Independant Investigation

### Background
I selected the subdataset with people who received the coupons for Coffee House.

### Objectives
The goal for this investigation is to highlights the differences between customers who did and did not accept the coupons. 
I interpretation of descriptive and inferential statistics to explore the data utilizing visulization skills.

### Conclusion
Based on the data exploration of the Coffee House coupons, the following hypotheses can be derived regarding the characteristics of drivers who accepted the coupons:

* Temperature: Drivers are more likely to use the coffee house coupon as the temperature gets warmer.
* Age: Younger drivers are more likely to accept the coffee house coupon compared to older drivers.
* Coffee House Visit Frequency: As the frequency of visiting coffee houses increases, the acceptance rate of coffee house coupons also increases until it reaches a peak at around 3 visits per month and then slightly decreases.
* Restaurant Visit Frequency: Drivers who visit restaurants more frequently, regardless of the price range, are more likely to accept the coffee house coupon.
* Distance: The acceptance rate of the coffee house coupon decreases as the distance from the driver's location to the coffee house increases.
* Carry Away: Drivers who frequently purchase take-away food are more likely to accept the coffee house coupon.
* Other Variables: Some categorical variables such as destination, passenger type, weather, expiration, marital status show affect the acceptance rate of the coffee house coupon.
* income, gender, presence of children, and same direction do not show consistent patterns or strong relationships.

These hypotheses provide insights into the characteristics of drivers who are more likely to accept Coffee House coupons. These insights can be utilized when deciding target demographic/environment to distribute the coupons.

However, further statistical analysis and hypothesis testing would be required to validate these findings and determine the significance of the relationships observed.
