# GraphCPIs
A novel graph-based computational model for potential compound-protein interactions

Identifying proteins that interact with drug compounds has been recognized
19 as an important part in the process of drug discovery. Despite extensive efforts that
20 have been invested in predicting compound-protein interactions (CPIs), existing
21 traditional methods still face several challenges. The computational methods can
22 provide high-quality CPIs candidates in an instant. In this study, we propose a novel
23 model, named GraphCPIs, to improve the CPIs prediction accuracy. First, we
24 establish the adjacent matrix of entities connected to both drugs and proteins from the
25 collected dataset. Then, the feature representation information of nodes can be
26 obtained by using the graph convolutional network and GraRep embedding model.
27 Finally, the stacked two kinds of features are fed into an extreme gradient boosting
28 (XGBoost) classifier to predict potential CPIs. The results demonstrate that
29 GraphCPIs achieve the best performance, whose average predictive accuracy rate
30 reaches 89.96%, average area under the receiver operating characteristic curve is
31 0.9574 and average area under the precision and recall curve is 0.9619. Moreover,
32 comparative results show that our model outperforms state-of-the-art methods in
33 terms of both accuracy and other indicators with the same experimental environment.
34 We believe that GraphCPIs model would provide valuable insight to discover novel
35 candidate drug-related proteins.
