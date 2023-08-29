# Module-10---Unsupervised-Learning-
Unsupervised-Learning

Challenge: Crypto Clustering

In this Challenge, I combined financial Python programming skills with the new unsupervised learning skills that you acquired in this module.

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

