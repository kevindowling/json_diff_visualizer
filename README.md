# JSON Structure Visualizer

![Screenshot](images/Screenshot.PNG)

## Main purpose
Highlight differences between two JSON structures. One diagram is built from 2 different JSON structures. Any nodes that are unique to the first json will be in blue, any nodes that are unique to the second json will be orange, any nodes that are shared between the two json will be grey. 

## What is not visualized
Values are not visualized, only keys. Also, if there is an array, only the first item in the array is visualized under the assumption that all items in the array have the same child structure.

