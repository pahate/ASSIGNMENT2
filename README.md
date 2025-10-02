# Task 1:
# input 
Check if a Number is Even or Odd
Problem Statement:  Write a Python program that:
1. 	Takes an integer input from the user.
2. 	Checks whether the number is even or odd using an if-else statement.
3. 	Displays the result accordingly.
4. 	take 7 as odd no and 12 as even no 
   
# python code
def check_even_odd(number):
    if number % 2 == 0:
        print(f"{number} is Even.")
    else:
        print(f"{number} is Odd.")

check_even_odd(7)
check_even_odd(12)

# Task 2
# input 
Task 2: Sum of Integers from 1 to 50 Using a Loop
 
Problem Statement: Write a Python program that:
1.   Uses a for loop to iterate over numbers from 1 to 50.
2.   Calculates the sum of all integers in this range.
3.   Displays the final sum.


   # python code 
total_sum = 0


for number in range(1, 51):
    total_sum += number


print("The sum of integers from 1 to 50 is:", total_sum)
   

