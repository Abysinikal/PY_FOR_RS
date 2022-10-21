# Satellite Image Analysis and Kmeans Clustering 

## Problem adressed

The term clustering is used to refer to the act of grouping information, which can be data from customers, products or in this example satellite data.It is the way to group and categorize based on common characteristics. Once we have identified the clusters we can make customized decisions for each of the clusters. 
Think of a puzzle, the fastest way to begin is to separate the pieces by color, shape, and edges.

## Methodology and Implementation

### Methodology 
   k-means clustering is a method of vector quantization, originally from signal processing, that aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean (cluster centers or cluster centroid), serving as a prototype of the cluster.

 
### Preprocessing 
   Working on satellite image data implies being able to :
   * opening satellite data formats like .tiff
   * reading one or multiple hyperspectral bands
   * visualize the satellite image
   * clipping the image to boundary of interest
   * Derive statitics on grid 
   * Clipping Images to Boundaries
   * Create Vegetation Index (NDVI)
   

### Clustering Algorithm implementation
  
  This example is based on satellite data with NDVI (normalized difference vegetation index). NDVI is an indicator of vegetation health based on how plants reflect certain ranges of the electromagnetic spectrum. The index ranges from -1 to 1; 1 indicating the best health status of the observed land cover.
  The core concept is to identify k clusters based on the NDVI without having to learn an underlying image to ndvi index mapping. 
  
## Results


<!---
### 1. Open satellite imagery in Python 
### 2. Read Satellite Image bands
### 3. Visualize Images
Visualising Band 3 (For code please refer to the attached jpynb):
![2021-07-19_17h50_15](https://user-images.githubusercontent.com/62526508/126189294-8653949d-36fa-4971-90f2-5cc7c93146f6.png)

### 4. Numpy Array Manipulations
### 5. Clipping Images to Boundaries
### 6: Create Vegetation Index (NDVI)
### 7: Derive statitics 
### 8: Clustering with KMeans algorithm
The clustering model generates the following map (For code please refer to the attached jpynb):
![2021-07-19_17h45_56](https://user-images.githubusercontent.com/62526508/126188673-4e16ec3a-1303-4b12-b3ba-30192c9081f1.png)
*/


-->
