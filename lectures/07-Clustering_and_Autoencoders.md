## Unsupervised machine learning: Clustering and Autoencoders

### Required Study Materials

- [Unsupervised ML](https://www.youtube.com/watch?v=lEfrr0Yr684)
- [k-means clustering](https://www.youtube.com/watch?v=4b5d3muPQmA)
- [Autoencoders](https://www.youtube.com/watch?v=7mRfwaGGAPg)
- [Starting with Transformers](https://www.youtube.com/watch?v=4Bdc55j80l8)

### Activities

Introduce the concept of Unsupervised learning

#### 1. Clustering
- split into groups and give them couple of pictures with color points (three separate groups, some spiral...)
- ask them to cluster the dots (use k-means) -> discuss the results, did it work?
- discuss different similarity functions, mention [other clustering algorithms](https://scikit-learn.org/stable/modules/clustering.html), what if we initialize the centroids at unfortunate places?
- discuss usages of clustering
- try the clustering in [jupyter notebook](07-kmeans_images.ipynb)
	- working with images
	- introduce the concept of embeddings
- discuss choosing K - internal, external criteria (Elbow method)

#### 2. Autoencoder for fruits

We want to encode any type of fruit into 5 features

- let them think about those 5 features (it can be eg color, shape, taste...)
- try to encode and decode KIWI fruit, does it work? if not, adjust the features
- move the encoder to other group, let them encode some fruit and try to decode it back
- let other group give you some atypical feature combination, try to decode (invent your own fruit) and share with others 
      
    -> this is how generative models worked some time ago

#### 3. Autoencoder  for dimensionality reduction

- working with MNIST images
- goal is to reduce the size of the image so we are still able to reconstruct it
