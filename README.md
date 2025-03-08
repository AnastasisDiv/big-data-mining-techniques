# Big Data Mining Techniques

Project of the **Data Analytics** course in **NKUA DIT**.

## Part 1: Text classification 

The task is to classify articles in 4 different categories:
- Business
- Entertainment
- Health
- Technology

In order to tackle this task, we used 2 different *classification methods* using **Bag of Words (BoW)** and **5-fold Cross-Validation**:
- Support Vector Machines (SVM)
- Random Forests

Dataset is available in [Kaggle](https://www.kaggle.com/competitions/bigdata2024classification/data).

## Part 2: Nearest Neighbor Search with Locality Sensitive Hashing

The purpose of Part 2 is to speed up the **K-NN classification** (K=7) method, using the **Locality Sensitive Hashing** technique on the same Dataset as Part 1.

We first run the **Brute-Force K-Nearest Neighbors** algorithm in order to find the *7 most similar documents* for each document, using the `Jaccard Similarity` metric.

Then, we test the **Min-Hash LSH** technique with various parameters for *number of permutations* and *threshold*, and compare the **execution times and accuracy** with the **Brute-Force** method.

## Part 3: Time Series Similarity

In this part, we implemented the **Dynamic Time Warping (DTW)** algorithm, in order to compute the similarities between time series of *different time resolutions*.

Dataset is uploaded at [dtw_test.csv](https://github.com/AnastasisDiv/big-data-mining-techniques/blob/master/dtw_test.csv), inside this repository.
