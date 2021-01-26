# Parallelization-in-C
A program that shows how to use threads in C to parallelize an expensive computation 

This program generates an image from the madlebrot set, which can be very computationally expensive.
I will not go into detail on what the set is, but you are able to find very interesting images by exploring the set.
The program can take several command line arguments:
  - x and y refer to the physical coordinates of the set.
  -'max' controls the amount of work done by the algorithm. The higher the max value, the more detail there will be but it will take longer to compute.
  - 's' referes to how zoomed in the picture is.
  - 'n' refers to the number of threads used in the set.
 
 
 There other arguments you can use as well, type help to find what they are. If there are no command line arguments, the program will print out the generic image of the mandelbrot set. 
 
 Here is an example of an image's coordiantes I used and how increasing the number of threads affected execution time:
 
 -x 0.2869325 -y 0.0142905 -s .000001 -W 1024 -H 1024 -m 1000

Threads | Execution Time (seconds)
--------|-----------------
1       | 3.519
2       | 1.957
3       | 1.487
4       | 1.140
5       | 1.123
10      | 1.062
50      | 1.018
100     | 1.027
