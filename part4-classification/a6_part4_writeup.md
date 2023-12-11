# Part 4 - Classification Writeup

After completing `a6_part4.py` answer the following questions

## Questions to answer

1. Comment out the StandardScaler and re-run your test. How accurate is the model? Why is that?
> If we comment out the Standard Scalar, the model loses accuracy as it goes from ~0.85 to ~0.63 which is far less accurate. This is because without the data being standardized to a certain level, the numbers will be larger and will influence the final answer.
2. How accurate is the model with the StandardScaler? Is this model accurate enough for the given use case? Explain.
> The model with StandardScalar is far more accurate. I would say that this model is accurate enough for the given use case because it has a rate of around 0.85 which is a pretty accurate level as well as there only being two options.
3. Looking at the predicted and actual results, how did the model do? Was there a pattern to the inputs that the model was incorrect about?
> The model did pretty well on by testing the predictedand actual results. There didn't seem to be much of a pattern with the inputs that the model was incorrect about but I would assume that they would be edge cases.
4. Would a 34 year old Female who makes 56000 a year buy an SUV according to the model? Remember to scale the data before running it through the model.
> No
