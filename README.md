# EDA_Team_FP
<h1>Project title : Churn Prediction for E-Commerce Customers</h1>

<h2>Project Overview :</h2>
<p align = 'justify'>
As a data science team, our goal is to predict customer churn in an e-commerce setting and provide recommendations to enhance engagement and reduce the churn rate. Customer churn is a major challenge in the e-commerce industry and can have a significant impact on the company's revenue. By using machine learning techniques, we aim to identify the factors that contribute to customer churn and develop a model to accurately predict which customers are likely to churn.
</p>
<h2>Role :</h2>
<p align = 'justify'>
We will be analyzing customer data from the e-commerce platform, including demographic information, customer behavior, and other relevant features. Our goal is to find the key drivers of customer churn and develop a predictive model that takes these factors into account.
</p>
<h2>Metrics :</h2>
<p align = 'justify'>
To evaluate the success of our model, we will be using two key metrics: customer churn rate and customer satisfaction score. The churn rate will indicate the percentage of customers who have stopped using the platform, while the satisfaction score will reflect the level of customer satisfaction with the platform. By reducing the churn rate and improving the satisfaction score, we aim to increase customer retention and ultimately drive growth for the e-commerce platform.
</p>
<h2>Outcome :</h2>
<p align = 'justify'>
The outcome of this project will be a machine learning model that can accurately predict customer churn and provide recommendations for enhancing customer engagement. The model will be validated using the metrics of customer churn rate and customer satisfaction score, and its results will be used to inform decisions and strategies aimed at reducing customer churn and improving customer satisfaction. By using data-driven insights, we aim to help the e-commerce platform improve its customer retention and drive growth for the business.
</p>
<h2>Exploratory Data Analysis</h2>
<p align = 'justify'>
<ul>Statistic Descriptive
    <li>The data has 20 columns.</li>
    <li>There are three columns with inappropriate data types, namely Churn, CityTier and Complain.</li>
    <li>Some variations of the column contents appear to be duplicated, using different values for the same purpose.</li>
    <li>There is a different number of data counts indicating a missing value in columns such as Tenure, WarehouseToHome, HourSpendOnApp, OrderAmountHikeFromlastYear, CouponUsed, OrderCount, DaySinceLastOrder and CashbackAmount. </li>
    <li>There is a suspicious value in the WarehouseToHome column with a max value of 127 with an average value of 15.64. NumberOfAddress with a Max value of 22 (this value is too large) with an average of 4. </li>
    <li>However, there is no data that has a suspicious distance between the mean and median.</li>
</ul>
<h2>Insight and Recommendations:</h2>
<ul>Business Insight:
    <li>. Mobile optimization is critical for the business's success, given that the preferred login device is the mobile phone. The company should prioritize making its platform user-friendly and easy to navigate for mobile users to ensure a positive user experience and increase customer retention. The next step is focusing to developing mobile-specific features such as push notifications, personalized recommendations, and easy-to-use checkout systems to increase customer engagement and reduce churn.</li>
    <li>The popularity of debit and credit card payments suggests that e-commerce businesses should prioritize implementing secure and easy-to-use payment systems to cater to their customers' preferred payment methods.</li>
    <li>Given that married men users dominate, the business may want to develop targeted marketing campaigns and promotions to appeal to this demographic.</li>
    <li>The fact that the top product categories are mobile phones and laptops/accessories indicates that the business should focus on expanding its offerings in these categories to meet the high demand. </li>
    <li>Since mobile phones are a top-selling category, the business should focus on offering a range of mobile phone accessories to encourage customers to purchase complementary products.</li>
    <li>The high demand for laptops and accessories suggests that the business should focus on offering a range of high-quality and affordable laptop models to cater to different customer needs and budgets.</li>
    <li>With an average of 28% of complain for each product category, the company should focus on improving the quality of those products or providing additional product information to reduce the likelihood of customer complaints. This also be an opportunity for e-commerce businesses to demonstrate their commitment to customer satisfaction by offering refunds, exchanges, or other compensatory measures to affected customers.</li>
    <li>Customers who have not made a purchase in a long time may be more likely to churn in the future. This insight suggests that e-commerce businesses should focus on developing targeted marketing campaigns to re-engage dormant customers and encourage repeat purchases.</li>
    <li>CityTier 3 has a higher churn rate compared to CityTier 1. There are several possibilities that need to be explored further; customer in CityTier 3 may have lower purchasing power, limited access to high-speed internet or face other logistical challenges in accessing e-commerce platforms that leading to a higher likehood of churn, different preferences and expectations, lower trust in e-commerce platform.</li>
</ul>
<ul>Business Recommendation:
    <li>For mobile optimization, the company should invest in a responsive website design that provides a seamless user experience across all devices. They should also consider developing mobile-specific features such as push notifications, personalized recommendations, and easy-to-use checkout systems.</li>
    <li>To cater to customers preferred payment methods, the e-commerce business should implement secure and user-friendly payment systems that support debit and credit card payments.</li>
    <li>The business should develop targeted marketing campaigns and promotions to appeal to the dominant demographic of married men users. The campaigns should highlight products that are popular with this demographic.</li>
    <li>The business should prioritize expanding its offerings in the top product categories, such as mobile phones and laptops/accessories, to meet high demand.</li>
    <li>The company should focus on offering a range of mobile phone accessories to encourage customers to purchase complementary products. This strategy can help increase customer loyalty and retention.</li>
    <li>The business should focus on offering a range of high-quality and affordable laptop models to cater to different customer needs and budgets. This strategy can help increase customer satisfaction and retention.</li>
    <li>The company should focus on improving the quality of the products with high complaint rates or providing additional product information to reduce the likelihood of customer complaints. This strategy can help increase customer satisfaction and reduce churn.</li>
    <li>The e-commerce business should focus on developing targeted marketing campaigns to re-engage dormant customers and encourage repeat purchases. The campaigns should offer incentives such as exclusive discounts or free shipping to encourage customers to make a purchase.</li>
    <li>To address the high churn rate in CityTier 3, the e-commerce business should conduct further research to understand the underlying reasons for the churn. The research should focus on identifying any challenges that customers in CityTier 3 may face when accessing the platform and make necessary changes to improve the user experience. Additionally, the business should consider offering more affordable products or payment options to address budget constraints and building trust with customers in these areas by improving customer service and offering transparent pricing.</li>
</ul>