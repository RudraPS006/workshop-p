# workshop-p
work shop of python

# Printing string
print("Hello World")

# Printing variables
name = "Rudra"
age = 18
print(name)
print(age)

# Printing multiple values
name = "Rudra"
age = 18
print("Name:",name,"Age:",age)

# Printing Formatted string literals
name = "Rudra"
age = 18
print(f"Name:{name},Age:{age}")

# Using .format method
name = "Rudra"
age = 18
print("Name:{},Age:{}".format(name,age))

# Using string concatenation
name = "Rudra"
age = 18
print("Hello,"+name+"!")

# Using sep parameter
print("Apple","banana","cherry", sep=",")
print("NIET","Greater","Noida", sep="-")

# Using end parameter
print("Hello",end=" ")
print("World !")

# Print Escape Sequences
print("Rudra\nPratap\nSingh") #New line 

a = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
print(a)

a = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
print(a[0:5])

a = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
print(a[-6:-1])

list = ["apple",5,8,2.6,"cherry",6,9,7,2,1]
print(list)
print(list[1])
print(list[0])
print(list[-4])
print(list[0:6])     
print(list[-7:-3])
print(list[1+2])
print(list[:5])
print(list[6:])
print(list[1:6:3])
print(list[0:2-3:4])
print(list[0:2-3:6])

x = "10"
y = int(x)+5
print(y)

