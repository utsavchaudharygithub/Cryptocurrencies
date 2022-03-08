# Cryptocurrencies
We created a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.The data Martha provided us was not ideal, so we processed to fit the machine learning models. Since there is no known output for what Martha is looking for, we decided to use unsupervised learning. To group the cryptocurrencies, Martha and us decided on a clustering algorithm. We used data visualizations to share our findings with the board.

# Resources Used:
Crypto_data.csv
# Applications used: 
Software: Python 3.7.7, Anaconda Navigator 1.9.12, Conda 4.8.4, Jupyter Notebook 6.0.3

# Process Used:
* Preprocessing the Data for PCA: preprocessed the dataset in order to perform PCA 
<img width="572" alt="Screen Shot 2022-03-07 at 10 25 14 PM" src="https://user-images.githubusercontent.com/91306158/157179969-c72fd24e-e1b6-44f3-b287-9268f7c5df02.png">


* Reducing Data Dimensions Using PCA:  Applied the Principal Component Analysis (PCA) algorithm, and reduced the dimensions of the X DataFrame to three principal components and place these dimensions in a new DataFrame.
 <img width="863" alt="Screen Shot 2022-03-07 at 10 25 29 PM" src="https://user-images.githubusercontent.com/91306158/157179562-b756aaa8-b957-4fb9-b787-1d0c3923407b.png">

* Clustering Cryptocurrencies Using K-means: The K-means algorithm is used to cluster the cryptocurrencies using the PCA data. Ran the K-means algorithm to predict the K clusters for the cryptocurrencies’ data.

<img width="1402" alt="elbowcurve" src="https://user-images.githubusercontent.com/91306158/157179658-33eac190-8a54-497d-8965-d3352664469a.png">

* Visualizing Cryptocurrencies Results: creating scatter plots with Plotly Express and hvplot,create a table with all the currently tradable cryptocurrencies using the hvplot.table() function.
<img width="787" alt="3DscatterWPCAdataandClusters" src="https://user-images.githubusercontent.com/91306158/157179740-ab109a18-dd1a-48e9-9427-4ea7dad3904d.png">

<img width="1395" alt="hvplot totalcoinsminesVSTotalcoilsupply" src="https://user-images.githubusercontent.com/91306158/157179762-56cfac12-86c8-4af4-bd4c-1b78d3578ed5.png">

# Findings:
There are 532 tradable cryptocurrencies. In Unsupervised learnings, a dataset is provied wuthoutlables, and a model learns useful properties of the structure of the dataset. Compared to supervised learning models, the unsupervised learnings have less information about eh data. The unsupervised learnings involves, grouping similar examples together, in above case similar cryptocurrencies, It also involves dimentionality reduction, and density estimation. 
