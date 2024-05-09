# Calculator
Scientific and Graphing Calculator


def calculate_area(name): #this part of the code is for calculating the area of the inputed shape by the user by giving the formula
    name = name.lower()
    if name == "rectangle":
        l = int(input("Enter rectangle's length: "))
        w = int(input("Enter rectangle's width: "))
        rectangle_area = l * w
        print(f"The area of rectangle is {rectangle_area}.")
    elif name == "square":
        s = int(input("Enter square's side length: "))
        square_area = s * s
        print(f"The area of square is {square_area}.")
    elif name == "triangle":
        h = int(input("Enter triangle's height length: "))
        b = int(input("Enter triangle's base length: "))
        triangle_area = 0.5 * b * h
        print(f"The area of triangle is {triangle_area}.")
    elif name == "circle":
        r = int(input("Enter circle's radius length: "))
        pi = 3.14
        circle_area = pi * r * r
        print(f"The area of circle is {circle_area}.")
    else:
        print("not available")
