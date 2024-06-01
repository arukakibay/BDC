# BDC
The goal of the first assignment is to appreciate the practical meaning of low-rank approximation. To this purpose, we are going to take a look at image reconstruction.
At a high level, your task is the following: i) read in a black/white photo and convert it into a matrix: ii) perform a singular value decomposition of the matrix thus obtained; iii) reconstruct the photo corresponding to using only 5%, 10%, 25%, 50% of the singular values. Things you should look at:
* Print the reconstructed photo. How good is the quality of the reconstructed photo?
* What percent of the Frobenius norm of the matrix corresponding to the original picture is retained in each case?
