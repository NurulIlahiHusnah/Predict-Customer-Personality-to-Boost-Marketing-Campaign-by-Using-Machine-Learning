# Predict Customer Personality to Boost Marketing Campaign by Using Machine Learning
# Problem Statement 
The use of the internet and advances in technology provide many opportunities for business people to achieve success. All these conveniences are certainly accompanied by various challenges and tight competition. The need for a more effective and targeted marketing campaign strategy is the key to business success. Traditional marketing approaches often use broad segmentation that fails to capture the unique characteristics and preferences of each customer. As a result of ineffective marketing campaigns, wastage of resources and low conversion rates. The purpose of the research is to utilize machine learning techniques to predict customer personality characteristics by using information to improve marketing campaigns. By analyzing various data such as customer demographic data, online activities, calculating the coversion rate of each category for the purpose of developing an accurate predictive model.

Give convertion rate :

![Capture](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/d583da2e-d1e1-40b1-8901-74db1b62d9ef)



**Why is Analysis important?**
<br>The conversion rate value reflects the effectiveness of the campaign in reaching the target audience and enhances the effectiveness of the Call to Action (CTA), transforming prospective customers into potential customers, ultimately contributing to an increase in the company's revenue.<br>

**What will be changed if there are results?**
<br>What will be changed is the marketing strategy to make it more effective and efficient. Through marketing retargeting of cluster segments that are suitable for retargeting.



**Data and Assumptions**
- Consists of 2046 rows and 32 columns
- Dataset comes from 2012 – 2014 (2 years)
- The dataset contains customer demographic data, campaign traffic data, revenue from each product, and purchasing channels. <br>

## Early Insight from the data
1. *Marketing Retargeting* 

![Education](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/d59813a0-71e3-46a7-a027-2048e60d2669)

![Income per group age](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/c52feb34-ea52-4cc2-a2c8-59247a4829aa)

![Marital Status](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/6d98e2a3-2576-4891-a6e1-27463927bbf6)


## Riset
Segmenting by applying the k-means clustering algorithm to existing datasets, and choosing the right number of clusters by looking at the elbow method, and evaluating using silhouette scores.
<br>
*The following are the results of the elbow method evaluation:* 
<br>
![Elbow](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/d9c7fee1-7ac1-4809-877b-7cb4156176ae)


*Here are the results of the silhouette score evaluation:* <br>
![Alt text](image-1.png)

<br>

![2](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/eba6d2eb-f64c-4ec2-85ca-39abb230a489)



*Here result income per cluster, revenue product per cluster, Business Ecosystem and Marketing,Number Campaign by Cluster, Traffic campaingn per Month:* <br>


![Preferred Product](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/f4addadf-39fd-465a-8a5a-db88ffcd603f)

![trafic campaign](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/4e1fcbd4-1794-49e9-973a-017eb08b9280)

![Number Campaign by Cluster](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/8bba1a17-f96b-446e-a370-82b5890907c7)

![Business Ecosystem and Marketing](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/362e4503-a90c-4277-b873-62704e2e3e62)





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


## 🔗 Links
![tableau](https://img.shields.io/badge/tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)https://public.tableau.com/app/profile/nurul.ilahi.husnah/viz/Boost_campaign/Dashboard1

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nurul-ilahi-husnah27/)
