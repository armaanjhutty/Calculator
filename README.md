Scientific Calculator Python Code

Libraries used in code Matplotlib and Numpy

def main() this part of the code is actually what runs first when you run the code, this prompts the user to enter either "math, shape, or graph." Math for mathemitacal expressions, shape for calculating the area of certain shapes, and graph to print a trig graph, polynomial or quadratic with linear lines. If the user chooses math it will prompt the user to enter two different numbers in order to perfrom the calculations, and if shape is chosen it will prompt the user for a rectangle, circle, triangle, or square. This will then send this input to the def calculate_area(name) function that is used to calcualte the area using two user given inputs. The graph function will take it to the various different graph codes in with the given input in order to actaully print the graph. If the user enters sin, cos, or tan it will print the basic trig graphs for these ratios. If the user enters quadratic it will prompt the user to enter an equation in order to print the graph of. It then again prompts the user to print a linear graph if chosen in order to be plotted on the same graph as the quadratic. If polynomail is choosen it will prompt the user to input an equation to plot the graph, it will then prompt for a linear graph similar to the quadratic code.

def calculate_area(name) this function is used to actually be able to give the formula to calculate the area of each of the shapes (rectangle, square, circle, and triangle), this function works under the prompt from the main function

def quadratic(a, b, c) this function takes the coefficients of a quadratic equation as input and returns the roots (solutions) of the equation. The nature of the roots (real or complex) depends on the value of the discriminant.

In summary the overall goal of this project was to compile all math functions such as adding, subtratcing, multiplying, dividing, and exponents along with calculating area of a square, circle, triangle, and rectangle along with graphing different graphs like sin, cos, tan, quadratic and polynomial graphs with POI with a linear line. Through various different user inputs in forms of numbers, formulas, and equations it allows the code to do any of the above math functions in a matter of seconds. 
