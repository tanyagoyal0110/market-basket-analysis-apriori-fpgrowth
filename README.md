# Market Basket Analysis using Apriori and FP-Growth

## Overview
This project applies **association rule mining techniques** to discover meaningful patterns in transactional data. Market basket analysis is a fundamental task in **data mining and knowledge discovery**, aimed at identifying relationships between items that frequently occur together.

The project focuses on the **comparative evaluation** of two classical algorithms — **Apriori** and **FP-Growth** — with emphasis on interpretability, computational efficiency, and rule quality.

---

## Dataset
The project uses the **Groceries dataset**, which consists of real-world supermarket transaction records. Each transaction contains a set of purchased items, making the dataset suitable for frequent itemset mining and association rule discovery.

Although relatively clean and moderate in size, the dataset is widely used in academic contexts for demonstrating and evaluating association rule mining algorithms.

---

## Methodology
The workflow followed in this project includes:

1. Data cleaning and preprocessing  
2. Grouping items into transaction-level baskets  
3. Transaction encoding using one-hot representation  
4. Frequent itemset mining using:
   - Apriori
   - FP-Growth  
5. Association rule generation  
6. Rule evaluation using multiple interestingness measures  

---

## Evaluation Metrics
Association rules are evaluated using standard and advanced measures, including:

- **Support** – frequency of itemsets  
- **Confidence** – reliability of implication  
- **Lift** – strength of association beyond random chance  
- **Jaccard Index**  
- **Kulczynski Measure**  
- **Imbalance Ratio**

These metrics enable both quantitative comparison and qualitative interpretation of discovered patterns.

---

## Results and Discussion
- FP-Growth demonstrated improved computational efficiency compared to Apriori  
- High-lift rules revealed strong associations between frequently co-occurring items  
- Comparative analysis highlighted trade-offs between algorithm complexity, scalability, and interpretability  

The results emphasize the importance of algorithm selection and threshold tuning in transactional data mining.

---

## Limitations
The Groceries dataset is relatively clean and moderate in size. As a result, the scalability advantages of FP-Growth over Apriori are less pronounced than they would be on larger or noisier transactional datasets. Results may vary when applied to high-dimensional or sparse retail data.

---

## Key Learnings
- Importance of preprocessing in transactional data mining  
- Practical differences between Apriori and FP-Growth  
- Role of interestingness measures in rule evaluation  
- Interpretation of frequent patterns for data-driven insights  

---

## Tools and Technologies
- Python  
- Pandas  
- mlxtend  
- Matplotlib  

---

## Conclusion
This project demonstrates the application of **classical data mining algorithms** to extract actionable knowledge from transactional data. By combining algorithmic comparison with rule interpretation, the work aligns closely with foundational concepts in **Machine Learning and Data Mining**.

---

### Note
This project is an independent academic implementation based on standard association rule mining techniques described in the data mining literature.
