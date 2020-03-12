# shapes5
import turtle 

sq = turtle.Turtle()

sq.speed(20)

#square
sq.penup()
sq.setposition(250,425)
sq.pendown()
sq.color("green")
sq.begin_fill()
for x in range (4):
  sq.forward(100)
  sq.right(90)
sq.end_fill()
sq.penup()

#circle
sq.setposition(-250,425)
sq.color("red")
sq.pendown()
sq.begin_fill()
sq.left(180)
sq.circle(50)
sq.end_fill()
sq.penup()
