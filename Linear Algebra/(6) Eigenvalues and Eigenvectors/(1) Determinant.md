For some n x n matrix A with $A_{ij}$ the minor obtained deleting the ith row and jth column of A, We have the ==determinant== to be given by

$det \ A = \sum_j (-1)^{i+j}a_{ij} det(A_{ij})$
(Here we can sum over js or is it doesn't matter, either you look at a row and then form minors or you use a column to form minors)


Additionally, we can compute the determinant as follows:
$det(A) = \sum_{\sigma \in S_n} sgn(\sigma)a_{1\sigma(1)}a_{2\sigma(2)}...a_{n\sigma(n)}$

This is only useful if we have diagonal matrices or matrices with lots of 0 rows.
