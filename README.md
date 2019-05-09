# Starbucks-Project
Exploring customer behaviour purchase of Starbucks and grouping the like customers in Clusters
# Project Overview
The Starbucks project was my capstone project for the Udacity Data Scientist Nanodegree.
This data was provided by Starbucks to behaviour pattern of the Customer and their transaction 
to see if there are better approaches to sending customers specific promotional deals.

I wanted to do this project beacause I wanted to upskill my knowledge on clustering model and also to understand the 
behaviour of the customer and see how can I influence business by giving them the better approch of through statistical 
understanding of the data.

The different files that were used to create this project are located in the Profile Portfolio and Transcript Data.zip file. Here is a quick overview of each file:

1. Profile - Dimensional data about each person, including their age, salary, and gender. There is one unique customer for each record.
2. Portfolio - Information about the promotional offers that are possible to receive, and basic information about each one including the promotional type, 
  duration of promotion, reward, and how the promotion was distributed to customers
3.Transcript - Records show the different steps of promotional offers that a customer received. 
  The different values of receiving a promotion are receiving, viewing, and completing. 
  You also see the different transactions that a person made in the time since he became a customer.
  With all records, you see the day that they intereacted with Starbucks and the amount that it is worth.
  
 One important segment of any business is to look for areas that can be improved create more revenue. 
 I was determined to look to see how well certain promotions were being used by all customers and to try and see what was a more effective method to offering promotions.
 Once I could see how people normally reacted, the problem then became to find a better way to make sure that the right people were receiving the right promotions.
 
 I used exploratory analysis to see what type of customers existed in the Starbucks universe, their transaction / promotional engagement habits, 
 and created a customer matrix dataframe that gae the whole view of what type of customer they were.
 The best machine learning approach was then to use a clustering method that could break up customers into different segments 
 that would respond differently to different promotional deals.

By doing this, Starbucks can allocate their promotional deals in a more effective manner. 
People who come back on a regular basis dont need buy one get one free deals, but should receive discount deals.
People who might not be able to afford coming into Starbucks stores at a constant basis or don't go regularly for their own reasons
should be given BOGO deals to reengage their interests in Starbucks and make them a more reliable customer.

My results showed that Starbucks customers fall into 4 different categories based on mostly their income and the number of times they interact with Starbucks.
There are 2 clusters that come consistantly to Starbucks that don't need to receive buy one get one free offers and should only receive discounted promotions. 
That way those customers still feel rewarded for being a customer, while Starbucks saves some money that they were giving away to them when they didn't have to.
The other 2 clusters are groups of people who should be offered more buy one get one free promotions. These customers might not be able to afford coming into Starbucks
stores at a constant basis or don't go regularly for their own reasons should be given BOGO deals to reengage their interests in Starbucks and make them a more reliable customer.


