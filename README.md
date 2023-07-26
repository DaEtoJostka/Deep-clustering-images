# Deep clustering images with VGG19 

I found this article (https://towardsdatascience.com/how-to-cluster-images-based-on-visual-similarity-cd6e7209fe34) and decided to adapt it to my needs. I rewrote it from Keras to Pytorch, changed model from VGG16 to VGG19, added experiment tracking, and improved visualization. Use it and suggest improvements! 

P.S. The algorithm does not split images that are similar in color and shape well, so be careful.
 
Exampels of clustering:

## Cluster 1
![alt text](https://github.com/DaEtoJostka/Deep_clustering_images/blob/main/Examples/output.png?raw=true)

## Cluster 2
![alt text](https://github.com/DaEtoJostka/Deep_clustering_images/blob/main/Examples/output1.png?raw=true)

## Cluster 3
![alt text](https://github.com/DaEtoJostka/Deep_clustering_images/blob/main/Examples/output3.png?raw=true)
