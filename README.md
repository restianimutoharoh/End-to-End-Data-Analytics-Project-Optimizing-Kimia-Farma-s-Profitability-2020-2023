# End-to-End Data Analytics Project: Optimizing Kimia Farma's Profitability 2020-2023

## Executive Summary

### Sales Metrics Year 2020-2023
**Insight** 
* Business performance is highly sensitive to external factors, such as the shift in consumer behavior to online purchasing during the pandemic.
* The company showed resilience with a significant increase in revenue in 2022, driven by high demand for healthcare products.
* The revenue decline in 2023 is due to internal weaknesses ("operational issues"), which require immediate improvement.
  
**Recommendation**
* Strengthen investments in e-commerce platforms and online sales channels to anticipate shifts in consumer behavior.
* Conduct in-depth analysis to identify and rectify root causes of operational issues that led to revenue decline in 2023.
* Continue to monitor healthcare demand trends and adjust product portfolio to maintain growth momentum.
* Develop contingency plans to deal with future volatility in market or economic conditions.

### Top 10 Provincial Branch Transactions
**Insight** 
* There is a strong correlation between population and transaction volume, with West Java dominating the market significantly.
* High market concentration in West Java could be a risk in case of volatility.
* Other provinces (North Sumatra, Central Java, East Java) show great regional market potential to be developed.
  
**Recommendation**
* Focus market expansion in provinces with large population to maximize market share.
* Diversify sales strategy to other provinces to reduce dependency on West Java.
* Conduct in-depth analysis of mid-ranked provinces to find new growth opportunities.
* Replicate successful strategies from West Java to other provinces to increase transaction volume.

### Top 10 Net Sales of Provincial Branches
**Insight** 
* Net Sales are highly concentrated in West Java, creating high revenue dependency.
* There is a strong correlation between the number of transactions and Net Sales.
* There is significant growth potential in other regional markets such as North Sumatra and Central Java.
  
**Recommendation**
* Diversify sales to other provinces to reduce dependency on West Java.
* Analyze key success factors in West Java and replicate to other potential markets.
* Increase number of transactions and net sales in strategic provinces such as North Sumatra and Central Java.

### Top 5 Highest Branch Ratings VS. Top 5 Lowest Transaction Ratings
**Insight** 
* There is a significant gap between high branch quality ratings and low transaction ratings.
* This pattern occurs across many branches, indicating a systemic issue.
* These branches have great untapped potential to increase transactions.
  
**Recommendation**
* Conduct a deep analysis to find the root cause of the low transaction ratings.
* Develop a targeted local marketing strategy to increase traffic and conversions.
* Provide staff with training on more proactive sales techniques.

### Gross Profit by Province 
**Insight** 
* West Java dominates profit with Rp 26.94 billion, more than 4 times that of the second province.
* There is a strong correlation between transaction value and profit; the province with the highest transactions also has the highest profit.
* There is a large profit gap between regions, from the highest (Rp 26.94 billion) to the lowest (Rp 572.94 million).
  
**Recommendation**
* Develop an expansion strategy in leading provinces besides West Java to reduce dependency.
* Analyze obstacles in low-performing markets (such as West Papua) to find expansion opportunities.
* Replicate successful strategies from West Java to other provinces to increase profit.


## Kimia Farma 
*Kimia Farma* is a leading pharmaceutical company in Indonesia engaged in the production, distribution, and sale of pharmaceuticals and other health products. The company also provides integrated healthcare services, including pharmacies, clinics and clinical laboratories. Kimia Farma has been part of Indonesia's public health development for more than 100 years. Kimia Farma was established in 1817 by the Dutch East Indies Government under the name NV Chemicalien Handle Rathkamp & Co, making it the first pharmaceutical company in Indonesia.

**Project Objective**

This project aims to evaluate Kimia Farma's business profitability in 2020-2023. Through data analysis using SQL and interactive visualization, we will identify key trends, quantify performance metrics, and provide strategic insights to support better business decision making.

**Data Source** 
* Dataset Overview: This project uses the Kimia Farma product sales transaction dataset with
with the following characteristics:
* Data Structure: Consists of four relational tables:
kf_final_trancation (8 columns): Records detailed information about product transactions such as, transaction_id, date, branch_id, customer_name, product_id, price, discount_percentage and rating.
kf_kantor_cabang table (6 columns): Contains information about branch_id, branch_category, branch_name, city, province, and rating.
kf_inventory (5 columns): Has information about inventory, branch_id, product_id, product_name and opname_stock. 
kf_product table (4 columns): Records product information such as product_id, product_name, product_category and price. 
* Data Time Range: Data is available for 2020-2023.

## SQL Query Analysis 

*Query* 

