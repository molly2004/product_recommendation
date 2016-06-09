# product_recommendation
Use Hadoop MapReduce jobs to analysis log files to provide product recommendation.

##### Builds three matrices from web log files:
* History matrix:  contains the interactions between users and products as a user-by-product binary matrix
* Co-occurrence matrix:  transforms the history matrix into an product-by-product matrix, recording which product co-occur or appear together in user histories.
* Indicator matrix: The indicator matrix retains only the anomalous (interesting) co-occurrences that will serve as clues for recommendation. 

<img src=“https://github.com/HongyuSun2004/product_recommendation/blob/master/mapreduce.png" align=“middle” />
<img src=“/HongyuSun2004/product_recommendation/blob/master/mapreduce.png" align=“middle” />