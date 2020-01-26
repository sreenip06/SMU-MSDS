### Introduction

This project covers the details of exploratory analysis on US Craft Beers and Breweries data sets provided to us. We did the required analysis on the data sets to answer key questions as well as gather interesting findings based on the data.

### Input Data Sets

i. Beers.csv - Contains data on 2000+ craft canned beers brewed in the US
ii. Breweries.csv - Contains data for 500+ breweries in the US
iii. StatePopArea.csv - Contains the population (as of 2019) and area (in square miles) for the 50 US states and District of Columbia

### Key Analysis Questions

The analysis addresses the following key questions:

1. Where are the craft beer breweries located?
2. What's the quality of data we have?
3. What are the median beer measures by State?
4. Which are our most strong and most bitter beers?
5. What is the distribution of ABV of our beers?
6. Is there a correlation between ABV and IBU measures?
7. Can we classify IPA and Other Ale beers using a KNN model based on ABV and IBU?

In addition, we also conduct a brewery adequacy analysis assessing the number of breweries in a State relative to its population and area.

### Conclusions

- In general, the breweries are distributed throughout the US relative to the State's population, with a few exceptions
- IBU measure is missing for more than 40% of the observations in the input data set; availability of quality data is key to make effecitve inferences from the analysis
- Median values are good center measures to assess the state-wise distribution of ABV and IBU measures
- A moderate positive correlation exists between ABV and IBU measures; in addition, we can build an effecitve model to classify beers as IPAs or Other Ales using the ABV and IBU measures
