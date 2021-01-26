# Parallelization-in-C
A program that shows how to use threads in C to parallelize an expensive computation 

This program generates an image from the madlebrot set, which can be very computationally expensive.
I will not go into detail on what the set is, but you are able to find very interesting images by exploring the set.
The program can take several command line arguments:
  - x and y refer to the physical coordinates of the set
  -'max' controls the amount of work done by the algorithm. The higher the max value, the more detail there will be but the longer       it will take to compute
  - 's' referes to how zoomed in the picture is
  -
 
 If there are no command line arguments, the program will print out the generic image of the mandelbrot set. 
