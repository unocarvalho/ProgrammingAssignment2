cacheSolve <- function(x, ...) {
inverter.matrix <- x$getinverse()
if(!is.null(inverter.matrix)) {
return(inverter.matrix)
}
else {
MatrixData <- x$getMatrix()
inverter.matrix <- solve(MatrixData, ...)
x$setInverse(inverter.matrix)
return(inverter.matrix)
}
}
