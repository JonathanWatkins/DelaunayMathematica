This reads a set of coordintates from a file and calculate the Delauny Triangulation.

The format is a single frame or timestep per line.

Each line contains a list of x and y positions of the N particles.

e.g.

x0 y0 x1 y1 .... xN-1  yN-1

The result of the routines is a variable called frames that contains all the images of the Delaunay Triangulation.
