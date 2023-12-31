# Predict Customer Personality to Boost Marketing Campaign by Using Machine Learning
# Problem Statement 
The use of the internet and advances in technology provide many opportunities for business people to achieve success. All these conveniences are certainly accompanied by various challenges and tight competition. The need for a more effective and targeted marketing campaign strategy is the key to business success. Traditional marketing approaches often use broad segmentation that fails to capture the unique characteristics and preferences of each customer. As a result of ineffective marketing campaigns, wastage of resources and low conversion rates. The purpose of the research is to utilize machine learning techniques to predict customer personality characteristics by using information to improve marketing campaigns. By analyzing various data such as customer demographic data, online activities, calculating the coversion rate of each category for the purpose of developing an accurate predictive model.

**Metrics**
- Convertion rate

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

![3](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/e7fd8bc4-2042-4ef9-975e-54a804f1912f)

![Education](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/d59813a0-71e3-46a7-a027-2048e60d2669)  ![Marital Status](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/6d98e2a3-2576-4891-a6e1-27463927bbf6)

![4](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/b988b743-41f2-4bf4-b24e-c82dbebb1fe2)



## Riset

Determining customer segments with the K-Means Cluster concept, using the elbow algorithm to produce optimal K values. Then evaluate the K value with the Silhoutte Score.
<br>

*The following are the results of the elbow method:* 
<br>
![Elbow](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/d9c7fee1-7ac1-4809-877b-7cb4156176ae)


*Here are the results of the silhouette score evaluation:* <br>
![1](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/50872d2a-d030-4903-8dfb-7f8338b857c0)


<br>

*Here are the results visualization of the PCA:* 

![2](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/eba6d2eb-f64c-4ec2-85ca-39abb230a489)


## Marketing Retargeting

*Here result income per cluster, revenue product per cluster, Business Ecosystem and Marketing,Number Campaign by Cluster, Traffic campaingn per Month:* <br>


![6](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/23bb70c7-2299-4dd4-942d-46436a7a7002)  ![9](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/2cc8ff2a-15b2-447c-a2d2-41983d9eb91c)

![11](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/4282fcdb-134a-4d89-b004-5fec449d77d1)   ![10](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/e7061d88-0310-44c2-ad80-a1af90af8b1e)



![7](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/f36a077f-a127-4491-af6a-8601268a0172)   ![13](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/9e514da2-c793-4710-bf2b-bbeec135377c)


![14](https://github.com/NurulIlahiHusnah/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/125198828/d18673dd-92ef-45df-8381-8e0e90581af5)

# Summary
The sample obtained from the results of the K-Means algorithm is 3 clusters, namely:
1. High Spender (Cluster 2) : 
    - high income
    - high response
    - education is dominated by Bachelor's degrees but there are no high school graduates
    - Meat and coke products sell best as a whole cluster, this cluster has the best product sellers
    - The most frequently visited campaign is campaign 5
    - The highest business ecosystem is in shops, catalogs and the web 
2. Medium Spender (Cluster 0)
    - medium income
    - medium response
    - education is dominated by Bachelor's degrees but there are very few high school graduates.
    - Meat and coke products sell best as a whole cluster, this cluster has the second best product seller
    - The most frequently visited campaign is campaign 4
    - The highest business ecosystem is in shops, web and purchase deals
3. Risk Of Churn Spender (Cluster 1)
    - low income
    - low response
    - education is dominated by S1, all graduates are there.
    - The product seller is very low
    - The most frequently visited campaign is campaign 3
    - The highest business ecosystem is in shops, web and purchase deals

# Business Recommendations <br>
With the above results for business recommendations that can be used:

1.  Focus on campaigns that have a high impact and continue to improve the quality of these campaigns.
2. Rearrange the focus of the targets to be targeted to suit the campaign concept.
3. Improvements to the overall business ecosystem to increase the level of customer confidence in carrying out transactions both offline and online.


## 🔗 Links
![tableau](https://img.shields.io/badge/tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)https://public.tableau.com/app/profile/nurul.ilahi.husnah/viz/Boost_campaign/Dashboard1

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nurul-ilahi-husnah27/)

