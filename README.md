# telco_customer_churn

Source data: https://www.kaggle.com/blastchar/telco-customer-churn

### Aims:
- practice classification workflow on publicly available dataset
- use sample of algorithms to predict churn (Logisitic Regression, Random Forests, Support Vector Machines)
- address class imbalance using over-sampling, under-sampling and synthetic data creation (SMOTE, SMOTETotek)
- investigate customer groupings through data analysis and clustering algorithms (Kmeans, hierarchical clustering, DBSCAN clustering)

### Results:
- modelling shows clear indications that churn amongst new customers (length of service = 1 month) and those with fibre internet service was significantly higher than the rest of the population.
- clustering shows that there are 4 main groups of customers, with one group in particular having much higher rates of churn than others. This group tended to not have partners or dependents, had phone and internet service with higher adoption of fibre internet service, but less likely to be on 1 or 2 year contracts or take on additional services e.g. streaming TV, online security. Churn rate for this group was 47% vs 7%, 15% and 25% for the other groups and 27% for the population. (Results from Kmeans clustering but similar findings were obtained from hierarchical and DBSCAN).

### Recommendations:
- further investigation would need to be made into those customers cancelling after 1 month. This would include reviewing business processes, particularly around the fibre internet service, to see if there were any particular failings were happening.
- more focus placed on retaining the group with highest churn rates, perhaps through greater emphasis of cross-selling additional services or converting month-to-month customers to 1 or 2 year contracts.
