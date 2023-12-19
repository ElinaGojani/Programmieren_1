Tag 1: While Schleife
durchgang = 1
while durchgang < 11:
    print(durchgang)
print("nach der Schleife")

Tag 2: Listen
# Listen in Python
vornamen = ['Axel', 'Elke', 'Martin']
print(vornamen[1])

Tag 3: Rechenoperationen
print(2*(3+3)*4) 
print(4-1)   # Subtraktion
print(17/8)  # Division
print(6%4)   # Division mit Rest
print(5**2)  # Quadratwurzel

Tag 4: Matrices
# Program to multiply two matrices using list comprehension

# 3x3 matrix
X = [[12,7,3],
    [4 ,5,6],
    [7 ,8,9]]

# 3x4 matrix
Y = [[5,8,1,2],
    [6,7,3,0],
    [4,5,9,1]]

# result is 3x4
result = [[sum(a*b for a,b in zip(X_row,Y_col)) for Y_col in zip(*Y)] for X_row in X]

for r in result:
   print(r)


Tag 5: Chekc if a list is empty
my_list = []
if not my_list:
    print("the list is empty")

Tag 6 : Reverse a number using while loop
num = 1234
reversed_num = 0

while num != 0:
    digit = num % 10
    reversed_num = reversed_num * 10 + digit
    num //= 10

print("Reversed Number: " + str(reversed_num))

Tag 7: turtle
import turtle
import time
import random

ws = turtle.Turtle()
ws.speed(0)
ws.color("blue")

for j in range(1,100):
    for i in range(1,6):
        ws.left(144)
        ws.forward(200)
    ws.left(5)
turtle.done()

Tag 8: Copy a file
from shutil import copyfile
copyfile("/root/a.txt", "/root/b.txt")

Tag 9: Using datetime
from datetime import datetime

my_date_string = "Mar 11 2011 11:31AM"

datetime_object = datetime.strptime(my_date_string, '%b %d %Y %I:%M%p')

print(type(datetime_object))
print(datetime_object)

Tag 10: 
my_string = '''The only way to
learn to program is
by writing code.'''

print(my_string)

Tag 11:
my_dict = {31: 'a', 21: 'b', 14: 'c'}

del my_dict[31]

print(my_dict)

Tag 12:
x = float(1)
y = float(2.8)
z = float("3")
w = float("4.2")
print(x)
print(y)
print(z)
print(w)


Tag 13:
a = "Hello, World!"
print(a.upper())




