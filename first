import time
import turtle
from turtle import Turtle
from random import randint

screen = turtle.Screen()
screen.title("Car Race")
turtle.bgcolor("forestgreen")
turtle.speed(0)
turtle.penup()
turtle.setpos(-140,200)
turtle.write("CAR RACE",font=("Arial",30,"bold"))
turtle.penup()

turtle.setpos(-400,-180)
turtle.color("chocolate")
turtle.begin_fill()
turtle.pendown()
turtle.forward(800)
turtle.right(90)
turtle.forward(300)
turtle.right(90)
turtle.forward(800)
turtle.right(90)
turtle.forward(300)
turtle.end_fill()

stamp_size= 20
square_size= 15
finish_line= 200
turtle.color("black")
turtle.shape("square")
turtle.shapesize(square_size/stamp_size)
turtle.penup()
for i in range(10):
    turtle.setpos(finish_line,(150-(i*square_size*2)))
    turtle.stamp()
for j in range(10):
    turtle.setpos(finish_line,((150-square_size)-(j*square_size*2)))
    turtle.stamp()
turtle.hideturtle()

# CAR 1
car1 = Turtle()
car1.speed(0)
car1.color("red")
car1.shape("square")
car1.penup()
car1.goto(-250,100)
car1.pendown()

# CAR 2
car2 = Turtle()
car2.speed(0)
car2.color("blue")
car2.shape("square")
car2.penup()
car2.goto(-250,50)
car2.pendown()

# CAR 3
car3 = Turtle()
car3.speed(0)
car3.color("yellow")
car3.shape("square")
car3.penup()
car3.goto(-250,0)
car3.pendown()

# CAR 4
car4 = Turtle()
car4.speed(0)
car4.color("black")
car4.shape("square")
car4.penup()
car4.goto(-250,-50)
car4.pendown()

time.sleep(2)
for i in range(145):
    car1.forward(randint(1,5))
    car2.forward(randint(1, 5))
    car3.forward(randint(1, 5))
    car4.forward(randint(1, 5))
turtle.exitonclick()
