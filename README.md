# -Control-Structures-in-Python
Control structures determine how the flow of execution moves through your Python program. They help you make decisions, repeat actions, and control the logic of your code.
Conditional Statements (Decision Making)
num % 2 → gives the remainder when num is divided by 2.

If the remainder is 0, the number is even.

Otherwise, it’s odd.
Q1) n = int(input("Enter a  number: "))
if n % 2==0:
  print(f"{n} is an even number")
else:
  print(f"{n} is an odd number") 
Output: Enter a  number: 7
7 is an odd number
Enter a  number: 12
12 is an even number

Q2) total_sum = sum(range(1, 51))
print(f"The sum of numbers from 1 to 50 is: {total_sum}")
Output: The sum of numbers from 1 to 50 is: 1275

