# *How to run the program* #

This program was created using python in a google colab notebook. The file [ edit_distance.ipynb ] can be ran online wihtout the need of installation or dependencies through google colab at: https://colab.research.google.com/drive/1LHN0bzyPX3nxrYv2rOlnpT7csTObfXJK?usp=sharing

# *Program Discription* #

This program calculates the edit distance between two words and outputs both the matrix of distance calculation and an alignment that demonstrates the result.

The program begins by asking the user to input two words. Those two words are then used as the parameters in the edit_distance function. A two-dimensional array is used to create a matrix with (m+1) rows and (n+1) columns, where m and n are the lengths of the two inputted words. The algorithm then uses the (i,j)th element of the matrix and computes the minimum edit distance between the two strings. The minimum edit distance is calculated based on the minimum amount of insertions, deletions, and substitutions needed to transform one string into the other.

A list is then used to store the alignment between the two input words that correspond to the minimum edit distance. The alignment is then computed by tracing back the matrix from the bottom-right corner to the top-left corner.
