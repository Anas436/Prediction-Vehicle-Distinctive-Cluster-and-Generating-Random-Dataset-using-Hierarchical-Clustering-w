# Vehicle-Distinctive-Clustering-using-Hierarchical-Clustering-with-Python



## Objectives

After completing this lab you will be able to:

*   Use scikit-learn to do Hierarchical clustering
*   Create dendograms to visualize the clustering

<h1>Table of contents</h1>

<div class="alert alert-block alert-info" style="margin-top: 20px">
    <ol>
        <li><a href="https://#hierarchical_agglomerative">Hierarchical Clustering - Agglomerative</a></li>
            <ol>
                <li><a href="https://#generating_data">Generating Random Data</a></li>
                <li><a href="https://#agglomerative_clustering">Agglomerative Clustering</a></li>
                <li><a href="https://#dendrogram">Dendrogram Associated for the Agglomerative Hierarchical Clustering</a></li>
            </ol>            
        <li><a href="https://#clustering_vehicle_dataset">Clustering on the Vehicle Dataset</a></li>
            <ol>
                <li><a href="https://#data_cleaning">Data Cleaning</a></li>
                <li><a href="https://#clustering_using_scipy">Clustering Using Scipy</a></li>
                <li><a href="https://#clustering_using_skl">Clustering using scikit-learn</a></li>
            </ol>
    </ol>
</div>
<br>
<div>

<h1 id="clustering_vehicle_dataset">Clustering on Vehicle dataset</h1>

Imagine that an automobile manufacturer has developed prototypes for a new vehicle. Before introducing the new model into its range, the manufacturer wants to determine which existing vehicles on the market are most like the prototypes--that is, how vehicles can be grouped, which group is the most similar with the model, and therefore which models they will be competing against.

Our objective here, is to use clustering methods, to find the most distinctive clusters of vehicles. It will summarize the existing vehicles and help manufacturers to make decision about the supply of new models.
</div>
