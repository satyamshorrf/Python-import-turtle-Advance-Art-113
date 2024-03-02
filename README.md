# Python-import-turtle-Advance-Art-113
Create python use import turtle graphics code
from turtle import*
from colorsys import*
title("Satyam Shorrf")
setup(width=750, height=650)
tracer(2)
bgcolor('black')
pensize(3)
h=0.5

for i in range(150):
    c = hsv_to_rgb(h,1,1)
    h+=0.003
    pencolor(c)
    left(70)
    goto(0,0)
    forward(50)
    circle(130-i*.5,90)
    backward(i*.1)
    h+=1/3
done()    
