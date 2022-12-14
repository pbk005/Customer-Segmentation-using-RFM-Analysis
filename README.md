                                                            CUSTOMER SEGMENTATION USING RFM

The main objective of this project is to perform customer segmentation using RFM analysis. The dataset consists of transaction details of customers across different countries between 01/12/2010 and 09/12/2011. Data cleaning operations such as removing null values, deleting duplicate records and filtering the cancelled orders have been performed. Cohort analysis has been performed and the retention rate of customers has been calculated for each month. The same has been displayed using a heatmap.

The RFM model has been built by calculating Recency (R), Frequency (F) and Monetary (M) values for each customer and the respective scores have been assigned to each of them. Recency means the number of days since a customer made the last purchase. Frequency is the number of purchase made by the customer in a given period. Monetary is the total amount of money a customer spent in that given period. The frequency and monetary rank are assigned as highest rank for high values and lowest rank for low values whereas the recency rank is assigned in the opposite order. The RFM score is calculated by adding the corresponding RFM values of each customer. The distribution plot for R, F and M values has been plotted and it has been observed that the values are right skewed. Loyalty levels has been assigned to each customer based on the R, F, M score. 

K-means clustering algorithm is used to build the model. Optimum number of cluster has been found as 3 by plotting an elbow curve. RFM data is normalized by applying log transformation. Data scaling has been performed using standard scaler. A scatter plot has been plotted for different RFM values. Based on the RFM values clusters are assigned to each one of them.

Observations

•	Among all the countries, the county with maximum number of customers is UK.

•	The most popular product sold across all the countries is ‘Paper Craft, Little Birdie’.
