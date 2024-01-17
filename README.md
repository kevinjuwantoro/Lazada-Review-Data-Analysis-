# Lazada-Review-Data-Analysis-
**Analyze negative customer reviews on the Lazada platform** to understand the prevalent issues and root causes impacting product dissatisfaction. Utilizing the columns such as reviewContent and reviewTitle, employ Natural Language Processing (NLP) techniques to identify common themes and keywords in negative reviews. 

Explore the distribution of negative reviews across product categories (category_x) and brands (brandName), while examining factors such as product pricing (price), delivery times (retrievedDate_x), and review ratings (rating) to uncover the contributors to customer dissatisfaction. 

Identify specific keywords in negative reviews, prioritize areas for improvement based on customer engagement metrics (likeCount, upVotes, downVotes, helpful), and consider additional factors such as total reviews (totalReviews), relevance scores (relevanceScore), purchase dates (boughtDate), customer types (clientType), and temporal trends (retrievedDate_y) to enhance the overall product quality, customer satisfaction, and user experience on the Lazada platform.

## Background
<img src = 'https://www.bca.co.id/-/media/Feature/Promo/Page/2023/12/20231204-lazada-bann.JPG?v=1'>
Lazada is an international e-commerce company and one of the largest e-commerce operators in Southeast Asia. It was founded in 2012 by Maximilian Bittner with the intention of establishing an Amazon-like business model in the region. Lazada operates in six countries: Indonesia, Malaysia, the Philippines, Singapore, Thailand, and Vietnam. It offers a wide range of products across various categories, such as fashion, electronics, home and living, mother and baby, and health and beauty. It also has a virtual mall called LazMall, where consumers can shop from leading international and local brands.

Lazada has a marketplace platform that allows third-party retailers to sell their products on its website and mobile apps. It also has a cross-border business that features homegrown brands and sellers from markets such as China, Hong Kong, Korea, Japan, the United States, and Europe. Lazada provides a full suite of services to its sellers, such as secure payment options, customer care support, marketing analytics, and logistics network.

Lazada is backed by Alibaba Group, which acquired a controlling stake in the company in 2016. Alibaba’s technology infrastructure and expertise have helped Lazada to enhance its customer experience, expand its product assortment, and improve its operational efficiency. Lazada aims to serve 300 million customers by 2030 and become the leading online shopping and selling destination in Southeast Asia.

With its market potential, as a Data Analyst we could identify **patterns and trends** in sales volume and product preferences across different industries and customer segments. Also, we could explore other **companies buying behaviors** including purchase frequency, preferred products, and geographic distribution of customers especially in SaaS sales.

### Business Problem Statements
<img src = 'https://25174313.fs1.hubspotusercontent-eu1.net/hub/25174313/hubfs/LAZADA_WALLET_ACTIVATION.png?width=639&height=467&name=LAZADA_WALLET_ACTIVATION.png'>

1. What are the common themes or issues mentioned in negative customer reviews?

2. Are there specific product categories or brands consistently receiving negative feedback?

3. How do factors such as product pricing, delivery issues, or customer service contribute to negative reviews?

4. Can we identify patterns in customer complaints and use them to prioritize improvements?

## **Column Description**

**Here is the Original Dataset:**

## **Column Description**

| Column           | Description                                       |
|------------------|---------------------------------------------------|
| `itemId`         | Unique identifier for each item                   |
| `category_x`     | Product category identifier                       |
| `name_x`         | Identifier for the product name                    |
| `brandName`      | Brand name of the product                         |
| `url`            | URL for the product on Lazada                      |
| `price`          | Price of the product                              |
| `averageRating`  | Average rating of the product                      |
| `totalReviews`   | Total number of reviews for the product           |
| `retrievedDate_x`| Date of data retrieval for product information    |
| `category_y`     | Product category identifier in reviews            |
| `name_y`         | Identifier for the product name in reviews         |
| `rating`         | Rating given in the review                        |
| `originalRating` | Original rating given in the review               |
| `reviewTitle`    | Title of the review                               |
| `reviewContent`  | Content of the review                             |
| `likeCount`      | Number of likes for the review                    |
| `upVotes`        | Number of upvotes for the review                  |
| `downVotes`      | Number of downvotes for the review                |
| `helpful`        | Indicates if the review was marked as helpful     |
| `relevanceScore` | Relevance score of the review                     |
| `boughtDate`     | Date of purchase of the product                   |
| `clientType`     | Type of client (customer)                         |
| `retrievedDate_y`| Date of data retrieval for reviews                |

## Conclusion
<img src = 'https://img.alicdn.com/imgextra/i2/O1CN01NVg7CY28nyeFAwvXA_!!6000000007978-2-tps-780-439.png'>

1. The products with high upvotes tend to be branded and well-known, such as Sharp, Samsung, and LG, while the products with low upvotes tend to be generic and unbranded, such as COOCAA and Midea.

2. The products with high downvotes usually have issues with their appearance and color, which could indicate a mismatch between the product description and the actual product delivered.

3. The products with moderate upvotes and downvotes are mostly home appliances that are functional and dependable, but not very attractive or innovative.

## **Conclusion for CooCaa Products who have the most not recommended or negative reviews**

1. Coocaa products have the most negative sentiment, upvotes, downvotes, and like counts among the top 10 products on Lazada, according to the heatmap. This indicates that Coocaa products are not well-received by the customers, and have a low quality and reputation.

2. The main reasons for the negative feedback are the poor packaging, handling, and transportation of the products, which result in damage, breakage, or cracking of the screens. Additionally, the products are defective, faulty, or mismatched, and do not function properly or meet the customers’ expectations. Furthermore, the return or refund process is complicated, time-consuming, or costly, and the delivery service is problematic.

3. The main impacts of the negative feedback are the customer dissatisfaction, frustration, anger, disappointment, and loss of trust. These could affect the sales, revenue, and market share of Lazada and Coocaa, as well as their brand image and loyalty. Moreover, the negative feedback could also influence the ratings, reviews, and relevance scores of the products, which could affect their visibility and attractiveness on the platform

### Recommendation

1. To improve their customer satisfaction and reputation, Lazada should monitor and review the products that receive high downvotes, especially in the appearance and color category, and ensure that they meet the quality standards and expectations of the customers.

2. To increase their sales and revenue, Lazada should promote and highlight the products that receive high upvotes, especially in the categories that are relevant and appealing to the customers, such as performance and features.

3. To diversify their product portfolio and attract more customers, Lazada should introduce and showcase more products that are creative and unique, such as smart devices, gaming consoles, and wearable gadgets.

4. To improve their customer satisfaction and reputation, Lazada  should improve their packaging, handling, and transportation of the products, and ensure that they are protected from damage, breakage, or cracking. They should also check the quality and functionality of the products before shipment, and provide warranty books and VIP cards to the customers.

5. To resolve the customer complaints and issues, Lazada  should simplify and expedite their return or refund process, and provide clear and accurate information and communication to the customers. They should also address the problems with the delivery service, such as the charges for packing wood, or the delivery of the wrong products.

6. To increase their sales and revenue, Lazada  should update and enhance their product description, specification, and expectation, and avoid misleading or inaccurate information. They should also offer more incentives and discounts to the customers, such as free shipping, coupons, or vouchers.

## Authors

* **Hieremias Kevin Juwantoro** - *Initial work* - [https://github.com/kevinjuwantoro/Lazada-Review-Data-Analysis-)
