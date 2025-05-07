# Fire_Plants
Interpreting California fire and plant datasets

To start, we identified the geopandas library as the best library to overlap our datasets over the same geographical area. After mapping the datasets onto each other, we ran into problems identifying the meaningful methods in which we can interpret our data. We ended up deciding to try several different classification techniques as well as linear regression to try and identify which plants are most likely to grow in fire prone areas. 

We now want to interpret our data and use several techniques to show which classification is appropriate. For this, we tried kNN clustering from class. Classifying our plants in 4 classes based on percentiles shows that with each class how accurate our data will be, since the red class (highest percentile) is the highest accuracy for common weeds or weeds that have been in many fires). 
