# CubeSphereSurfaceArea

: Suppose your geometry professor asks you to create a program that calculates the surface areas 
of a cube and a sphere.
In order to find these two values, your program needs to get the side of the cube and the radius of the 
sphere first and then, using them, calculate the corresponding areas using the formulas shown below

Surface area of cube: 6 x s^2
Surface area of sphere: 4 x π x r^2

The values corresponding to s (side of the cube), r (radius of the sphere), and the calculated areas must be
double precision real numbers.

To solve this problem your program must perform the following tasks:
Declare a global constant variable named PI above main() that holds value 3.141592
Declare variables named side, radius, s_cube, and s_sphere that hold double precision real numbers
Prompt the user to "Enter side of cube : "
Read from keyboard the value entered by the user and assign it to side
Prompt the user to "Enter radius of sphere : "
Read from keyboard the value entered by the user and assign it to radius
Call cube_surf() to calculate the surface area of the cube and assign the result to s_cube
Call sphere_surf() to calculate the surface area of the sphere and assign the result to s_sphere
Clear the screen
Format the output to display the numbers in fixed format with two decimal digits
Display on the screen the message
 "The surface of a cube of sides ", side, " is ", s_cube
"The surface of a sphere of radius ", radius, " is ", s_sphere
Note: use 39 columns for text and 6 columns for the values.


You need to define four value-returning functions to implement this solution:
1) To calculate the square of a number you must define a value-returning function named square( ). It
receives a real number and returns its squared value (a real number). You must use it to calculate the
squares of side and radius. Do NOT use pow() in THIS FUNCTION to determine the square of the 
value received.
2) To calculate the surface area of the cube you must define a value-returning function named
cube_surf( ). It receives the side of the cube (a real number) and returns the calculated area (a real 
number) rounded to the second decimal digit. To round this and next area use the round_off() function 
that you created for lab 6 (see below please).
3) To calculate the surface area of the sphere you must define a value-returning function named
sphere_surf( ). It receives the radius of the sphere (a real number) and returns the calculated area (a real 
number) rounded to the second decimal digit.
4) To round a number define a value-returning function named round_off( ). It receives the number to 
be rounded (a real number) and the number of decimal digits that the number should be rounded to (a 
whole number), and returns the number rounded to the specified number of decimal digits.
The program must compile without errors or warnings.
