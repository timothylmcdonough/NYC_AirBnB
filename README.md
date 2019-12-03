# New York City Rental Price Prediction Report

Air BnB Prediction Values Project (Python)

The year is 2016 and I had decided to sell my apartment in Hoboken New Jersey and move out to the suberbs to make room for my 
expanding family. Trying to save on costs and maximize return, I decided to try to list and sell the apartment myself rather 
than using a realtor. In my reasearch for what sale price to list my apartment, I learned it was best to use prices of similar 
neighboring properties which had recently sold.

After completing this task I decided it was time to list my apartment on the open market which came with a slew of calls from 
real estate agents offering their services to help me sell the apartment. One day, during one of the agent conversations I had 
answered, I received the question, "How did you decide what amount to sell it for?" 
to which I told him I researched previously sold values of similar properties nearby. 
The agent told me, "You did a good job, this is exactly the price I would have listed it for."

Years later, in my efforts to expand on my data science skillset, I read about a similar circumstance where the same pricing strategy was used to determine the asking price. 
After reading this, a light bulb went off in my head. I used this sort of thinking years ago without even knowing this is how real estate prcing is actually done!  I said to myself, "I wonder how well I could do in predicting real estate values on an actual data set?"

This, is what lead my to the project below where I will attempt to predict rental values for Air BnB rentals for the Bronx borough of New York City.

## Business Problem

Landlords post their rental properties properties with rental prices either too high or too low with the surrounding relative real estate market.  Real estate companies, in order to increase their company revenue, could come up with a way to identify these properties and offer company services to the property owner, part of which includes listing the property rental price for an amount more in line with nearby comparative rental properties. This would increase number of days the property is rented throughout the course of the year and thus, would give the landlord a bigger financial return on their property.

## Client
New York City Real Estate Company

## Objective 

Come up with a solution to sell to a real estate company which pulls in a rental property data for an area of interest, identifies properties who are priced either too high or too low, and predicts a rental price for those properties more in line with what would be a reasonable price to be asking for the given property based off of nearby comparative properties.

## Solution

I imported an Air BnB (a short term real estate rental company) dataset.  From there I scrubbed and cleansed the data in order to make is workable for what type of modeling we need to perform on the data.  After this, I designed and deployed 3 different algorithmic models onto dataset (Linear Regression, Random Forest, and Gradient Boosting) then compared the MSE accuracy results (mean squared error) of these 3 models against each other to determine which algorithm predicted these rental prices most accurately (lowest MSE). 

## Result
The model with the highest accuary percentage was the Random Forest model producing an MSE of 5160.  
