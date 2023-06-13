# K-means-and-Visualization-of-Time-Series-Data
For my second PhD project, I learned another exciting method: K-means.  Here, you will find an easy to follow example of how to get started with K-Means and helpful resources that guided me throughout my project. This code was used for article “Neurodevelopmental Changes after Adversity in Early Adolescence”, which is currently under review.

The html version of this code can be found on my website or here: https://kmeans-timeseries.netlify.app/

Overview
First, we will conduct a K-Means analysis and then we will visualize the clusters as time series data.

What is K-means?
K-means is an unsupervised learning method (i.e., without categorical specifications). This method minimizes the average squared distance between points in the same cluster and is used to group objects into clusters (Hartigan & Wong, 1979; Jain, 2010; Lloyd, 1982). K-means is partitioning observations in “k” clusters. Each observation is sorted into a cluster with the closest average. With this technique in psychological research, we can find, for example, subgroups in population studies, or in other words, participants with similar characteristics in specific variables.

These are the steps we will follow during this short tutorial:

    We will determine the optimal number of clusters with the commonly used Elbow and Silhouette methods.

    We will conduct a K-means analysis.

    We visualized the clusters across two time points using ggplot.
