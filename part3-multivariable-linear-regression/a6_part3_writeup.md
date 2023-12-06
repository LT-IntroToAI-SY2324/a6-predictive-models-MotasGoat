# Part 3 - Multivariable Linear Regression Writeup

After completing `a6_part3.py` answer the following questions

## Questions to answer

1. What is the R Squared coefficient for your model? What does that mean about the model in relation to your data?
 > The R^2 value is around 0.85 which means that there is a strong correlation between the age and amount of miles on a car and the price of said car.
2. Is your model accurate? Why or why not?
 > I would say that my model is fairly accurate as it is able to predict within ~500 dollars typically, although there are sometimes outliers that are way less or more expensive but this could have to do with other factors we aren't accounting for such as the make and model of the car which could affect the price.
3. What does the model predict a 10-year-old car with 89000 miles is worth? What about a car that is 20 years old with 150000 miles?
 > When the model predicts a 10 year old car with 89,000 miles it is worth $9,273.66. If we were to do a car that is 20 year sold with 150,000 miles the price would be around $2442.09 according to the model.
4. You may notice that some of your predicted results are negative. This is occurring when the value of age and the mileage of the car are very high. Why do you think this is happening?
 > I think this is happening because the correlation formula is linear instead of being exponential. In reality the car price wouldn't plummet into the negatives it would eventually flatten out and have an asymptote of a price. The model is linear however so it does not account for the rate of change changing over time as the car gets older. 