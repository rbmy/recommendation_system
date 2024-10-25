# Team G.R.A.F - Project Proposal
___
#### Contacts 
*Panagiotis Farmakis - panagiotis.farmakis@gatech.edu*

*Rob Mayo - rmayo9@gatech.edu*
___

**Team Name**: G.R.A.F (Graph Representations Are Fun)

**Project Name**: Recommendation System with GNNs: Examining Vanilla GNN, LightGCN, and GraphSage.

## Project Summary
In our day-to-day lives, we are often confronted with many options in tasks such as shopping, finding entertainment, or finding a job. It is not easy to sift through all these options, but having an intelligent recommendation system can increase the quality of your experience. Vanilla Graph Neural Networks (GNNs) are great at creating recommendation systems, but there is room for improvement. Vanilla GNNs, for example, do not use attention techniques or convolution for feature extracting, and a vanilla GNN may not generalize well to new data. In this project, we will examine and compare more sophisticated architectures.

## Approach 
* Review existing literature regarding Graph Neural Networks. That would include: 
  * Literature regarding Graph Neural Network
  * Literature containing more specific GNN architectures, relevant to the setting. 
* Implement a Baseline (vanilla) GNN. That would require: 
  * Training/validation methodologies
  * Implementation of relevant evaluation metrics: Precision@k, Recall@k, NDCG@k, etc.
* Implement more sophisticated GNN architectures, tailored to Recommendation Systems: 
  * GraphSAGE
  * LightGCN
  * GAT (Graph Attention Networks) *[Stretch Goal]*
  * Comparison with the baseline model
* Experiment with Cold-Start approaches. A Common Problem in Rec.  Systems. *[Stretch Goal]*
* Dive into the Explainability of the Results *[Stretch Goal]*
* Present finding results in the Report. That would include: 
  * Achieved performance for each of the implemented models.
  * Detailed comparison of the models and thorough discussion of their strengths, limitations, and trade-offs 
  * Discussion with intuitions, findings, and observations. 

## Resources/Related Work 

* [1] “Graph neural networks: A review of methods and applications”, Zhou et al
* [2] “Graph Convolutional Neural Networks for Web-Scale Recommender Systems”,  Ying et al
* [3] “Neural Graph Collaborative Filtering“, Wang et al
* [4] “LightGCN: Simplifying and Powering Graph Convolution
Network for Recommendation”, He et al
* [5] “Inductive Representation Learning on Large Graphs”, Hamilton et al
* [6] “Graph Attention Networks”, Veličković et al
* [7] “Graph Neural Networks in Recommender Systems: A Survey”, Wu et al
* [8] “Graph Neural Networks for Social Recommendation”, Fan et al
* [9] “A Comprehensive Survey on Graph Neural Networks”, Wu et al 

## Dataset
* https://pytorch-geometric.readthedocs.io/en/2.6.0/modules/datasets.html

## Team Members
* Panagiotis Farmakis
* Rob Mayo
