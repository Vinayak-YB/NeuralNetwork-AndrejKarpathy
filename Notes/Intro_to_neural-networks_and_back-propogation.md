An Autograd engine implements back-propogation. 

## What's a gradient?

    z = f(x,y)\
    del f(x,y) = <fx(x,y), fy(x,y)> - vector of derivatives

Basically it's the vector that points in the direction of maximum increase at any x,y.

Backpropogation is an algorithm that allows you to effeciently evaluate the gradient of a loss function with respect to weightd of a neural network.
We can iteratively tune the weights of that neural network and improve the accuracy of that network.

