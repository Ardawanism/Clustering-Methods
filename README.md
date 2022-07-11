# Clustering-Methods
This Repo Contains Implementation Of Different Clustering Methods From Scratch Using Python

1- How K-Menas Works:<br/>
  step 1-Assign Each Sample To The Nearest Centoid<br/>
  step 2-Update Centroids : Center Of Each Cluster Is The Mean Of The All Samples Which Belongs To The Corresponding Cluster<br/>
  step 3-Repeat Until Convergence<br/>
The Following Video Visualizes How K-Means Is Actually Working:<br/>
![k-menas](https://user-images.githubusercontent.com/106836722/178311597-e59a8e10-7734-42f0-bd20-2704ae3d66a6.gif)
<br/>
2- How Kohonen Self Organizing Map Works:<br/>
    step 1-Consider A Specific Topology, Neighbourhood Radius and Weight Matrix<br/>
    step 2-for epoch 1:N DO:<br/>
        For Each Sample:<br/>
            Find The Nearest Neuron To The Data Sample<br/>
            Update The Weights Of The Winner Neuron And Neighbours Based On The Choosen Topology And Neighbourhood Radius<br/>
The Following Video Visualizes How Self Organizing Map Is Actually Working:<br/>
![SOM](https://user-images.githubusercontent.com/106836722/178313808-84f0bb9c-3802-4192-8416-e30c8c87a446.gif)





