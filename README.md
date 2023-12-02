# Heart_in_turtle
## Introduction:
Using the Turtle method to animate a heart in python.
## Requirements:
* Python 3.0
## Explanation:
The user can use the Turtle method to animate or draw an image on the screen in Python. 
In this code, we will be drawing a red heart .
___
## Explanation:
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
```
