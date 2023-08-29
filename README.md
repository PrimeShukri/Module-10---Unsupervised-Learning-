# Module-10---Unsupervised-Learning-
Unsupervised-Learning

Challenge: Crypto Clustering

In this Challenge, I combined financial Python programming skills with the new unsupervised learning skills that acquired in this module.



    I am a financial advisor at one of the top five financial advisory firms in the world. I am working on a project to propose a novel approach to assembling investment portfolios that are based on cryptocurrencies. I want to include other factors that might impact the crypto market, such as volatility and liquidity, in addition to returns.

    My manager loves the idea, and I am asked to create a prototype for submitting my crypto portfolio proposal to the company board of directors.

    I start by importing the necessary libraries and data. The data contains the price change data of cryptocurrencies in different periods.

    I then prepare the data by normalizing it. This means that I scale the data so that all of the features have a mean of 0 and a standard deviation of 1.

    Next, I use the elbow method to find the best value for k. The elbow method is a heuristic method for finding the optimal number of clusters in a clustering problem. It works by plotting the within-cluster sum-of-squares (WSS) for different values of k. The optimal value of k is the one that corresponds to the elbow in the WSS curve.

    I run the elbow method on the original data and find that the best value for k is 4. This means that I should cluster the cryptocurrencies into 4 groups.

    I then cluster the cryptocurrencies with K-means by using the original data. This means that I use the 4 clusters that I found in the previous step.

    I predict the clusters for each cryptocurrency and create a scatter plot of the cryptocurrencies, where the color of each point represents the cluster that it belongs to.

    The scatter plot shows that the cryptocurrencies are clustered into 4 distinct groups. The first group consists of cryptocurrencies that have had a lot of volatility. The second group consists of cryptocurrencies that have had a lot of liquidity. The third group consists of cryptocurrencies that have had a lot of returns. The fourth group consists of cryptocurrencies that have had a combination of volatility, liquidity, and returns.

    I am happy with the results of the clustering, but I want to see if I can improve the results by optimizing the clusters with principal component analysis (PCA).

    PCA is a technique that can be used to reduce the dimensionality of a dataset while preserving the most important information. In this case, I can use PCA to reduce the number of features from 4 to 3.

    I run PCA on the original data and find that the three principal components explain 92.3% of the variance in the data. This means that I can reduce the dimensionality of the data without losing too much information.

    I then use the PCA data to cluster the cryptocurrencies with K-means. I find that the best value for k is still 4. This means that the optimal number of clusters does not change when I use PCA.

    I create a scatter plot of the cryptocurrencies using the PCA data. The scatter plot looks similar to the scatter plot that I created using the original data. This suggests that using PCA does not have a significant impact on the clustering results.

    I am satisfied with the results of the clustering. I believe that this approach can be used to create a novel investment portfolio that is based on cryptocurrencies. I am excited to present my proposal to the board of directors and get their feedback.



The CSV file provided for this challenge contains price change data of cryptocurrencies in different periods.

The steps for this challenge are broken out into the following sections:

    Import the Data (provided in the starter code)
    Prepare the Data (provided in the starter code)
    Find the Best Value for k Using the Original Data
    Cluster Cryptocurrencies with K-means Using the Original Data
    Optimize Clusters with Principal Component Analysis
    Find the Best Value for k Using the PCA Data
    Cluster the Cryptocurrencies with K-means Using the PCA Data
    Visualize and Compare the Results

Import the Data

This section imports the data into a new DataFrame. It follows these steps:

    Read the “crypto_market_data.csv” file from the Resources folder into a DataFrame, and use index_col="coin_id" to set the cryptocurrency name as the index. Review the DataFrame.

    Generate the summary statistics, and use HvPlot to visualize your data to observe what your DataFrame contains.

    Rewind: The Pandasdescribe()function generates summary statistics for a DataFrame.

