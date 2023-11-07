from turtle import*

speed(0)

def star():
  begin_fill()
  for i in range(5):
    forward(10)
    left(144)
  end_fill()

color('dark blue')
goto(-200,200)
begin_fill()
forward(400)
right(90)
forward(400)
right(90)
forward(400)
right(90)
forward(400)
end_fill()

star()
goto(0,0)
color("red")

star()
color("white")
goto(10,30)
color("red")

star()
color("white")
goto(10,30)
color("white")

star()
color("white")
goto(-18,70)
color("blue")

star()
color("white")
goto(40,105)
color("red")

star()
color("white")
goto(55,110)
color("white")

star()
color("white")
goto(70,100)
color("white")
 
star()
