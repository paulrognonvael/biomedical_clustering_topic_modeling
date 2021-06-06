# Clustering and topic modeling for biomedical text mining

We propose an integrative approach to the problem of characterizing an unlabelled corpus of biomedical documents in an unsupervised manner. The integration is twofold. On one hand, we integrate, with multiview learning, different text representations derived from a traditional bag-of-words model, Latent Dirichlet Allocation, and a recurrent neural autoencoder. On the other hand, we integrate topic modeling outputs, clustering outputs and biomedical word embeddings to generate an intuitive and comprehensive characterization of the corpus. We also propose a semantic graph that supplies a synthetic visualization of the relationships between topics, clusters, and any other biomedical concept, based on semantic similarity. 

The notebooks in this repository constitute an application of our methodology to the CORD-19 dataset, a collection of articles on COVID-19, shows our methodology produces a coherent, meaningful, and informative characterization of the corpus.

Here is an overview of our methodology:
![](overview_proposal.png)
