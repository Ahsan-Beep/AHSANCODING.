# AHSANCODING.
this is my first github Repository
a = 7
b = 9
print(a)
c = a + b

print(c)

d =a/b
print(d)


e = a//b #removes decimal and round off the value 
print(e)

f = a - b

print(f)
a = 5          # Numeric Types   :int,float,complex
b ="house"     # Text Type  :str
c = -2         # Numeric Types  :int,float,complexd = False      # Boolean Types  : bool
e = ("apple","bannana","mango") # tuple : list :  lement can be change after adding
f = ["apple","bannana","mango"] # ;list : element can be change after adding
g = {"name":"John","age":"19"} # Dict: in dict we can assign data to its own data


print(type(a))
print(type(b))
print(type(c)) 
print(type(d))
print(type(e))
print(type(f))
print(type(g))


a = ("apple","bannana","cherry")
b = list(a) # here we will convert tuple in a list for updating element in it
b[1] = "dates"
a = tuple(b) # again converted to tuple
print(a)


honda =("civic","city","swift")
b=list(honda)
b[2]="city"
honda = tuple(b)
print (honda)

toyota= ("fortuner","land cruiser")
d= list(toyota)

d.append("supra")

toyota = tuple(d)

print (toyota)


# added an element

#replaced an element

family = ("father","mother","brother","me")
e = list(family)
e.append("little sister") # added a element 
family = tuple(e)
print(family)
family2 = ("father","mother","brother","me")
f = list(family2)
f.append("little sister") # added and removed a element 
f.remove("me")
family2 = tuple(f)
print(family2)

languages = ['python', 'swift', 'Engish', 'Urdu', 'Hindi', 'Sindhi']

# access elements of the list one by one
for i in languages:
    print(i)

number = 1


word="anaconda"
for letter in word:
	print (letter)

word="Tiger"
for letter in word:
	print (letter)


while number <= 7:
    print(number)
    number = number + 1

    # creating a dictionary
country_capitals = {
  "Germany": "Berlin", 
  "Canada": "Ottawa", 
  "England": "London"
}

# printing the dictionary
print(country_capitals)


# An empty loop 
a = 'geeksforgeeks'
i = 0
  
while i < len(a): 
    i += 1
    pass
    
print('Value of i :', i) 


a = int(input('Enter a number (-1 to quit): ')) 
  
while a != -1: 
    a = int(input('Enter a number (-1 to quit): ')) 


while a != -1:
    a + int(())
def tryMatching(value):
    if value < 5:
        print('value < 5')
    elif value > 8:
        print('value > 8')
    else:
        print('value is different')


tryMatching(6)



number = 0

if number > 0:
    print('Positive number')

elif number <0:
    print('Negative number')

else:
    print('Zero')

print('This statement is always executed')
  

number = 10

if number > 0:
    print('Number is positive')

print('This statement always executes')

 
number = 5

if number >= 0:
   
    if number == 0:
      print('Number is 0')
      
    else:
        print('Number is positive')


marks = int(input("enter student marks : "))

if (marks >= 90):
    grade = "A"
elif(marks >= 80 and marks < 90):
    grade = "B"
elif(marks >= 70 and marks < 80):
    grade = "C"
else: 
    grade = "D"

print("grade of the student ->", grade)



age = 14
if (age >= 18):
  print("CAN VOTE")
else:
    print("CANNOT VOTE")


age = 17
if (age >= 18):
   print("CAN DRIVE CAR")
else:
    print("CANNOT DRIVE CAR")# function defination 
def calc_sum(a, b): #parameters
    return a + b


  
calc_sum(9,42) #function call;arguments

calc_sum(70,90)

     
sum = calc_sum(105,136) #12
print(sum)



print('Python is powerful')

print('Good Morning!')
print('It is rainy today')


# print with end whitespace
print('Good Morning!', end= ' ')

print('It is rainy today')


print('New Year', 2023, 'See you soon!', sep= '. ')

number = -10.6

name = "Programiz"

# print literals     
print(5)

# print variables
print(number)
print(name)

print('Programiz is ' + 'awesome.')

x = 5
y = 10

print('The value of x is {} and y is {}'.format(x,y))

# using input() to take user input


print('You Entered:', num)

print('Data type of num:', type(num))

# using input() to take user input
num = input('Enter a number: ')

print('You Entered:', num)

print('Data type of num:', type(num))

Alphabets = "A,B"
for Alphabet in Alphabets:
    print(Alphabet)

    #write a function to take a input of a number and define it wheather its even or odd
# number = int(input("enter any number to find out it is odd or even: "))
# if (number % 2) == 0:
#     print("The number is even")
# else:
#     print ("The provided number is odd")

n = int(input(" Enter any number: "))

def even(n):
    if n%2 == 0:
        print("its even")
    else:
        print("Its odd")

even(n)
class Parrot:

    # class attribute
    name = ""
    age = 0

# create parrot1 object
parrot1 = Parrot()
parrot1.name = "Blu"
parrot1.age = 10

# create another object parrot2
parrot2 = Parrot()
parrot2.name = "Woo"
parrot2.age = 15

# access attributes
print(f"{parrot1.name} is {parrot1.age} years old")
print(f"{parrot2.name} is {parrot2.age} years old")
# base class
class Animal:
    
    def eat(self):
        print( "I can eat!")
    
    def sleep(self):
        print("I can sleep!")

# derived class
class Dog(Animal):
    
    def bark(self):
        print("I can bark! Woof woof!!")

# Create object of the Dog class
dog1 = Dog()

# Calling members of the base class
dog1.eat()
dog1.sleep()

# Calling member of the derived class
dog1.bark();

class Computer:

    def __init__(self):
        self.__maxprice = 900

    def sell(self):
        print("Selling Price: {}".format(self.__maxprice))

    def setMaxPrice(self, price):
        self.__maxprice = price

c = Computer()
c.sell()

# change the price
c.__maxprice = 1000
c.sell()

# using setter function
c.setMaxPrice(1000)
c.sell()


class Polygon:
    # method to render a shape
    def render(self):
        print("Rendering Polygon...")

class Square(Polygon):
    # renders Square
    def render(self):
        print("Rendering Square...")

class Circle(Polygon):
    # renders circle
    def render(self):
        print("Rendering Circle...")
    
# create an object of Square
s1 = Square()
s1.render()

# create an object of Circle
c1 = Circle()
c1.render()
input ("enter your name: ")  

name = input("enter your name: ")
print("Welcome ", name)


name = input("enter your age: ")
print("you entered", name)


val = input("enter some value: ")
print(type(val), val) # "25", "99.99"

name = input("enter your name: ")
age = int(input("enter age: "))
marks = float(input("enter marks: "))

print("welcome",name)
print("age= ",age)
print("marks= ",marks)

a =int(input("enter first: "))
b =int(input("enter second: "))

print(a >= b)

name = input("Enter your name: ")
print(name)

# Output: 
# Enter your name: James
# James

input('prompt')

# get input from user
inputString = input('Enter a string: ')

print('Input String :', inputString)
