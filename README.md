# Graphic-Engine
A graphic engine to design shapes on DE1-SOC and Terasic LT-24 LCD. 

The graphics engine driver consists of a header file and a source file that is capable of drawing geometrical shapes such as: lines, rectangles, circles and triangles. All the closed figures can either be unfilled or filled. In addition, the driver initializes the LT24 display if it has not been previously set with the values of the memory address. Rasterization of each geometrical shape is carried out by defining a function that returns an error value if the design is not created. 

