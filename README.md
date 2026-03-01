# Olist-E-Commerce-Data-Analysis

📄 Dataset Overview — Brazilian E-Commerce Public Dataset by Olist

Source:
This dataset is publicly available on Kaggle at:
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce?select=olist_order_reviews_dataset.csv

It contains real transactional data from Olist Store, a large multi-seller marketplace in Brazil, with over 100,000 orders placed between 2016 and 2018.

📁 Files / Tables Included

The dataset consists of 9 CSV files, each representing a different dimension of the e-commerce business.

1. olist_customers_dataset.csv

Stores customer details (customer IDs, location).
Used to link orders to unique customers.

2. olist_geolocation_dataset.csv

Contains geographic information (zip codes with latitude/longitude).
Useful for regional analysis and mapping.

3. olist_order_items_dataset.csv

Details products in each order:

order_id

product_id

seller_id

Item price and freight value.
Useful for revenue and item-level analysis.

4. olist_order_payments_dataset.csv

Records payment methods and values for orders.
Includes multiple payment installments per order.

5. olist_order_reviews_dataset.csv

Contains customer reviews and satisfaction scores for orders.
Includes timestamps of review submission.

6. olist_orders_dataset.csv

Core order table with:

Order status (delivered, cancelled, etc.)

Various timestamps (purchase, delivery, approval).
This is the primary fact table connecting to most others.

7. olist_products_dataset.csv

Product catalog information:

product_id

category

product attributes.
Useful to analyze product-level performance.

8. olist_sellers_dataset.csv

Seller profiles including location.
Used to analyze seller performance and regional dynamics.

9. product_category_name_translation.csv

Translates product category names from Portuguese to English.
Useful for making product categories understandable during reporting and analysis.
