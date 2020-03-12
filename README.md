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

#triangle
sq.setposition(-280,-225)
sq.color("purple")
sq.pendown()
sq.begin_fill()
for x in range (2):
  sq.left(90)
  sq.forward(100)
sq.setposition(-280,-225)
sq.end_fill()
sq.penup()

#star
sq.setposition(230,-255)
sq.pendown()
sq.color("orange")
sq.begin_fill()
for x in range (5):
  sq.forward(120)
  sq.right(144)
sq.end_fill()
sq.penup()

#diamond
sq.setposition(13,0)
sq.pendown()
sq.color("blue")
sq.begin_fill()
sq.right(45)
sq.forward(50)
for x in range(3):
  sq.right(90)
  sq.forward(80)
sq.end_fill()


