# Assignment 5
Using JavaFX tools, write a program that plots the graphs of the following parametic equations:
1. Daisy: π₯ = πcos(6π‘) cos(π‘) , π¦ = π cos(6π‘) sinβ‘(π‘)
2. Clover: π₯ = π cos(2π‘) cos(π‘) , π¦ = π cos(2π‘) sinβ‘(π‘)
3. Cardioid: π₯ = π(1 β sin(π‘)) cos(π‘) , π¦ = π(1 β sin(π‘))sinβ‘(π‘)
4. Lissajous: π₯ = 4πsinβ‘(3π‘ + 1), π¦ = 3πsinβ‘(π‘)
5. Tricuspoid: π₯ = π(2 cos(π‘) + cos(2π‘)), π¦ = π(2 sin(π‘) β sinβ‘(2π‘))

The GUI shoule have a ComboBox. When the user selects the name of a curve from
the ComboBox, the program should display the corresponding curve. Each curve should be drawn for 0 β€ π‘ β€ 2π. Make sure that each curve is custom scaled so that the full curve fits in the window. Use the same scale factor for both x and y to preserve the shape of the curve.

## Program Requirements
- The program should contain a method (drawCurve) that draws the graph of any parametric curve.
- **Input parameters**: GraphicsContext object; two DoubleUnaryOperator types (for the functions for x and y); two doubles for beginning and end values of the parameter t; a double for the scale factor (using same for both x and y directions); and an integer for the number of straight line pieces stroked to produce the curve.