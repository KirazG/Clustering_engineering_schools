This project uses data from Data.gov 's College Scorecard https://collegescorecard.ed.gov/data/documentation/ to evaluate two methods handling null values for unsupervised clustering: (1) imputing nulls via KNN prior to clustering and (2) clustering on complete observations and then assigning clusters to incomplete observations via KNN. 
Clusters are evaluated visually with pairplots and numerically with silhouette scores, where possible.
