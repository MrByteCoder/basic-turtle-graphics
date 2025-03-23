basic-turtle-graphics
=====================

A simple and visually appealing Python turtle graphics project created using the built-in turtle module. 
This script generates an intricate geometric pattern with rotating squares and circles using a few lines of code. 
Ideal for beginners learning Python graphics or anyone interested in creative coding.

-----------------------
Features:
-----------------------
- Generates colorful spiral and circular patterns
- Uses simple loops and turtle graphics
- Fast drawing with t.speed(0) for instant rendering
- Fully customizable parameters (colors, angles, repetitions)

-----------------------
Code Overview:
-----------------------

import turtle as t

t.speed(0)
t.bgcolor('black')
t.pencolor('orange')

def square(x, y):
    for j in range(4):
        t.forward(x)
        t.right(y)

for i in range(80):
    square(170, 90)
    t.right(5)
    t.circle(50)
    t.right(50)
    t.hideturtle()

t.done()

-----------------------
Requirements:
-----------------------
- Python 3.x 
- No external libraries needed

-----------------------
How to Run:
-----------------------
1. Save the code in a file named: turtle_art.py
2. Run the script using Python:
   python turtle_art.py

-----------------------
Author:
-----------------------
Devansh Mishra (MrByteCoder)
GitHub: https://github.com/MrByteCoder

-----------------------
License:
-----------------------
This project is licensed under the MIT License.
