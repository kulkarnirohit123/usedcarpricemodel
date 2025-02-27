Overview

In this application, you will explore a dataset from Kaggle. The original dataset contained information on 3 million used cars. The provided dataset contains information on 426K cars to ensure the speed of processing. Your goal is to understand what factors make a car more or less expensive. As a result of your analysis, you should provide clear recommendations to your client—a used car dealership—as to what consumers value in a used car.

What drives the price of a car?
Business Understanding

A car dealership is a volume based business and pricing a car to match the demand is key. When there is a large supply of used cars across dealerships, it make little sense for dealers to mark up significantly. Recently due to Ukraine war and chip shortage, there was a dearth of new cars in the market. Used cars of all kinds were in demand. Timing plays a factor in the used car market, however the specific thing we are trying to find in this assignment is also, what factors within the characteristics of the car still tend to influence the price more. True, a luxury car with the same mechanical specs tends to be more expensive. Lets dive into this and learn more about the used car domain
Data Understanding

Before looking at the dataset, here is the approach I would like to pursue:

    Review the dataset for what attributes are included
    Review how the columns correlate to the price using the techniques we have learned
    Resolve quality issues - dropna, and drop columns
    Remove columns that dont seem to have as much effect on the price
    If there is historical pricing data for the same car before it is sold, we could do some autocorrelation to see how prices affected the sale price
