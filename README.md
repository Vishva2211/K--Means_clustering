# K--Means_clustering
K-Means Clustering My approach
1)I ran a loop with all the elements to find each of its distances from the centroid and assigned the element with highest distance as rank 1
2)I ran a loop with all elements to find the distance between the rank 1 and arranged them in acending order and took the first 100 elements to store it as Rank A
3)then i removed the data of the first 100 rankers from the dataset
4)now I randomly generated 2 centroids for the remaining dataset elements
5)ran a loop to find the distance between each element to each centroid and clustered them based on the minimum distance
6)then I found the average of each cluster to find the new centroid
7)I ran the 5th and 6th steps 300 times
8)I ploted the graph
