# Intro
A real estate invsetor came to me and wanted to know what 5 zipcodes should he invest in. I was given a database from zillow with many zipcodes in America.

#PreProcessing
I decided to give my client a very safe strategy. I wanted to only invest in houses that had stable house prices and also high returns. To do that thook the average of standard deviation of all my zipcodes and decided that the bottem half qualified as stable prices. Next i took the average monthly return on all my zipcodes that were in the lower half of standard deviation. Lastly i took the top 5 houses that had the best return 

#Baseline Modeling
The first part of my modeling process i just wanted to get 5 baseline models for my zipcodes. I decided to use a sarima model since my i felt like there was a seasonality component to house prices. After running my baseline models i realized something wasnt right with my models. I spent alot of time trying to figure it out but could not solve it. I hoped i would be able to fix it while creating an improved model


# Improving my models
One big thing i did was try to improve my baseline model. I did this by creating a grid search that returuns the best params for my model. After i implemented my best params into my models,there was still something slighty off in my models. I went deeper to try and fix this problem but with no luck.

#Best 5 zipcodes?
After everything my best 5 zipcodes included 2 from Houston Texas, 1 from pfulugerville Texas, 1 from El Paso Texas and lastly 1 from Nashville Tennessee. These turned out to have great returns and were very stable


#Conclusion and future work
After all i would think that my investor should invest into the zipcodes. If my models are correct my client can make a great retrurn on investment over the next 4 years which is around 50% which is great. 

For some future work i really want to focus on the southern states and see why they are more stable than other states in America. For now my guess is that the tax laws might influence the housing prices. Also i want to learn more about how time series models really work, so that i can fix my errors and create more accurate forecasting models.

