# FutureUs

**Task** = To extract the features from the dataset and then apply unsupervised learning algorithms

**Dataset** = [Link](https://www.kaggle.com/datasets/ahmadahmadzada/images2000)

**Implementation**: I used transfer learning techniques and imported a pre-trained ResNet model for extracting features. Then I imported the sentence transformer, created sentence embeddings of each image caption, and concatenated it to the features extracted from the model. Then I used K-Means and Hierarchical Clustering algorithms for further categorization.
