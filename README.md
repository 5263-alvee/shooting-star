import turtle
import math

t = turtle.Turtle()
t.color("red", "yellow")
t.speed(10)
t.begin_fill()

for i in range (500):
    t.forward(math.sqrt(i)*10)
    t.left(167.7)


t.end_fill()
turtle.done()
