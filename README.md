# Practice notebooks

This will mainly deal with notebooks where certain analysis will be uploaded to make conclusions based on some data set. This is done so that it is easy to go through the process again if require. We wil be individually dealing with different datasets and questions asked within ipython notebooks

## Airbnb listing dataset
In this dataset, airbnb have provided us with dataset of different listing including the price, review, neighborhood etc. With this dataset it may/may not be possible to answer questions such as:

1. Does price of the property affect the review score?
2. Does cancellation policy affect the review score?
3. The most expensive neighborhood?
4. Does host listings count affect the review score?

### Libraries used
1. numpy
2. pandas
3. matplotlib.pyplot 
4. seaborn

### Files in the repository
1. airbnb_seaatle/listing.csv: lists all the airbnb listing in seattle
2. airbnb_seattle/airbnb_seattle.ipynb: Ipython notebook of the analysis
3. airbnb_seattle/reviews.csv: lists all the reviews of airbnb listings in seattle
4. airbnb_seattle/calendar.csv: lists the price and date of listing of airbnbs in seattle

### Summary of results
1. Price, cancellation policy etc does not affect review score that much
2. Number of listing that the host had seems to adversely affect the review score
3. The most expensive area based on median rental rate seems to be South Eastern Magnolia

### Acknowledgements
* Data source: [Seattle airbnb open data](https://www.kaggle.com/datasets/airbnb/seattle)

* Please go through the notebook and let me know if something is off. The blog can be found [here](https://code2yugen.substack.com/p/nobody-cares-if-you-have-strict-cancellation)
