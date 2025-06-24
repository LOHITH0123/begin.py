# begin.py
print("hi everyone")

#integer
age = 30
print("Age:")

#float
price = 999.99
print("Price:")

#string
name = "Lohith"
print("Name:")

#boolean
is_logged_in = True
print("Logged in?")

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

#types of operators
    (1) Arthematic
a = 10
b = 3
print(a+b)
print(a-b)
print(a*b)
print(a/b)
print(a%b) #modulus
print(a**b)#exponents


  (2) Comparison Operators
a=10
b=4
print(a == b)
print(a != b)
print(a > b)
print(a <= b)


  (3) Assignment Operators
x = 5
x += 3  # same as x = x + 3
print(x)
y=8
y-=4
print(y)


  (4) Logical
is_sunny = True
is_warm = False
print("AND:", is_sunny and is_warm)
print("OR:", is_sunny or is_warm)
print("NOT:", not is_sunny)


  (5) Bitwise Operators
print(a & b) #and
print(a | b) #or
print(a ^ b) #xor


   (6) Identity
x = [1,2]
y = x
z = [1,2]
print(x is y)     # True (same object)
print(x is z)     # False (different object)
print(x == z)     # True (same values)


  (7)  Membership Operators
colors = ["red", "blue", "green"]
print("blue" in colors)
print("yellow" not in colors)




# Check if user is eligible to vote
age = int(input("Enter your age: "))
if age >= 18:
    print("You are eligible to vote.")
else:
    print("You are NOT eligible to vote.")


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------


#for loops
nums=[1,2,3,4,5]
for num in nums:
    print(num)
    
#break
for num in nums:
    if num==3:
        print("Found1")
        break
    print(num)

#continue
nums=[1,2,3,4,5]
for num in nums:
    if num==3:
        print("Found!")
        continue
    print(num)
    

#inner loop
nums=[1,2,3,4,5]
for num in nums:
    for letter in 'abc':
        print(num, letter)

#while loop
x=1
while x<10:
    if x==5:
        break
    print(x)
    x +=1

 #infiniet loop
x=1
while True:
    print(x)
    x +=1

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------


#search for an element in list using loops

nums=[11,3,55,63,2]
target=int(input("Enter num to search: "))
found=False

for num in nums:
    if num == target:
        found=True
        break

if found:
    print(target, "found in list")
else:
    print(target, "not found")

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# To create tables

num=int(input("Enter your number:" ))
for n in range(1,11):
    print(num,'*',n,'=',num*n)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Patterns

for i in range(1,6):
    for j in range(1,i+1):
        print("#", end="")
    print("\n")


for i in range(5,0,-1):
    for j in range(1,i+1):
        print("$",end="")
    print("\n")


for i in range(1,6):
    for k in range(1,6-i):
        print(" ",end="")
    for j in range(1,1+i):
            print("&",end="")
    print("\n")


for i in range(5,0,-1):
    for k in range(1,6-i):
        print(" ",end="")
    for j in range(1,1+i):
            print("&",end="")
    print("\n")

for i in range(1,6):
    for k in range(1,6-i):
        print(" ",end="")
    for j in range(1,(2*i-1)+1):
            print("&",end="")
    print("\n")


for i in range(5,0,-1):
    for k in range(1,6-i):
        print(" ",end="")
    for j in range(1,(2*i-1)+1):
        print("!",end="")
    print("\n")

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Check if no is positive negative or zero

num=int(input("Enter your number: "))
if num>0:
    print("Positive no")
elif num<0:
    print("Negative no")
else:
    print("Zero")

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Area and Perimeter of Square
Write a program to find the area and perimeter of square whose side length is 4.5. On the first line, print square's area and on the second line, its perimeter.


side=4.5
area=side*side
perimeter=4*side

print(area)
print(perimeter)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# To find length of string


1.method(using split fun)
sentence = "Coding on CodeChef"
words = sentence.split()

for word in words:
    print(f"{word} - {len(word)}")

print(f"{sentence} - {len(sentence)}")



2.normal method
name="Coding on CodeChef"
print("Coding -",len("Coding"))
print("on -",len("on"))
print("CodeChef -",len("CodeChef"))
print("Coding on CodeChef -",len(name))

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Reversing the string

1.normal method
text="I Love Python"
reversed_text=""

for char in text:
    reversed_text=char+reversed_text
    
print(reversed_text)



2.using slicing
text=("I Love Python")
reversed_text=text[::-1]
print(reversed_text)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Area of circle
Write a program that takes the radius of a circle as input and prints its area
formula to calculate area of circle: 3.14*radius*radius

radius=float(input())
area=3.14*radius*radius
print(area)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Print the sentence
Write a program that takes the two different strings as input and prints them in a single line separated by spaces.

str1=input()
str2=input()
print(str1,"",str2)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Greet
Write a program that takes an input string - the name of a person and prints Hello and name of the person with a space between them.

name=input()
print(f"Hello",name)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

######################
What will the following code return as the output if the 1st line of input is 1 and the 2nd line of input is 2?

a = input()
b = input()
c = a + b
print(c)

===>>>>> 12

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

when 2 variables need to find
x, y=map(int,input().split())
print(x*y)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------


