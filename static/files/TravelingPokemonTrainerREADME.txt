This is a program that tackles the Traveling Salesperson problem
in a cute and fun way, based off of a Pokemon hunt in a region.

When given the number of Pokemon in a region, followed by the 
locations of each pokemon is a 2D-grid, where all locations in the
lower left quadrant are considered water and must be accessed by
a location on the shore ((0, -X) or (-X, 0)), the user may prompt for 
either a Minimal Spanning Tree, an efficient solution to "catch
all Pokemon", or the most optimal solution to "catch all Pokemon".

Test files are included in the folder "test_files", but it is possible 
to create alternate Pokemon layout by manual input.

To use, select mode -m and either MST, FASTTSP, or OPTTSP depending on whether
you would like a Minimal Spanning Tree, an efficient solution, or an 
optimal solution respectively. For further information, select mode -h.

This project is property of the University of Michigan, as it is project 4 of 
Data Structures and Algorithms, EECS 281. This code should remain private, with 
any public release of this code breaking the University of Michigan's 
honor code. This code was created using the starter code provided by the 
University of Michigan and the effort of George North.