a=int(input("Enter num1: "))
b=int(input("Enter num2: "))
c=int(input("Enter num3: "))
if (a > b and a < c) or (a > c and a < b):
    second_highest = a
elif (b > a and b < c) or (b > c and b < a):
     second_highest = b
elif (c > a and c < b) or (c < a and c > b):

    second_highest = c
print("The second highest number is:", second_highest)