print(5+2)
print(5-2)
print(5*2)
print(5%2)
print(5//2)
print(5**2)
print(5==6)
print(5==5)
print(5!=3)
print(3!=5)
print(5>=5)

x = True
y = False
print(x and y)

x=2
y=1
print(x or y)

# Bit wise operator
x=5
y=3
print(x&y) #AND GATE
print(x|y) #OR GATE
print(x^y) #XOR GATE
print(~x) #NOT GATE
print(5 << 3) #BITWISE LEFT SHIFT
print(5 >> 3) #BITWISE RIGHT SHIFT

x=int(input("Enter number"))
print(x+3)

x=4
y=4
print(x is y)

x=6
y=3
print(x is y)

# Identity Operator
x=int(input("Enter the x's number"))
y=int(input("Enter the y's number"))
print(x is y)

x=int(input("Enter your first number"))
y=int(input("Enter your second number"))
print(x is not y)       

x = [1,2,3]
y = [1,2,3]
z= x
print(x is y)
print(x is not y)
print(x is z)
print(z is y)
print(id (x))
print(id (y))
print(id (z))

fruits = ["Banana","Apple","Cherry"]
print("Apple" in fruits)
print("Apple" not in fruits)
print("Pineapple" in fruits)

x= [2**4*3+5-6]
print(x)

x= 5, 7, 8
y= 5, 7, 8
print(x is y)

# Bracket was the issue
x = 1,2,3
y = 1,2,3
z= x
print(x is y)
print(x is not y)
print(x is z)
print(z is y)

# Write a python program to print sum of two numbers
num1= int(input("Enter the first number"))
num2= int(input("Enter the second number"))
sum= num1+num2
#print("Sum =",sum)
print("The Sum of {0} and {1} is {2}".format(num1,num2,sum))

# Write a Python program to find the square root.
num= float(input("Enter a number"))
num_sqrt= num**0.5
print("The Square root of num",num_sqrt)
print("The Square root of %0.3f is %0.3f"%(num,num_sqrt))

# Write a python program to calculate the area of triangle.
a= float(input("Enter first side: "))
b= float(input("Enter second side: "))
c= float(input("Enter third side: "))
s= (a+b+c)/2
area= (s*(s-a)*(s-b)*(s-c))**0.5
print(area)
print("The area of the triangle is ", area)
print(f"The area of triangle is {area}")
print("The area of trianglr of {}, {} and {} is {}".format(a,b,c,area))
print("The area of the triangle is %0.2f"%area)

# write a python program to solve Quadratic Equation.

a= float(input("Enter a's value"))
b= float(input("Enter b's value"))
c= float(input("Enter c's value"))
d= (b**2)-(4*a*c)
sol1= (-b-(d)**(0.5))/2*a
sol2= (-b+(d)**(0.5))/2*a
print("The solution are {} and {}".format(sol1,sol2))
      
# Login 
id= input("Enter ID: ")
password= input("Enter Password: ")          
if(id=="user@gmail.com" and password=="123"):
 print("login successfully compleated")
else:
    print("incorrect")


text= "Python Pragramming"
#print(text[4])
#print(text[0:7])
#print(text[:5])
#print(text[8:])
#print(text[5:8:2])
#print("python" in text)
#print("cobra" in text)
#print(text.lower())
#print(text.upper())
#print(text.strip())

#words= text.split()
#print(words)

x= ("banana", "apple", "cherry")
y= list(x)
y[1]= "Grape"
x= tuple(y) #tuðple is for conversion
print(x)

# write a python program to swap two variables without third variable:
a=int(input ("Enter first number:"))
b=int(input ("Enter second number:"))
print("before swapping:")
print("a=",a)
print("b=",b)
print("after swapping:")
a,b=b,a
print("a=",a)      
print("b=",b)

# write a python program to swap two variables with third variable:
a=int(input ("Enter first number:"))
b=int(input ("Enter second number:"))
print("The value of a before swapping:{}".format(a))
print("The value of a before swapping:{}".format(b))
c=a
a=b
b=c
print("The value of a after swapping:{}".format(a))
print("The value of a after swapping:{}".format(b))

# Write a python program to covert killometer to miles:
kilometers=float(input("Enter value in kilometers"))
conv_fac=0.621371
miles=kilometers*conv_fac
print("%0.2f kilometers is equal to%0.2f miles"%(kilometers,miles))

# write a python program program to seconds to days , hours, minutes,seconds
time=float(input("input time in seconds: "))
day=time//(24*3600)
time=time%(24*3600)
hour=time//3600
time%=3600
minutes=time//60
time%=60
seconds=time
print("d:h:m:s->%d,%d,%d,%d"%(day,hour,minutes,seconds))

# write a python program to compute the distance between the
# point (x1,y1)and (x2,y2)
x1=int(input("Enter x1: "))
x2=int(input("Enter x2: "))
y1=int(input("Enter y1: "))
y2=int(input("Enter y2: "))
result=((((x2-1**2)+((y2-y1)**2))**0.5))
print("distance between ",(x1,x2),"and",(y1,y2),"is: ",result)


# condition statement
d= {
    name: "Rudra"
    address: "greater noida"
    id: "123"
    }
d[address]: "delhi"
print(d)

age= int(input("enter the age"))
if age>18:
         print("you can vote")
else:
     print("you cannot vote")

# WAP program to check email id and password.
email= input("Enter email")
password= input("Enter password")
if email=="rudra@gmail.com" and password=="123":
    print("Welcome")
elif password !="123":
    print("try again")
    password=input("Enter correct password")
    if password== "123":
        print("correct password")
    else:
        print("try again")
else:
    print("incorrect password")
  



email= input("Enter email")
password= input("Enter password")
if"@" in email:
   if email=="rudra@gmail.com" and password=="123":
      print("Welcome")
   elif password !="123":
      print("try again")
      password=input("Enter correct password")
      if password== "123":
         print("correct password")
      else:
          print("try again")
   else:
       print("incorrect password")
else:
    print("please enter correct password")



# writw a python program to check year is leap year or not.
year= int(input("Enter a year"))
if(year%4==0 and year%100!=0) or year%400==0:
    print("year is leap year")
else:
    print("not leap year")

#                        or

a = int(input("Enter the year: "))
if a%4 == 0 and a%100 != 0:
    if a%400 == 0:
        print("Year is a leap year")
    else:
        print("Year is not a leap year")
else:
    print("Year is  a leap year")
    

# write a python program to check a number is divisible by both 4 and 6.


# write a python program that check foe following condition
#if the light is green-"car is allowed to go"
#if the light is yellow-" car has to wait"
#if the light is red-" car has to stop"
#other signal-" unrecognised signal"

signal=input("what is a traffic signal?: ")
if signal=="Red":
    print("car has to stop")
elif signal=="yellow":
    print("car has to wait")
elif signal=="green":
    print("car is allowed to go")
else:
    print("unauthorised signal")

# write a python program to check students grades.
name=input("Enter Student name: ")
Class=input("Enter class: ")
section=input("Enter section: ")
grade=input("Enter Student grade: ").upper()
print("Name:",name)
print("Class:",Class)
print("grade:",grade)
if grade=="A":
    print("Grade: outstanding")
elif grade=="B":
    print("Grade: Excellent")
elif grade=="C":
    print("Grade: Very Good")
elif grade=="D":
    print("Grade: Good")
elif grade=="E":
    print("Grade: Satisfactory")
elif grade=="F":
    print("Grade: padh le bsdk")
else:
    print("Unauthorised Grade")

# while loop example
count= 1
while count<=5:
     print(count)
     count += 1
else:
    print("Loop completed")

# for loop example
list= [1,2,3,4,5]
for i in list:
      print(i)
      
# Break
for i in range(5,10):
    if i== 8:
        break;
    print(i)
# continue statement: skips the current iteration and moves
#to the next one.

for i in range(5):
    if i==3:
        continue
    print(i)

# pass statement: a placeholder that does nothing, it is used to
#when a statement a syntactically required.
for i in range(5):
    if i==3:
        pass
    print(i)

# write a python to display the multiplication table.
Output:     
#12 x 2 =24
#12 x 3 =36
#12 x 4 =48
   :
   :
#12 x 10 =120
num= int(input("Display multiplication table of ?"))
# interate 10 times from i=1 to 10
for i in range(1,11):
    print(num,"x",i,"=",num*i)

# write a python program to print sum of n natural numbers
n= int(input("Enter number"))
sum= 0
i=1
while i<=n:
    sum=sum+i
    i=i+1
print(sum)

# write a python program to check whether a number is prime no. or not
num = int(input("Enter a number to chech it is prime or not"))
count = 0
i= 1
while i<=num:
      if num%i==0:
           count = count+1
      i=i+1
if count==2:
      print("Prime Number")
else:
    print("Not prime number")

# Write a pytho program to print all prime numbers in an interval.
#interval: 11-25(11,13,17,19,23)
start= int(input("Enter first number: "))
end= int(input("Enter last number"))
for i in range(start, end+1):
    if i>1:
        for j in range(2,i):
             if i%j== 0:
                   break;
             else:
                   print(i)

# write a python program to check armstrong number
#153= 1**3+5**3+3**3=1+125+27=153
num= int(input("Enter a number"))
n=len(str(num))
sum=0
temp=num
while temp>0:
      digit= temp%10
      sum=sum+digit**n
      temp=temp//10
if sum==num:
     print("Armstrong Number") 
else:
      print("Not Armstrong Number")

#write a python program to find the factorial of an integer number.
num= int(input("Enter a number")

# pattern print- nested loop
#*****
#*****
#*****
#*****
#*****
num= 5
for i in range(num):
    for j in range(num):
        print("*",end="")
    print()    

#*
#**
#***    
#****
#*****
num= int(input("Enter a number"))
for i in range(num):#0
    for j in range (i+1):#1
        print("*",end="")
    print()    
#1
#12
#123
#1234
#12345
num= int(input("Enter a number"))
for i in range(num):#0
    for j in range (i+1):#1
        print(j+1,end="")
    print()

#1
#11
#222
#3333
#44444
num= int(input("Enter a number"))
for i in range(num):#0
    for j in range (1,i+1):#1
        print(i,end="")
    print()

#A
#AB
#ABC
#ABCD
#ABCDE
num= int(input("Enter a number"))
for i in range(num):#0
    for j in range (i+1):#1
        print(chr(j+ord("A")),end="")
    print()

#*****
#****
#***
#**
#*
num= int(input("Enter a number"))
for i in range(num):#0
    for j in range (1,num-i+1):#1
        print("*",end="")
    print()

#    A
#   AB
#  ABC
# ABCD
#ABCDE
size= int(input("Enter a number"))
for i in range(size):
    for j in range (1,size-i):
        print(" ",end="")
    for k in range(i+1):
        print(chr(65+k),end="")
    print()]

#12345
#1234
#123
#12
#1
num= int(input("Enter a number"))
for i in range(num):#0
    for j in range (1,num-i+1):#1
        print(j,end="")
    print()

#    1
#   212
#  32123
# 4321234
num=int(input("Enter the number"))
for i in range(1,num+1):
    for j in range(1,num-i+1):
        print(" ",end="")
    for j in range(i,0,-1):
        print(j,end="")
    for j in range(2,i+1):
        print(j,end="")
    print()


# print smiley face
def print_smiley_face():
    smiley = [
        "   *****   ",
        " *       * ",
        "*  O   O  *",
        "*    ^    *",
        "*   \\_/   *",
        " *       * ",
        "   *****   "
    ]
    
    for line in smiley:
        print(line)

# Call the function to print the smiley face
print_smiley_face()

   * 
  ***
 *****
*******
num=int(input("Enter the number"))
for i in range(1,num+1):
    for j in range(1,num-i+1):
        print(" ",end="")
    for j in range(i,0,-1):
        print("*",end="")
    for j in range(2,i+1):
        print("*",end="")
    print()


# calculator
def calculate(num1,num2):
    add= num1+num2
    sub= num1-num2
    multiply= num1*num2
    div= num1/num2
    return add, sub, multiply, div
a,b,c,d= calculate(10,5)
print(a,b,c,d)

num1= int(input("Enter a number"))
num2= int(input("Enter a number"))          
def calculate(num1,num2):
    add= num1+num2
    sub= num1-num2
    multiply= num1*num2
    div= num1/num2
    return add, sub, multiply, div
ok= calculate(num1,num2)
print(ok)

def value(a,b):
   return a+b
print(value(10,5)) 

# write a python program to print add, sub, multiply, divide
def value(a,b):
    a+b
    a-b
    a*b
    a/b
    return sum, sub, mul, div
a,b,c,d= value(10,5)
m,n,o,p= value(12,6)
print(a,b,c,d)
print(m,n,o,p)


def my_function(fname, lname):
    print("My name is {} and the last name is {}" .format(fname, lname))
my_function("Rudra Pratap", "Singh")

# POSITIONAL ARGUMENT
def name(fname, lname):
    print("My name is {} and last name is {}" .format(fname, lname))
name("Rudra Pratap", "Singh")

# KEYWORD ARGUMENT
def name(fname, lname):
    print("My first name is {} and my last name is {}" .format(fname, lname))
    name(lname = "Singh", fname = "Rudra Pratap")
# default argument
def name(fname, lname = "Singh"):
    print("My name is {} and last name is {}" .format(fname, lname))
name("Rudra Pratap")

# variable-lenght positional argument
def sum_num(num1, *num):
    result = num1
    for i in num:
        result+=i
    return result
r = sum_num(10, 20, 30)
print("The sum of numbers is {}" .format(r))

# variable-length keyword arguments
def fun_name(**name):
    print(f" My first name is {name['fname']} and second name is {name[']})
fun_name(fname="Rudra Pratap",lname="Singh")

#variable a python to check even and odd number using function

# scope rules example
global_var="Hello,Welcome to NIET"
def func1():
    'Scope Rules'
    local_var="Hi, I am Rudra"
    print(local_var)
    print(global_var)
func1()
print(global_var)
print(local_var)

# Namespace
global_var=88
def my_function():
    local_var=222
    print(local_var,global_var)
my_function()

#Recursion
# WAP to print factorial number
def fact(num):
    if num==0:
        return 1
    else:
        return num*fact(num-1)
n= int(input("Enter a number"))
f= fact(n)
print(f"THE FACTORIAL OF {n} IS: {f}")

# WAP to print fibonacci number
def fibonacci(n):
    if n<=1:
        return n
    return fibonacci(n-1)+fibonacci(n-2)
num_terms=int(input("Enter a number"))
print(f"Fibonacci sequence for {num_terms} terms: ")
for i in range(num_terms):
    print(fibonacci(i))
#Write a recurssive function to find the sum of all the elements in a list
def sum_list(list):
    if not list:
        return 0
    else:
        return list[0]+sum_list(list[1:])
numbers= [1,2,3,4,5,6]
result= sum_list(numbers)
print(result)

# Write a recurssive function to print length of a string.
# 1+length_of_string(s[1:])
def length_of_string(s):
    if s=="":
        return 0
    else:
        return 1+length_of_string(s[1:])
print(length_of_string("Hello, welcome to NIET"))

#write a recursive of function to print exponentiation(power of a number)
#base*power(base'exponent-1)
def exp(base,exponent):
    if exponent==0:
        return 1
    else:
        return base*exp(base,exponent-1)
result= exp(2,5)
print(result)
# Handle negative exponents
def exp(base, exponent):
    if exponent == 0:
        return 1
    elif exponent > 0:
        return base * exp(base, exponent - 1)
    else:
        return 1 / exp(base, -exponent)

# wrire a recursive function to calculate the sum of numbers from 1 to n.
def sum_of_numbers(n):
    if n==1:
        return 1
    else:
        return n+sum_of_numbers(n-1)
num=int(input("Enter a number "))
result= sum_of_numbers(num)
print(result)

#WAP program using function to check weather two numbers are equal or not.
#write a program using functions to swap two numbers.
#write a program using function to return the full name of a person using seperator.
#WAP program using function to return the average of its arguments

# WAP program using function to check weather two numbers are equal or not.
def check_equal(num1,num2):
   if num1==num2:
       return true
   else:
        return false
     
num1= float(input("enter the number"))
num2= float(input("enter the number"))
if num1==num2:
  print("number is equal")
else:
       print("number is not equal")

# write a program using functions to swap two numbers.
def swap_numbers(a,b):
    return b,a
a=float(input("Enter a number"))
b=float(input("Enter a number"))
a,b= swap_numbers(a,b)
print(f"After swaping first number is: {a}")
print(f"After swaping second number is: {b}")

# write a program using function to return the full name of a person using seperator.
def full_name(first_name, last_name, separator=" "):
    return separator.join([first_name, last_name])
first_name = input("Enter your first name: ")
last_name = input("Enter your last name: ")
full_name_result = full_name(first_name, last_name, separator=" ")
print(f"Full name: {full_name_result}")

#WAP program using function to return the average of its arguments.

# simple function
def function_name():
    a=int(input("Enter a's value: "))
    b=int(input("Enter b's value: "))
    c=int(input("Enter c's value: "))
    result=a+b+c
    return result
print(function_name())

# Anonymous/lambda function
result= lambda a,b,c: a+b+c
print(result(10,20,30))

# filter function
numbers= [1,2,3,4,5,6,7,8,9,10]
def is_even(n):
    if n%2==0:
        return True
even_numbers= filter(is_even,numbers)
even_numbers_list= list(even_numbers)
print(even_numbers_list)

# Sequence
list=[1,2,3,4,5,6]
print(list)

# packing
packed= (1,2,3,4,5,6,"Hello")
print(packed)

# unpacking
a,b,c= "Hello",345,"World"
print("a=",a,"b=",b,"c=",c)
print("id=",id(a),"length of a=",len(a))
print("id=",id(b),"length of b=",len(str(b)))
print("id=",id(c),"length of c=",len(c))


def return_multiple():
    return 5,6,7
val1,val2,val3= return_multiple()
print(val1,val2,val3)

# Mutable
list=[1,4,6,3]
list[1]="Hello world!"
print(list)

# immutable
text="Hello,world!"
text[0]="e"
print(text)

#write a python program to check how many duplicate number are existed in a string
# write a python program to add value in a list using append method from old list
my_list = []
value = input("Enter a value to add to the list: ")
my_list.append(value)
print("Updated list:", my_list)'''


old_list = [1, 2, 3, 4, 5]
print("Old List:", old_list)
value = input("Enter a value to add to the list: ")
old_list.append(value)
print("Updated List:", old_list)Make a note of list
