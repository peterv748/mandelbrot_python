# mandelbrot_python
straight forward implementation of mandelbrot set using python and some python libraries
you need to install, using pip or a similar package installer, numpy for the complex calculations, and matplotlib
the program stores the results of the mandelbrot calculation in a 4096x4096 array, and displays this array using matplotlib functions
included are three png files:
 - showing processing time without any optimization (this python code)
 - showing processing time usig numba jit optimazition
 - showing processing time usig a NVIDIA GTX1070 mobile, using CUDA version 10 API
 
 All is run on a HP OMEN laptop, having 16GB memory and a Intel Core i8 8750, with 6 cores
