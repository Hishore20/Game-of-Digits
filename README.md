# Game-of-Digits



Develop a program that reads a four-digit integer from the user and displays the sum of the digits in the number. For example, if the user enters 3141 then your program should display 3+1+4+1=9.
Logic Test Case 1

Input (stdin)
9091972

Expected Output

The total sum of digits is: 37
Logic Test Case 2

Input (stdin)
25121988

Expected Output

The total sum of digits is: 36

num = int(input())

# initializing sum to zero

sum = 0

# going through every digit using every for loop

while num > 0:

    d = num%10

    num = num//10

    sum += d

    

    # we can write above code in single line

    # uncomment the below line and comment the above three lines

    # num,sum = num//10,sum+(num%10)

# printing the sum

print("The total sum of digits is:",sum)
