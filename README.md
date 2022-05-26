# Marketing-Campaign
**Overview**

Customer Personality Analysis is a detailed analysis of a company’s ideal customers.
It helps a business to better understand its customers and makes it easier for them to
modify products according to the specific needs, behaviors and concerns of different
types of customers. Customer personality analysis helps a business to modify its
product based on its target customers from different types of customer segments. For
example, instead of spending money to market a new product to every customer in the
company’s database, a company can analyze which customer segment is most likely
to buy the product and then market the product only on that particular segment.
The main objective here is -
1. What people say about your product: what gives customers’ attitude towards the
product.
2. What people do: which reveals what people are doing rather than what they are
saying about your product.

**Dataset**

The dataset you can get through this link https://raw.githubusercontent.com/amankharwal/Website-data/master/marketing_campaign.csv

**Approach**

It can be seen from the data and the problem statement that it is Unsupervised learning, tried all the necessary classical machine learning tasks such as Data Cleaning, Feature Engineering, Model building. Used K-means clustering algorithm to identify a pattern in the data. 

**Result**
1. As the income of cluster 1 is more than cluster 0, former is more likely to spend more than the other. MntWines is the most consumed product in the product category, then meat products. Therefore it can said that customers are more likely to buy Wines than the other products. 
2. Both  customers spend minimum on fruits than any other product.
Finally the product buying behaviour of the customers mostly depend on the Income of the customer.
3. Cluster 0 customers like to buy from web visits more ,also Catalog purchases are least prefered for this cluster.
4. Cluster 1 customers like to go to store and purchase a product, also they don't like to buy through deals.

**Technologies Used**

Pandas

Google Colab Notebook

Matplotlib

Sckit-Learn
