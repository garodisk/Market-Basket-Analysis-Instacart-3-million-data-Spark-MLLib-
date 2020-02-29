# Market-Basket-Analysis-Instacart-3-million-data-Spark-MLLib-
Association mining for products using Spark and FP-Growth algorithm in Spark ( Databricks )

Here's the link to my blog on this project:

https://medium.com/@saketgarodia/market-basket-analysis-on-3-million-orders-from-instacart-using-spark-24cc6469a92e?source=friends_link&sk=ad580efa7c7697b731eb36dd2c33ad82

Supermarkets around the world are using data mining techniques to analyze the user buying pattern in order to make their business more efficient thereby increasing their business and fulfilling customer needs at the same time. One such application is determining which are the goods that a consumer tends to buy together and analyze the ‘if-then’ patterns to understand if a consumer buys A which are the B’s to recommend to the consumer. This helps them in placing the right products at the right aisle thereby helping the consumer recall their need. This helps the consumers to stock up their refrigerators and homes according to their needs and decreases their purchasing time at the same time.
In this project, I will use Instacart’s real dataset from Kaggle which contains data from 3 million grocery orders from 200,000 users. For each user, there are about 4–100 different orders based on how many times they have purchased from Instacart. Here’s the link to the dataset:
https://www.kaggle.com/c/instacart-market-basket-analysis/data
I will be showing the implementation on spark owing to the fact that it runs very fast on Databricks as it uses distributed in-process computing and takes very less time even on such a large dataset. Luckily we have the FP ( Frequent-Pattern Mining) library already on spark and thereby I will use that to understand the patterns. Let us start.
Note: Databricks provides users to use their community platform for free. So, feel free to replicate the code and see the magic of pattern mining.


