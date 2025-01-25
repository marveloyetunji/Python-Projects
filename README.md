# Python-Projects
This is a list of my Python projects available for modifications and sharing 

Code Sample for creating a captivating turtle graphics in Python 
import turtle

# Set up the screen
wn = turtle.Screen()
wn.bgcolor("black")

# Create a turtle named "spiral"
spiral = turtle.Turtle()
spiral.speed(0)
spiral.color("cyan")

# Move the turtle to create a spiral
distance = 1
for _ in range(360):
    spiral.forward(distance)
    spiral.right(59)
    distance += 1

# Hide the turtle
spiral.hideturtle()

# Finish the drawing
turtle.done()
