# Cerberus

Cerberus was tasked with exploring various aspects of breweries throughout the United States utilizing the beers.csv and the breweries.csv datasets provided.

The primary questions of interest were as follows:
1.	What is the count of breweries in each state?
2.	What I the median alcohol content and international bitterness unit for each state?
3.	Which state has the beer with the highest alcohol content and which state has the beer with the highest international bitterness unit?
4.	Show summary statistics for the ABV data
5.	What is the relationship between bitterness and alcohol content?
6.	What is the relationship of ABV and IBU for IPAs and other Ales?
7.	What other discoveries came from the project?

The codebook begins with a count of the breweries by state and a histogram to demonstrate the values.  It then merges the datasets to facilitate further exploration. NA values were removed to compare complete data.  The codebook then answers the median values question and the maximum values question.  Bar charts are created for a visual reference of the medians by state.  It was discovered that a relationship between bitterness and alcohol content exists using a scatterplot with a simple linear regression line.

To explore a bitterness / alcohol content relationship for IPAs and Ales, the codebook uses a maximum efficiency KNN model to predict the style of beer based on ABV and IBU.
The codebook then explores the potential in marketing an IPA in the southeast region of the United States by demonstrating the popularity of IPAs vs the lack of IPA options in the region.
