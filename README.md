# Simple Matrix Factorization Collaborative Filtering for Drug Repositioning on Cell Lines

The discovery of new biological interactions, such as interactions between drugs and cell lines, can improve the way drugs are developed. Recently, there has been important interest for predicting interactions between drugs and targets using recommender systems; and more specifically, using recommender systems to predict drug activity on cellular lines.

In this work, we present a simple and straightforward approach for the discovery of interactions between drugs and cellular lines using collaborative filtering. We represent cellular lines by their drug affinity profile, and correspondingly, represent drugs by their cell line affinity profile in a single interaction matrix. Using simple matrix factorization, we predicted previously unknown values, minimizing the regularized squared error.

We build a comprehensive dataset with information from the ChEMBL database. Our dataset comprises 300,000+ molecules, 1,200+ cellular lines, and 3,000,000+ reported activities. We have been able to successfully predict drug activity, and evaluate the performance of our model via utility, achieving an Area Under ROC Curve (AUROC) of near 0.9.
