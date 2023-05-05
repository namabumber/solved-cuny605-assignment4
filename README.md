Download Link: https://assignmentchef.com/product/solved-cuny605-assignment4
<br>
In this problem, we’ll verify using R that SVD and Eigenvalues are related as worked out in the weekly module. Given a 3 × 2 matrix <strong>A</strong>

<strong>A</strong>                                                                       (1)

write code in R to compute <strong>X </strong>= <strong>AA<sup>T </sup></strong>and <strong>Y </strong>= <strong>A<sup>T</sup>A</strong>. Then, compute the eigenvalues and eigenvectors of <strong>X </strong>and <strong>Y </strong>using the built-in commans in R.

Then, compute the left-singular, singular values, and right-singular vectors of <strong>A </strong>using the <em>svd </em>command. Examine the two sets of singular vectors and show that they are indeed eigenvectors of <strong>X </strong>and <strong>Y</strong>. In addition, the two non-zero eigenvalues (the 3rd value will be very close to zero, if not zero) of both <strong>X </strong>and <strong>Y </strong>are the same and are squares of the non-zero singular values of <strong>A</strong>.

Your code should compute all these vectors and scalars and store them in variables.

Please add enough comments in your code to show me how to interpret your steps.

<ol start="2">

 <li>Problem Set 2</li>

</ol>

Using the procedure outlined in section 1 of the weekly handout, write a function to compute the inverse of a well-conditioned full-rank square matrix using co-factors. In order to compute the co-factors, you may use built-in commands to compute the determinant.

Your function should have the following signature:

B = myinverse(A)

where <strong>A </strong>is a matrix and <strong>B </strong>is its inverse and <strong>A</strong>×<strong>B </strong>= <strong>I</strong>. The off-diagonal elements of <strong>I </strong>should be close to zero, if not zero. Likewise, the diagonal elements should be close to 1, if not 1. Small numerical precision errors are acceptable but the function <em>myinverse </em>should be correct and must use co-factors and determinant of <strong>A </strong>to compute the inverse.

Please submit PS1 and PS2 in an R-markdown document with your first initial and last name.