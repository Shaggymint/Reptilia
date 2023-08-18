# Reptilia
#prompt the user to input two numbers. 
#Convert the input strings to integers using the`int()` function
#Compare the two numbers using the 'if' statements:
'''If the first number is greater than the second number, print a message indicating that the first number is larger.
If the second number is greater than the first number, print a message indicating that the second number is larger.
If the two numbers are equal, print a message indicating that the numbers are equal.'''
user_input1 = str(input('Enter a random number'))
ans1 = int(user_input1)
user_input2 = str(input('Enter another random number'))
ans2 = int(user_input2)
if ans1 > ans2:
    print('The first number is greater')
elif ans2 > ans1:
    print('The second number is greater')
else:
    print('They are equal')