[SQL_Query_Kimia_Farma_Business_Performance.txt](https://github.com/restianimutoharoh/End-to-End-Data-Analytics-Project-Optimizing-Kimia-Farma-s-Profitability-2020-2023/blob/master/SQL_Query_Kimia_Farma_Business_Performance.txt)

**Key Insight to Profitability** 

*Margin Structure* 
* Key Insight
Profitability (Gross Profit) is highly sensitive to high Transaction Sales Prices, especially transactions above $500,000 (because they receive a 30% margin).
* Strategic Implications
Focus on Value-Selling. Increase Average Transaction Value (ATV) by promoting high-value products or services, or by cross-selling/up-selling on every transaction.

*Geography* 
* Key Insight
The province of West Java (Ciamis, Bekasi, Karawang) emerged as the main center of profitability, contributing the majority of the highest gross profit transactions in the data sample.
* Strategic Implications
Resource Allocation. Prioritize investments in marketing, inventory, and staff training at branches in West Java to maximize profit potential.

*Products* 
* Key Insight
High-profit transactions are dominated by the specialist medicine category (e.g., psycholeptics, anti-inflammatories).    
* Strategic Implications
Strategic Inventory Management. Ensure adequate availability of specialist/high-margin products in strategic locations to prevent lost sales potential.

*Service Quality* 
* Key Insight
Branch and Transaction ratings are generally good (4.0 to 4.8), indicating that service quality supports high-value transactions.     
* Strategic Implications
Maintain Standards. High service quality must be maintained, as this can be a determining factor for customers to conduct large-value transactions.


## Kimia Farma Performance Analysis

![alt text](https://github.com/restianimutoharoh/End-to-End-Data-Analytics-Project-Optimizing-Kimia-Farma-s-Profitability-2020-2023/blob/master/Sales%20Metrics%20year%202020-2023.png?raw=true)

**Insight** 
* *Sensitivity to Consumer Shifts:* The significant decline in revenue from 2020 to 2021 indicates that business performance is heavily influenced by changes in consumer behavior triggered by external factors, such as the COVID-19 pandemic, where many consumers shifted to online purchases and reduced visits to physical stores.
* *Market Resilience & Post-Pandemic Opportunities:* The strong increase in revenue in 2022 indicates that Kimia Farma has highly desirable health products (high demand) and is able to capitalize on the momentum of the post-pandemic economic recovery.
* *Internal Vulnerabilities:* The decline in revenue in 2023, specifically due to "operational issues", indicates internal weaknesses that need to be addressed. This is in contrast to the decline at the beginning of the pandemic, which was caused by external factors.

![alt text](https://github.com/restianimutoharoh/End-to-End-Data-Analytics-Project-Optimizing-Kimia-Farma-s-Profitability-2020-2023/blob/master/Top%2010%20Provincial%20Branch%20Transactions.png?raw=true)

**Insight** 
* *Strong Correlation with Population:* The data shows a very strong correlation between a province's population and transaction volume. West Java, as the most populous province, dominates the total transactions significantly, with almost 4 times the value of the second-placed province.
* *Market Concentration:* There is a very large market concentration in one region (West Java). While this demonstrates the strength of dominance in a key market, too much reliance on one region can be a risk if that market experiences volatility.
* *Regional Market Potential:* The provinces in positions 2 to 4 (North Sumatra, Central Java, East Java) show substantial market potential. Although their transactions are far below those of West Java, their transaction values position them as important regional markets worth developing.

![alt text](https://github.com/restianimutoharoh/End-to-End-Data-Analytics-Project-Optimizing-Kimia-Farma-s-Profitability-2020-2023/blob/master/Top%2010%20Net%20Sales%20of%20Provincial%20Branches.png?raw=true)

**Insight** 
* *Extreme Market Dominance:* Nett Sales in West Java ($102.57B) dominate in the extreme, more than four times that of the second ranked province. This demonstrates the success of the business model in West Java, but also creates a very high revenue dependency on one region.
* *Transaction-Sales Correlation:* The data confirms that Nett Sales is directly proportional to the number of transactions. The province with the highest transactions (West Java) also has the highest net sales.
* *Growth Potential Outside Java:* Despite the dominance, the provinces ranked 2-4 (North Sumatra, Central Java, East Java) show significant regional market potential. The long distance from West Java indicates a great opportunity to increase net sales in these regions.

![alt text](https://github.com/restianimutoharoh/End-to-End-Data-Analytics-Project-Optimizing-Kimia-Farma-s-Profitability-2020-2023/blob/master/Top%205%20Highest%20Branch%20Ratings%20VS.%20Top%205%20Lowest%20Transaction%20Ratings.png?raw=true)

**Insight** 
* *Quality vs. Performance Gap:* There is a consistent gap between branch quality (which is rated high, with an average of 4.5 out of 5) and transaction performance (which is consistently at 3). This indicates that even though the quality of service or branch facilities is good, it has not successfully been converted into a significant increase in transaction volume or value.
* *Systemic Issue:* This pattern occurs across five different branches, indicating that the problem is not an isolated incident but is likely a systemic issue affecting several branches broadly.
* *Untapped Potential:* These branches have a strong foundation. Their already high quality is a significant asset. The challenge is to find a way to optimize this potential and drive more transactions.

![alt text](https://github.com/restianimutoharoh/End-to-End-Data-Analytics-Project-Optimizing-Kimia-Farma-s-Profitability-2020-2023/blob/master/GROSS%20PROFIT%20BY%20PROVINCE.png?raw=true)

**Insight** 
* *Centralized Profit Dominance:* West Java Province dominates profit significantly with a total profit of Rp 26.94 billion, which is more than 4 times that of the second-ranked province, North Sumatra (Rp 6.51 billion). This confirms that the high transaction volume in West Java is the main driver of the company's profit.
* *Strong Correlation Between Transactions and Profit:* The data shows a direct correlation between transaction value and profit. The three provinces with the highest transaction values (West Java with $198.72K, North Sumatra with $48.18K, and Central Java with $46.49K) are also the highest contributors to gross profit.
* *Regional Profit Disparity:* There is a very large profit gap between regions, from the highest profit in West Java (Rp 26.94 billion) to the lowest profit in West Papua (Rp 572.94 million). This indicates the presence of untapped market potential or operational issues in regions with low profit.
