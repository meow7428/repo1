# repo1
import turtle
import math
t=turtle.Turtle()
t.speed(0)
t.pensize(2)
t.left(90)
t.color("brown")
def tree(i):
    if i<10:
        return
    else:
        t.forward(i)
        t.color("pink")
        t.circle(2)
        t.color("brown")
        t.left(20)
        tree(4*i/5)
        t.right(40)
        tree(4*i/5)
        t.left(20)
        t.backward(i)
t.penup()
t.goto(0,-150)
t.pendown()
tree(70)
t.hideturtle()
turtle.done()
