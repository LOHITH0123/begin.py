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




