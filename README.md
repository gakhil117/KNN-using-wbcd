# KNN-using-wbcd

K-Nearest Neighbors
The KNN algorithm assumes that similar things exist in close proximity. 
In other words, similar things are near to each other.

“Birds of a feather flock together.”

There are other ways of calculating distance, and one way might be preferable depending on the problem we are solving. However, the straight-line distance (also called the Euclidean distance) is a popular and familiar choice.

The KNN Algorithm
Load the data
Initialize K to your chosen number of neighbors

1 Calculate the distance between the query example and the current example from the data.

2 Add the distance and the index of the example to an ordered collection

4. Sort the ordered collection of distances and indices from smallest to largest (in ascending order) by the distances

5. Pick the first K entries from the sorted collection

6. Get the labels of the selected K entries

7. If regression, return the mean of the K labels

8. If classification, return the mode of the K labels
