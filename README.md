# Recommender System with Non Negative Matrix Factorization
Computer Science Department of Shahid Beheshti University

Machine Learning Course Project

**Student** : Mohammad Saeid Heidari

**Supervisor**  : Dr.Katanforoush 

February 2023

# About the project
In this project, I have implemented the recommender system with two methods, [1-Non Negative Matrix Factorization](https://github.com/ms-heidari/Recommender-System-with-Non-Negative-Matrix-Factorization/tree/main/NMF) and [2-Ordinal Non Negative Matrix Factorization](https://github.com/ms-heidari/Recommender-System-with-Non-Negative-Matrix-Factorization/tree/main/Ord-NMF), by adapting papers such as [paper 1](https://github.com/ms-heidari/Recommender-System-with-Non-Negative-Matrix-Factorization/blob/main/Research%20papers/Paper1-ordNMF.pdf) and [paper 2](https://github.com/ms-heidari/Recommender-System-with-Non-Negative-Matrix-Factorization/blob/main/Research%20papers/Paper2-Nmf%20Algorithms.pdf). And every time I have run it on [Netflix Prize dataset](https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data) and reported the result, it is interesting to examine the error history of two matrix W and H in both methods.


# [Dataset](https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data)
The file "training_set.tar" is a tar of a directory containing 17770 files, one
per movie. The first line of each file contains the movie id followed by a
colon. Each subsequent line in the file corresponds to a rating from a customer
and its date in the following format:

**CustomerID,Rating,Date**
- MovieIDs range from 1 to 17770 sequentially.
- CustomerIDs range from 1 to 2649429, with gaps. There are 480189 users.
- Ratings are on a five star (integral) scale from 1 to 5.
- Dates have the format YYYY-MM-DD.


# References
- [Ordinal Non-negative Matrix Factorization for Recommendation (main paper)](https://github.com/ms-heidari/Recommender-System-with-Non-Negative-Matrix-Factorization/blob/main/Research%20papers/Paper1-ordNMF.pdf)
- [Algorithms for Non-negative Matrix Factorization](http://web.cs.ucla.edu/~yzsun/classes/2014Spring_CS7280/Papers/Clustering/NNF_lee01algorithms.pdf)
- [Bayesian Non-negative Matrix Factorization](http://mikkelschmidt.dk/papers/schmidt2009ica.pdf)
