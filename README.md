# Clustering the colors in an image using Machine Learning
KMeans Algorithm is used in this model to implement color seperation.

## Abstract
Color Seperation is a process of seperating all the colors and plotting a pie chart of all colors present in the image.KMeans is an unsupervised machine learning algorithm which identifies the optimal number of clusters (k) using Elbow method and assigns the optimal centroid to each cluster.This model clusters the colors using Kmeans and has an accuracy of 83%.

Let's seperate the colors of this image

![input](https://user-images.githubusercontent.com/114278846/210208358-70de547c-11a7-44a1-8916-bf2a2ac37d73.png)

To read this image we use OpenCV; where it uses RGB pattern instead of BGR. 

So converting to RGB

![rgb](https://user-images.githubusercontent.com/114278846/210208699-d636f99d-400d-4ec2-abc6-9093453434aa.png)

Now, use KMeans to fit the image

> The predicted centroid values are:

![predicted_centroids](https://user-images.githubusercontent.com/114278846/210209126-9a83d0cd-4e37-430c-9688-2917f43a2e26.jpeg)

> Pie Chart for predicted centroid

![predicted pie](https://user-images.githubusercontent.com/114278846/210210825-64383469-6aa0-4e86-bc4a-d1163aeae785.png)

with a shape of **5,3**

Graph for Elbow Method

![elbow graph](https://user-images.githubusercontent.com/114278846/210211032-67d35ba8-4e48-4949-a64a-449dbf86c34f.png)

The optimal K value is found to be 4

> resulting a Pie Chart:

![optimal pie](https://user-images.githubusercontent.com/114278846/210211209-da8a336a-b73c-486b-beb3-ea429ae66e51.png)

