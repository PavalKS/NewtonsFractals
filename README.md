# NewtonsFractals
Contains the code to create Fractals using Newton's Method in MATLAB

Newton's Method is a well known procedure for finding roots of functions.  
Specifically, we start with a function $f(x)$ and an initial value of $x_0$.  We then define values xn by the equation

$x_(n+1) = x_n - f(x_n)/f'(x_n)$

In most cases, xn will converge to a root of $f(x)$ rapidly.  

While most people learn this using real functions, there is no reason why Newton's Method cannot be used with complex functions.  
So, given a function $f(z)$ with multiple roots, we can color each point $z$ in the complex plane by which root Newton's Method will converge to if $z_0 = z$. 
We can also alter the color depending on how quickly we converge to the root, and we will color the point black if we don't converge to anything in a 
predetermined number of steps.

Since this is an iterative complex system, it is not too surprising that we end up with fractals.  
What is wonderful about this scheme is the great variety of images one can make with this simple concept.  
The students in my numerical analysis class were given a program that would create these fractals.  
They picked the function, the colors, and the error tolerance. 
