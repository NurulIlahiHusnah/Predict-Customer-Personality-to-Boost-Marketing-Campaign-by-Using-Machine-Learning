# Predict Customer Personality to Boost Marketing Campaign by Using Machine Learning
# Problem Statement 
The use of the internet and advances in technology provide many opportunities for business people to achieve success. All these conveniences are certainly accompanied by various challenges and tight competition. The need for a more effective and targeted marketing campaign strategy is the key to business success. Traditional marketing approaches often use broad segmentation that fails to capture the unique characteristics and preferences of each customer. As a result of ineffective marketing campaigns, wastage of resources and low conversion rates. The purpose of the research is to utilize machine learning techniques to predict customer personality characteristics by using information to improve marketing campaigns. By analyzing various data such as customer demographic data, online activities, calculating the coversion rate of each category for the purpose of developing an accurate predictive model.

Give convertion rate :

![Conversion Rate](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/5e146003-ddcf-45d3-bc67-923424e5eb3b)


**Why is Analysis important?**
<br>The conversion rate value reflects the effectiveness of the campaign in reaching the target audience and enhances the effectiveness of the Call to Action (CTA), transforming prospective customers into potential customers, ultimately contributing to an increase in the company's revenue.<br>

**What will be changed if there are results?**
<br>What will be changed is the marketing strategy to make it more effective and efficient. Through marketing retargeting of cluster segments that are suitable for retargeting.



**Data and Assumptions**
- Consists of 2046 rows and 32 columns
- Dataset comes from 2012 – 2014 (2 years)
- The dataset contains customer demographic data, campaign traffic data, revenue from each product, and purchasing channels. <br>

## Early Insight from the data
1. *Exploratory Data Analysis* (EDA)
- Education <br>
![Education](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/1ffbf450-1f68-42e5-ba73-e75a0fe25f5d)


![Income per group age](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/f5bcaf5f-28a8-49cf-a82a-6e6c1fcff071)

![Marital Status](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/bd5aeec5-6c37-432a-b82a-6aab7cddfcdc)

## Riset
Segmenting by applying the k-means clustering algorithm to existing datasets, and choosing the right number of clusters by looking at the elbow method, and evaluating using silhouette scores.
<br>
*The following are the results of the elbow method evaluation:* 
<br>
![Elbow](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/8f3be31b-36b6-4e63-8869-c1bcd5839072)


*Here are the results of the silhouette score evaluation:* <br>
![Silhouette](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/0089f160-cfd8-4243-a40b-994a3777059b)

<br>

*Here result income per cluster, revenue product per cluster, Business Ecosystem and Marketing,Number Campaign by Cluster, Traffic campaingn per Month:* <br>


![Preferred Product](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/f0f58607-fc0c-4b3d-8037-ef6e0d7a16e6)


![trafic campaign](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/64c989da-1bcb-484f-a21b-0a773e5521ca)

![Number Campaign by Cluster](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/be747eb4-71cf-4459-99da-d104d041b0d8)

![Business Ecosystem and Marketing](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/4e7e73f2-35b8-4a1c-a781-c4ed352f3a6f)



The sample obtained from the results of the K-Means algorithm is 3 clusters, namely:
1. High Spender
2. Medium Spender
3. Risk Of Churn Spender
<br>

# Business Recommendations <br>
With the above results for business recommendations that can be used:

1. Enhance the campaign in terms of concept, visualization, and other aspects to adjust deals purchases targeting the median spender and risk churn spender clusters.
2. In terms of the business ecosystem and marketing, among the four concepts mentioned above, there is a need for further improvement in deals purchases to continually strengthen the ecosystem. This can be achieved through offering promotions, shopping vouchers, free shipping, or other discounts to boost sales.
3. Conduct retargeting marketing and focus on growth in Clusters 1 and 2.
4. Make improvements for up-selling and cross-selling
5. Maintain customer retention rates, existing customers tend to earn more compared to new customers.
