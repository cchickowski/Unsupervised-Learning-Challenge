# Unsupervised-Learning-Challenge

## Background:

You are on the Advisory Services Team of a financial consultancy. One of your clients, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. They’ve asked you to create a report that includes what cryptocurrencies are on the trading market and determine whether they can be grouped to create a classification system for this new investment.

You have been handed raw data, so you will first need to process it to fit the machine learning models. Since there is no known classification system, you will need to use unsupervised learning. You will use several clustering algorithms to explore whether the cryptocurrencies can be grouped together with other similar cryptocurrencies. You will use data visualization to share your findings with the investment bank.

## Analysis and Code: 

### Step 1:
Prepared data for unsupervised machine learning analysis. This included removing unnessary columns/null values, filtering for only coins being traded/coins mined, and converting all data to numeric values. Finally, data was scaled for the analysis.

### Step 2: 
Used PCA and t-SNE to perform dimensionality reduction on the data. This included creating a scatter plot to check for clusters. 

### Step 3: 
Used K-means to create and elbow plot and determine inertia for additional cluster analysis. 
