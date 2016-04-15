### Assignment: Caching the Inverse of a Matrix

Matrix inversion is usually a costly computation and there may be some
benefit to caching the inverse of a matrix rather than computing it
repeatedly (there are also alternatives to matrix inversion that we will
not discuss here). Your assignment is to write a pair of functions that
cache the inverse of a matrix.

makeCacheMatrix is a function that returns a list of functions
Its puspose is to store a martix and a cached value of the inverse of the 
matrix. Contains the following functions:
* set      set the value of a matrix
* getMatrix      get the value of a matrix
* setinverse   set the inverse of the matrix and cache it
* getinverse     get the cahced value (inverse of the matrix). If there is
no cache, compute the inverse and cache it
