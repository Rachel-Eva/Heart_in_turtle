# Heart_in_turtle
## Introduction:
Turtle is a pre-installed library in Python which we use to create images.
We can use this to draw on the screen.
## Requirements:
* Python 3.0
## Explanation:
The user can use the Turtle method to animate or draw an image on the screen in Python. 
In this code, we will be drawing a red heart .
___
## Explanation:
### Importing the method:
We import the Turtle method
```
import turtle
```
### Screen:
Displays a blank screen which is what we use to draw on.
```
s=turtle.getscreen()
```
### Object:
We create an object which we use to draw.
```
t=turtle.Turtle()
```
###  Hide Turtle:
Usually while using Turtle, the cursor is present on the screen. To hide the cursor we use
this.
```
t.hideturtle()
```
### Screen colour:
Turtle allows you to change the colour of the screen. We change it to black.
```
turtle.bgcolor("black")
```
### Heart colour:
We fill the heart colour red using this function.
```
t.fillcolor("red")
```
### Filling process:
We use functions like begin_fill() to start the filling process and end_fill()
to end the filling process.

### Drawing process:
There are different functions used with Turtle to move the cursor around the screen and draw.
List of functions we use in the code:
fd() - forward
lt() - left turn
There are other functions that are available as well. Functions like,
bk() - backward
rt() - right turn

### Using shapes:
Turtle also provides functions to draw basic shapes that cannot be drawn easily.
We use one such function in our program.
circle() - draws a circle

## Program:
```
import turtle
# import the turtle method

s=turtle.getscreen()
# displays a blank screen to draw on

t=turtle.Turtle()
# creates an object

t.hideturtle()
# hides the turtle cursor from the screen

turtle.bgcolor("black")
# changes the screen colour to black

t.fillcolor("red")
# fills the heart with the colour red

t.begin_fill()
# starts the filling process

t.lt(90)
t.circle(37,180)
t.fd(5)
t.lt(10)
t.fd(10)
t.lt(10)
t.fd(5)
t.lt(25)
t.fd(100)
t.lt(90)
t.fd(100)
t.lt(25)
t.fd(5)
t.lt(10)
t.fd(10)
t.lt(10)
t.fd(5)
t.circle(37,180)

t.end_fill()
# ends the filling process
```
## Output:
![ffff](https://github.com/Rachel-Eva/Heart_in_turtle/assets/145921131/c2753cb9-bde1-4c19-a9af-9cb5a4d4cf99)

