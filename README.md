# Predict-Customer-Personality-to-boost-marketing-campaign-by-using-Machine-Learning
Tools : Google Colab Visualization : Seaborn and Matplotlib Library Dataset : Rakamin Academy


A company can rapidly grow by understanding its customers' personalities, enabling them to 
provide better services and benefits to potential loyal customers. By analyzing historical 
marketing campaign data to enhance performance and target the right customers for 
transactions on the company's platform, our focus from these data insights is to create a 
predictive clustering model, making it easier for the company to make decisions.

## Steps:
1. EDA : Conversion Rate Analysis Based on Income, Spending and Age
2. Data Cleaning & Preprocessing :

   
    ● There are missing values in Income 24 rows (1.071%). It decided to drop them because they do not significantly affect the results.


    ● There is no duplicated data.

   
    ● Drop some unnecessary features.

   
    ● Perform feature encoding on the features Education, Marital_Status, and Age_Category.

   
    ● Handling Outliers using IQR

   
    ● Data selection is using the RFM model as follows:
      - R (RECENCY): Time elapsed since the customer's last purchase (Recency).
      - F (FREQUENCY): Total number of orders (Total_Purchases).
      - M (MONETARY VALUE): Total order value for buying products (Total_Spent).
    ● Standarization and Rename Column
3. Data Modeling using K-Means Clustering
4. Interpreting Model :

   
    ● **Cluster 0**: Customers in Cluster 0 are relatively new but already show high shopping frequency and significant spending.

   
    ● **Cluster 1**: Customers in Cluster 1 are relatively new customers with low shopping frequency and relatively low spending.

   
    ● **Cluster 2**: Customers in Cluster 2 are long-term, high-frequency shoppers with the highest spending.

   
    ● **Cluster 3**:  Customers in Cluster 3 are long-term customers but with low shopping frequency and relatively low spending compared to other clusters.

