# W1S1

* What is rank of a matrix?

> Rank of a matrix is defined as the maximum number of **linearly independent** column/row vectors in the matrix

* What is non-singular matrix?

> If $$det(A_{n \times n}) \neq 0$$, then $$ A_{n \times n}$$ is called non-singular matrix

* Known matrix forms

> * diagonal matrix
> * upper triangular matrix
> * lower triangular matrix
> * upper bi-diagonal matrix
> * lower bi-diagonal matrix
> * tridiagonal matrix
> * pentadiagonal matrix
> * upper Hessenberg if $$ a_{ij} = 0 $$ for $$ i-j>1$$
> * * $$ \begin{bmatrix} a_{11} & a_{12} & a_{13} & a_{14}\\a_{21} & a_{22} & a_{23} & a_{24}\\0 & a_{32} & a_{33} & a_{34}\\0 & 0 & a_{43} & a_{44}\\ \end{bmatrix}$$
> * lower Hessenberg matrix
> * Hilbert matrix
> * * Square matrix of order n whose elements in $$(i,j)$$ position is $$ \frac{1}{i+j-1}$$
> * Toeplitx matrix
> * * shape of \
> * Centrosymmetric matrix
> * Bisymmetric: $$ A=A^T$$ and $$ AJ=JA $$
> * Exchange matrix: $$J_3= \begin{bmatrix} 0&0&1\\0&1&0\\1&0&0\end{bmatrix}$$
> * Hankel matrix \(upside-down Toeplitz matrix\)
> * * shape of /
>   * Hilbert matrix is a special form of Hankel matrix
> * Vandermonde matrix
>
> * * $$ V=\begin{bmatrix}1 & \alpha _1 & \alpha _{1}^{2} & \cdots\\ \vdots & \vdots &\vdots& \ddots\end{bmatrix}$$
>   * $$ det(V)=|V|= \prod \limits_{1\leqslant i<j\leqslant n} \left( \alpha_j - \alpha_i \right)$$
> * Zero matrices
> * Identity matrices
> * * Columns of identity matrix are called **canonical vectors**
> * Permutation matrix
> * * There are $$n!$$ permutation matrices of size $$n$$
>   * Non-singular, and the determinant is always $$\pm 1$$
>   * $$AA^T=A^TA$$
> * Involutory: $$A^2=I$$
>   * e.g. $$A=\begin{bmatrix} 1&\alpha\\0&-1\end{bmatrix}$$
> * Idempotent: $$A^2=A$$
> * Nilpotent: $$A^k=0,k>0$$
> * For real $$x$$, $$x^Tx=0$$ iff $$x=0$$
> * For complex $$x$$, $$x^Hx=0$$ iff $$x=0$$



