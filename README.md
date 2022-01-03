#Segmentation of Colposcopic images by k-means



The K-means algorithm is an iterative technique that is used to partition an image into K clusters.The basic algorithm is
1.Pick K cluster centers, either randomly or based on some heuristic method.
2.Assign each pixel in the image to the cluster that minimizes the distance between the pixel and the cluster center
3.Re-compute the cluster centers by averaging all of the pixels in the cluster
4.Repeat steps 2 and 3 until convergence is attained (i.e. no pixels change clusters)
In this case, distance is the squared or absolute difference between a pixel and a cluster center. The difference is typically based on pixel color, intensity, texture, and location, or a weighted combination of these factors. K can be selected manually, randomly, or by a heuristic. This algorithm is guaranteed to converge, but it may not return the optimal solution. The quality of the solution depends on the initial set of clusters and the value of K.
Medical Image Enhancement:Main Algorithm working:
1.Choosing the number of Clusters(n)
2.kmeans centers points for centroid.
3.Assigning each Data point as we say each pixel value closest to the above centroid that further gives us clusters.
4.On the last step we just do the concatination of original and segmented image.


###Uses of Image Segmentation:
Improved Quality of MRI/Medical images for better detection of diseases and problems
Segmenting images can help to improve robot vision
Image segementation is also be applied to satellite images in order to get better object detection. These objects may be buildings,roads,cars,or trees , for example. Applications of this type of imagery labelling are widespread, from analysing traffic to monitoring environmental changes taking place due to global warming.
