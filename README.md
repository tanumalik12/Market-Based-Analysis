# Market-Based-Analysis

In this project, I will be implementing Market Basket Analysis, a data mining technique used to identify associations and patterns in customers' purchasing behavior. By analyzing transactional data, we aim to uncover relationships between products frequently bought together, which can provide valuable insights for businesses, such as cross-selling opportunities, optimizing product placement, and improving marketing strategies.

![image](https://github.com/tanumalik12/Market-Based-Analysis/assets/128899444/c95b7ebf-5ba0-445d-a4bf-27f76b88014a)


**Dataset Used:**

For this analysis, a transaction dataset containing records of customer purchases was utilized. The dataset includes information about the items purchased in each transaction.

**STEPS**

        Here is the basic suggested skeleton for my data analytics repo:
        
        ├── data loading
        │ 
        ├── Assignment-1_Data.xlsx 
        │
        ├── cleanedData
        │
        |── Cleaned Assignment-1_Data.xlsx
        |
        ├── Data acquisition
        |
        ├── Data preprocessing 
        |
        ├── Data analysis 
        |
        ├── Association Rule Mining
        |
        ├── Rule Interpretation
        |
        ├── Visualization
        |
        ├── README.md




**Feature Descriptions**

BillNO : A 6 digit unique number assigned to each Transaction

Itemname : Name of the item purchased

Quantity : The quantity of each item being purchased

Date : Transcation Data

Price : Price of each Item

CustomerId: Unique Id of each customer

Country : The name of the country where each customer resides.        


# **RULES**

Let’s me explain the terms above,

Antecedents = Antecedents refer to the items or itemsets that appear before the arrow (->) in an association rule. They represent the items that are present in the transactions before a certain event or outcome.

Consequents = Consequents refer to the items or itemsets that appear after the arrow (->) in an association rule. They represent the items that are predicted or inferred to occur based on the presence of the antecedents.

Antecedent Support= Antecedent support is the proportion of transactions in the dataset that contain the antecedent items. It is calculated by dividing the number of transactions containing the antecedent by the total number of transactions.

Consequent Suppor= Consequent support is the proportion of transactions in the dataset that contain the consequent items. It is calculated by dividing the number of transactions containing the consequent by the total number of transactions.

Antecedent Support= Antecedent support is the proportion of transactions in the dataset that contain the antecedent items. It is calculated by dividing the number of transactions containing the antecedent by the total number of transactions.

Support= Support is the proportion of transactions in the dataset that contain both the antecedent and consequent items together. It is calculated by dividing the number of transactions containing both items by the total number of transactions.

Confidence=Confidence is the conditional probability of finding the consequent items in a transaction given that the antecedent items are present. It is calculated by dividing the support of the rule (transactions containing both antecedent and consequent) by the support of the antecedent. Confidence measures how often the rule is true.

Lift=Lift metric is used to detect uninteresting association rules to ease rule pruning. It assumes the occurrence of item A in a transaction is independent of the occurrence of item B if P(A ∪ B) = P(A)P(B), otherwise these two items are dependent and so correlated.

Lift(A → B) > 1 means that items are positively correlated and occurrence of one positively affects the occurrence of other</br>

Lift(A → B) =1 means that there is no correlation</br>

Lift(A → B) < 1 means that items are negatively correlated and occurrence of one negatively affects the occurrence of other

Leverage= Leverage is the measure of the difference between having items A&B in a transaction together and having item A and item B as they were independent.

Conviction=Conviction metric is used to measure how much a consequent depends on an antecedent.Conviction value ranges from 0 to infinity.If the conviction value is high, this means that the consequent is highly dependent on the antecedent.


**Recommendation Based on Rules Created:**

People buy snakesbox and plasters for them mostly together

People buy lunchbox and snakebox together</br>

Placing this item together can increase the salse


People same color paper plates , cups and napkins together

People buy lunchbox and snakebox together

People buy snakesbox and plasters for them mostly together


**SUMMARY**

The market basket analysis conducted on the transaction dataset aimed to uncover relationships between products frequently purchased together. By transforming the data and applying the Apriori algorithm, we identified frequent itemsets and generated association rules. The interpretation of these rules offers valuable insights into customer preferences and purchasing patterns. The visualization of support and confidence values using a heatmap enhances the understanding of the strength of these associations. In summary, market basket analysis serves as a powerful tool for businesses to optimize product recommendations, cross-selling strategies, and overall customer satisfaction.
Placing this item together can increase the salse
