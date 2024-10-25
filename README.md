# CUSTOMER-SEGMENTATION-USING- KMEANS-&-HIERARCHICAL-CLUSTERING

![customer segmentation image](https://github.com/user-attachments/assets/a853682f-b03a-4942-8806-be670b1f11a2)



## Objective of the project 

This Customer Segmentation Project aims to categorize customers into distinct groups based on their purchasing behavior and demographics. By leveraging advanced clustering techniques, i analyze key attributes such as spending score, age, and annual income. The objective is to empower businesses with a deep understanding of their customer base, enabling personalized marketing strategies that enhance engagement and drive profitability.

## Business Problem
A company faced significant challenges in optimizing their marketing strategies due to insufficient understanding of their customer base. The absence of precise customer segmentation resulted in inefficient resource utilization, low customer engagement, and missed revenue growth opportunities. As a machine learning engineer, I decided to develop a solution that identifies unique customer segments based on behavioral and demographic factors, aiming to enable tailored marketing, improve customer satisfaction, and boost overall sales and profitability.

## Problem Encountered: Incompatible Data Type for Indexing
During the project, I encountered an issue with indexing a Pandas DataFrame using boolean arrays, which was incompatible with the plt.scatter() function. This was due to a type mismatch between the boolean array and the DataFrame structure.To resolve the issue, I converted the DataFrame to a NumPy array which ensured proper application of boolean indexing (e.g., data[y_kmeans == 0]), as NumPy arrays handle boolean indexing more effectively than DataFrames in this context.

## Key Learnings from the Project
Understanding Clustering Algorithms: Gained insights into clustering techniques, particularly k-means and hierarchical clustering, to segment customers based on attributes like spending score, annual income, and age.

Clustering Evaluation: Learned to assess the effectiveness of clustering methods using the Elbow Method for k-means and Dendrograms for hierarchical clustering, helping determine the optimal number of clusters.


Data Visualization: Enhanced skills in visualizing data through scatter plots and dendrograms, crucial for interpreting clusters and explaining customer segments in a business-relevant manner.

Troubleshooting Data Issues: Improved troubleshooting skills in handling data type mismatches and optimizing clustering performance using tools like NumPy and Pandas.


### Model Implementation and Insights
The project successfully provides a strategic advantage by segmenting the customer base into actionable groups, enabling targeted marketing approaches that significantly improve customer interactions and business outcomes.


#### KMeans Clustering (Spending Score & Annual Income)
The KMeans model segmented customers into five distinct groups based on their spending behavior and income levels. Cluster 1 includes moderate spenders with average income, who may be encouraged to spend more through personalized offers. Cluster 2 consists of high-income, high-spending customers who would benefit from loyalty programs and exclusive promotions. Cluster 3 involves high spenders with low income, suitable for cost-effective deals. Cluster 4 includes high-income individuals who are conservative in their spending, where targeted engagement with high-value products could increase their expenditure. Cluster 5 represents low-income, low spenders who might be motivated through budget-friendly options and payment flexibility.

#### Hierarchical Clustering (Spending Score & Age)
Hierarchical clustering revealed two main groups based on age and spending. Cluster 1, spanning all age groups, includes low spenders who could be targeted with product improvements and customized marketing to enhance spending. Cluster 2, primarily younger, high-spending customers, should be engaged with youth-oriented products, digital marketing, and community programs that align with their preferences.

### Recommendations
The strategy should focus on retaining high spenders through tailored loyalty and premium services while engaging moderate and conservative spenders with personalized marketing and exclusive offers. For budget-conscious customers, introducing installment plans and budget-friendly products can help elevate their spending levels. By leveraging insights from these clustering models, businesses can develop targeted marketing strategies that effectively address the unique needs and preferences of each customer segment, leading to improved engagement and increased profitability.


