# Explanation of the implemented gradient descent methodology

First I used the modules numpy for calculations, matplotlib to plot the results in 2D and mpl_toolkits.mplot3d to plot the results in 3D.

I defined 4 functions:
- mathfunc: the function to be optimized
- dxmathfunc: the derivate of mathfunc with respect of x
- dymathfunc: the derivate of mathfunc with respect of y
- gdalgorithm: the function with the gradient descent code, this function calculates the gradient in a loop, the values of x and y and then it appends in a list

Defining some parameters like x_start, y_start, learningRate and iterations we can call the gdfunction, and with the returning values of this function we can plot the results.

I plotted the results in 2D grid and in a 3D grid.