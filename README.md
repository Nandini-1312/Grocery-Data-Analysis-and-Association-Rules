# **Grocery-Data-Analysis-and-Association-Rules**


**Overview**

This project contains an analysis of transactional data from a grocery store, focusing on uncovering associations between different grocery items. The main techniques employed include item frequency visualization, association rule mining, and recommendations for increasing pastry sales.



**Analysis**

A) Item Frequency Plot
The item frequency plot visualizes the top 40 grocery items based on their frequency of occurrence in the dataset.

B) Top Five Rules by Confidence
The top five association rules were identified and ranked by their confidence metric. Confidence measures the likelihood that a rule's consequent is purchased when its antecedent is purchased.

C) Top Ten Rules by Lift
The top ten association rules were identified and ranked by their lift metric. Lift measures the strength of an association rule over the random co-occurrence of items.

D) Consistency and Differences
While both confidence and lift metrics help in identifying strong association rules, they can yield different top rules due to their underlying calculations. Confidence focuses on the probability of co-occurrence, whereas lift considers the independence of item occurrences.

E) Recommendations for Increasing Pastry Sales
Based on the analysis, specific item bundles can be developed to enhance pastry sales. Recommendations include bundling pastries with frequently associated items such as coffee, tea, or fresh fruits, identified from the high-confidence and high-lift rules.
