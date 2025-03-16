# Module_19_UnsupervisedLearning

In this project, I analyzed a cryptocurrency market dataset using unsupervised machine learning models.

Data Preprocessing: The data was first scaled to ensure all features contributed equally.

Clustering Analysis:
A K-Means clustering model was applied to the scaled data.
An Agglomerative Clustering model was also tested, but K-Means provided better results.

Dimensionality Reduction: Due to multicollinearity in the dataset, Principal Component Analysis (PCA) was performed to reduce feature redundancy.

Model Comparison: A K-Means model was then fitted to the PCA-transformed data, and the results were compared to those obtained from the original dataset.

This analysis helped uncover patterns in the crypto market and demonstrated the effectiveness of clustering techniques on financial data.
