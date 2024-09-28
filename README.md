<p align="center">
    <img src="https://miro.medium.com/v2/resize:fit:1400/1*I2i-ujG_TUw5HsNN7v__4Q.png" alt="MasterHead"/>
</p>

# Rating-Product-Sorting-Reviews Analysis in Amazon

## 1. Business Problem

Accurately calculating post-sale product ratings is one of the most crucial issues in e-commerce. Addressing this ensures greater customer satisfaction, highlights products for sellers, and provides a smooth shopping experience for buyers. Another significant challenge is the correct ranking of product reviews. Misleading reviews can negatively impact product sales, resulting in both financial and customer losses. By solving these two issues, e-commerce sites and sellers can boost sales while customers can enjoy a hassle-free purchasing journey.

## 2. Dataset Story

This dataset contains Amazon product data, including various metadata and product categories. The dataset focuses on user ratings and reviews for the most reviewed product in the **Electronics** category.

### 2.1 Variables:
- **reviewerID**: Unique identifier for the reviewer.
- **asin**: Unique identifier for the product.
- **reviewerName**: Username of the reviewer.
- **helpful**: Degree of helpfulness of the review.
- **reviewText**: Detailed review text.
- **overall**: Overall rating given to the product.
- **summary**: Brief summary of the review.
- **unixReviewTime**: Timestamp of the review in Unix format.
- **reviewTime**: Human-readable timestamp of the review.
- **day_diff**: Number of days elapsed since the review.
- **helpful_yes**: Number of users who found the review helpful.
- **total_vote**: Total number of votes received by the review.

## 3. Objective

The primary objective of this project is to improve the accuracy of product rating calculations by leveraging recent reviews. Additionally, the project aims to rank product reviews to display the most relevant and helpful feedback on the product detail page. This will enhance customer satisfaction and product reliability by showing more meaningful reviews while mitigating the impact of misleading or low-quality reviews.

### Key Goals:
1. Develop an approach to calculate the weighted average rating that gives more importance to recent and relevant reviews.
2. Identify and rank the top 20 reviews based on helpfulness and recency to be featured on the product detail page.

## 4. Conclusion

By employing a data-driven approach to calculate product ratings based on recent reviews, e-commerce platforms can offer a more accurate reflection of customer sentiment. This helps in avoiding issues like outdated or misleading reviews dominating the ratings. Additionally, the ability to showcase the top 20 relevant reviews improves the customer experience, guiding potential buyers to more trustworthy and helpful feedback. These improvements not only boost customer trust but also support product sales and engagement for sellers.

