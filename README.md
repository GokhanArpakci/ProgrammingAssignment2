# Programming Assignment 2: Lexical Scoping

## For the Coursera course [R Programming](https://www.coursera.org/course/rprog)

Please find below instructions and scrpit of assesment.R code


	# read the R script
	# replace the "path/to/file" with the directory you save the file into
	# or you can read the file directly from the web
	source("path/to/file/assesment.R")

	# create a *square* matrix (because `solve` only handles square matrices)
	# create the matrix during the call of makeCacheMatrix()
	G <- makeCacheMatrix( matrix(c(7,9,18,27), nrow = 2, ncol = 2) );

	summary(G);
	#>              Length Class  Mode    
	#> setMatrix    1      -none- function
	#> getMatrix    1      -none- function
	#> cacheInverse 1      -none- function
	#> getInverse   1      -none- function

	G$getMatrix();
	#>      [,1] [,2]
	#> [1,]    7   18
	#> [2,]    9   27

	cacheSolve(a)
	#> [,1]        [,2]
	#> [1,]  1.0000000 -0.6666667
	#> [2,] -0.3333333  0.2592593

	# the 2nd time we run the function,we get the cached value
	cacheSolve(a)
	#> getting cached data
	#> [,1]        [,2]
	#> [1,] -1.1818182  1.09090909
	#> [2,]  0.1818182 -0.09090909



