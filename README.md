<h1 align="center">
Customer Segmentation using RFM Analysis
</h1>

<h2 align="center">
Introduction
</h2>
<p>
In today’s ever-changing e-commerce landscape, understanding and engaging your customers
is one of the most important things that can make or break a business’s success.
In this project, we’re diving into Customer Segmentation with the help of Recency, Frequency,
and Monetary (RFM) analysis. RFM is a powerful tool used by businesses to analyze and
understand customer purchasing behavior.
The eCommerce dataset is a vast collection of transactional data that serves as the basis for
our research into creating different customer segments.
</p>

<h2 align="left">
Objectives
</h2>
<p>
1. To perform comprehensive exploratory data and RFM analysis on the given eCommerce dataset. <br>
2. To segment customers based on their RFM scores, revealing valuable insights into customer behavior. <br>
3. To enable the development of focused marketing campaigns and effective retention strategies through the identified customer segments. <br>
</p>
<h2 align="left">
Data Description
</h2>
<p>
<b>InvoiceNo: </b> Unique identifier for each transaction.<br>
<b>StockCode: </b> Code associated with the product. <br>
<b>Description:</b> Brief description of the product. <br>
<b>Quantity:</b> Quantity of the product purchased. <br>
<b>InvoiceDate:</b> Date and time of the transaction. <br>
<b>UnitPrice:</b> Price of a single unit of the product. <br>
<b>CustomerID:</b> Identifier for the customer making the purchase. <br>
<b>Country:</b> Country where the customer is located. <br>
</p>
<h2 align="left">
Data standardization
</h2>
<p>
As the data was skewed, it was normalised by log transformation to get these results
</p>
</table>
![image](https://github.com/mansiraturi/RFM_Analysis/assets/83804789/00eb628d-9900-4441-ab66-98f0943b8948)
![image](https://github.com/mansiraturi/RFM_Analysis/assets/83804789/20af1e7e-6dcb-4185-a707-bb5037d5002c)
<h2 align="left">
Data Preprcoessing
</h2>
<p>
The dataset was profiled on python as well as Alteryx by converting to appropriate datatypes, removing duplicate values, handling null rows and adding appropriate additional columns.
</p>
<h2 align="left">
Customer Segmentation
</h2>
<p>
The Recency, Frequency and Monetary values and scores were calculated for every customer . The resulting RFM scores were then used to categorize customers into distinct groups such as "Best Customers," "Loyal Customers," "Almost Lost," and "Passerby Customers."
</p>
<h2 align="left">
Clustering 
</h2>
<p>

Advanced K-means clustering was utilized for additional customer segmentation, taking into account data distribution and standardization. To determine the optimal number of clusters, the Elbow method was employed. After careful consideration, 4 clusters were chosen for segmentation. K-Means clustering and Silhouette score were applied to the RFM values to effectively group customers into distinct segments based on their purchasing behavior and engagement with the platform. This approach ensures a thorough understanding of customer segments, facilitating targeted marketing campaigns and retention strategies tailored to the specific needs and preferences of each segment.
</p>
![image](https://github.com/mansiraturi/RFM_Analysis/assets/83804789/d7fd7346-e2d9-4a9d-9eb3-ea23175bcbd7)

<h3 align="left">
Cluster Correlation heat map
</h3>
![image](https://github.com/mansiraturi/RFM_Analysis/assets/83804789/b5a6a57d-f8cd-4388-9073-5f9e63c68dc6)


