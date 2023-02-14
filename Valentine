import turtle
import math

def love(t):
    x = 16 * (math.sin(t) ** 3)
    y = 13 * math.cos(t) - 5 * math.cos(2 * t) - 2 * math.cos(3 * t) - math.cos(4 * t)
    return x, y

turtle.setup(800, 800)
turtle.bgcolor('black')
turtle.pensize(2)
turtle.pencolor('red')
turtle.speed(0.1)

factor1 = 20
factor2 = 10
turtle.penup()

for i in range(0, 200):
    x, y = love(i)
    turtle.goto(x * factor1, y * factor1)

    turtle.pendown()

turtle.penup()
turtle.goto(-150, -30)
turtle.pendown()
turtle.write("Happy Valentine", font=("Verdana", 25, "bold"))
turtle.penup()
turtle.goto(-80, -70)
turtle.pendown()
turtle.write("My Love", font=("Verdana", 25, "bold"))

turtle.exitonclick()
