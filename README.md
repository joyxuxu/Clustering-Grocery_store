# Clustering-Grocery_store

**Goal**

Company XYZ is an online grocery store which has a lot of data about user purchase history. Therefore, they would like to put the data into use! Look at user purchase history and create categories of items that are likely to be bought together and, therefore, should belong to the same section(basically cluster the items).


**Challenges:**
- Customer who bought the most items overall in her lifetime and for each item, the customer who bought that product the most
- Cluster items based on user co-purchase history. That is, create clusters of products that have the highest probability of being bought together.


**Data**
The data contains two tables:
- "item_to_id" - for each item, it gives the corresponding id
- "purchase_history" - for each user purchase, the items bought


**Scripts Description**


1. **preparing_data.ipynb** (prepares the dataframe and saves it to *prepared_purchased_history.csv* in order to accomplish task1 and task2)
2. **challenge_1.ipynb** shows the customer who has purchased max. number of items overall (**269335**) and also list of customers who has purchased each item max. number of times(results are saved to *each_item_max_purchase_customer_id.csv*).
3. **challenge_2.ipynb** contains the modelling of kmeans clustering algorithm and the results are saved to *clustered_dataframe.csv*.
