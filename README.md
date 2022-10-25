# topic-classification
Businesses deal with many other unstructured texts daily, like, news posts, support tickets, or customer reviews. Failing to glean this data efficiently can lead to missed opportunities or, even worse, angry customers. So again, an automated system that can process a vast amount of data is a more scalable solution than manual scanning.   In this repo, I focus on the problem of `topic classification`, with the aim to assign a topic to some piece of text. The list of topics is predefined, and in that sense, I use the [20 newsgroups dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_20newsgroups.html#sklearn.datasets.fetch_20newsgroups) available through _scikit-learn_ and that comprises around 18000 newsgroups posts on 20 topics. I implement a topic classifier from scratch and present various techniques related to dimensionality reduction and text mining:

* **Exploratory data analysis**
    * Pie charts
    * N-gram frequencies
* **Dimensionality reduction**
    * Principal Component Analysis
    * Linear Discriminant Analysis
    * Singular Value Decomposition
* **Text representations**
    * Word Embedding
* **Classification algorithms**
    * K-Nearest Neighbor
    * Random Forest
    * Decision Trees
* **Tools**
    * fastText
