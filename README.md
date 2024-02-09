# Assign5 Find the value of inverse of a matrix, determinant of a matrix by using the following values:
A=matrix(1:100, nrow=10)
B=matrix(1:1000, nrow=10)

A <-matrix(1:100, nrow = 10)
B <-matrix(1:1000, nrow = 10)

t_A <-t(A)

t_B <-t(B)

a <-1:ncol(A)

b <-1:ncol(B)

P <-A%*%a

Q <-B%*%b

a <-1:nrow(A)

b <-1:nrow(B)

R <-A%*%B

S <-matrix(2:5, nrow = 2)

S_inverse <-solve(S)

det_S <-det(S)
