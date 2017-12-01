# Collaborative Filtering

Two algorithms I coded as part of Ying Liu's Fall 2017 Applied Data Science course at Columbia.

SimRank is coded in R, and based on [this paper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.578.8723&rep=rep1&type=pdf) by Glen Jeh and Jennifer Widom, and also based on Colin Su's [Python implementation](https://github.com/littleq0903/simrank).

Mean Squared Difference was coded in Python, and was optimized for parallel processing.

The data should be a sparse matrix. For SimRank the data should be 1s and 0s. For Mean Squared Difference, the data can be the scores.
