#python

import turtle
import random
t1=turtle.Turtle()
t1.shape("turtle")
colors=["red","yellow","green","black"]
t1.color("red")

def push(x,y):
    t1.color(random.choice(colors))
    pl_a=45
    t1.left(pl_a)
    t1.forward(100)
    
t1.onclick(push)
turtle.done()
