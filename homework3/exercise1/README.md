# Exercise 1

## 1.How does a program read the cvMat object, in particular, what is the order of the pixel structure?

A Program reads cvMat with a pointer and inputs of datatype,rows,columns. The pointer contains the pixel values represented by different types of multiple channels. We can access a particular point in the matrix fo pixel by using a coodinate(x,y),if there are multiple color-channels in one pixel, we can use datatype to access the pixel.


