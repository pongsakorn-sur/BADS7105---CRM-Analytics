# Customer Segmentation [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1SsqHH_gb9939e5DapckTBaNF6u04pcJI)
[![CLV Dashboard](https://img.shields.io/badge/-Python-blue)](https://github.com/pongsakorn-sur/BADS7105-CRM-Analytics/tree/main/02%20-%20Customer%20Segmentation)
[![CLV Dashboard](https://img.shields.io/badge/-Google%20Colab-blue)](https://github.com/pongsakorn-sur/BADS7105-CRM-Analytics/tree/main/02%20-%20Customer%20Segmentation)
[![CLV Dashboard](https://img.shields.io/badge/-K--Means-blue)](https://github.com/pongsakorn-sur/BADS7105-CRM-Analytics/tree/main/02%20-%20Customer%20Segmentation)




## 1. Import Dataset
The supermarket dataset are historical data of sales transactions from year 2006 to 2008 of 2 stores and 6100 customers. It contains total 956574 rows and 22 columns.  

**Note:** The dataset are imported to Drive for Google colaboratory.

## 2. Feature Engineering
Define the feature for clustering model.
- Total spend
- Total visit
- Total SKUs
- Customer life time(Days)
- Recency(Total days from last purchase)
- Average active weekly baskets(Frequency)
- Average active weekly spending(Monetary)
- Standard deviation of weekly baskets
- Average ticket size(Total spend/No. of baskets)
- Standard deviation of ticket size 
- Mean time between purchase
- Weekly purchase consistency(No. of week/customer lifetime)
- Top basket_dominant_mission
- Most visit day
- Least visit day
- Most visit shop hour
- Least visit shop hour

## 3. Customer Single View
Generate customer single view to prepare data for use in clustering model. The final features were selected total 13 features.

[![CSV DF](https://github.com/pongsakorn-sur/BADS7105-CRM-Analytics/blob/main/02%20-%20Customer%20Segmentation/Customer%20single%20view.png)](https://github.com/pongsakorn-sur/BADS7105-CRM-Analytics/blob/main/02%20-%20Customer%20Segmentation/Customer%20single%20view.png)

## 4. Model Performance
[![Model performance](https://github.com/pongsakorn-sur/BADS7105-CRM-Analytics/blob/main/02%20-%20Customer%20Segmentation/Model%20Performance.png)](https://github.com/pongsakorn-sur/BADS7105-CRM-Analytics/blob/main/02%20-%20Customer%20Segmentation/Model%20Performance.png)

## 5. KMeans Clustering
Create KMean model using pycaret and choosing K number of clusters = 6

[![Elbow](https://github.com/pongsakorn-sur/BADS7105-CRM-Analytics/blob/main/02%20-%20Customer%20Segmentation/Elbow.png)](https://github.com/pongsakorn-sur/BADS7105-CRM-Analytics/blob/main/02%20-%20Customer%20Segmentation/Elbow.png)
[![Silhouette](https://github.com/pongsakorn-sur/BADS7105-CRM-Analytics/blob/main/02%20-%20Customer%20Segmentation/silhouette.png)](https://github.com/pongsakorn-sur/BADS7105-CRM-Analytics/blob/main/02%20-%20Customer%20Segmentation/silhouette.png)
[![PCA](https://github.com/pongsakorn-sur/BADS7105-CRM-Analytics/blob/main/02%20-%20Customer%20Segmentation/PCA%20Plot.png)](https://github.com/pongsakorn-sur/BADS7105-CRM-Analytics/blob/main/02%20-%20Customer%20Segmentation/PCA%20Plot.png)

## 6. Interpret results and plan for actions
- Cluster 0 : Non frequent visitors
- Cluster 1 : The Star
- Cluster 2 : Visit once in a blue moon
- Cluster 3 : Potential Star
- Cluster 4 : Not worth pursuing
- Cluster 5 : Ignore them!!

[![Action](https://github.com/pongsakorn-sur/BADS7105-CRM-Analytics/blob/main/02%20-%20Customer%20Segmentation/Action.png)](https://github.com/pongsakorn-sur/BADS7105-CRM-Analytics/blob/main/02%20-%20Customer%20Segmentation/Action.png)
