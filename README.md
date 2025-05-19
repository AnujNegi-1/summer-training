# summer-training

  mkdir => use to make directory
  ls => use to check list
  touch => use to create a file
  rmdir => use to remove directory
  pwd => it shows the working directory
  sudo => it is use to five the permission of root or any  comand
  cmd => it use for common directory
  rm -r * => it is use to remove directory 
  
# This program prints Hello, world!
print('Hello, world!')

# This program adds two numbers
num1 = 1.5
num2 = 6.3

# Add two numbers
sum = num1 + num2

# Display the sum
print('The sum of {0} and {1} is {2}'.format(num1, num2, sum))

# Store input numbers
num1 = input('Enter first number: ')
num2 = input('Enter second number: ')

# Add two numbers
sum = float(num1) + float(num2)

# Display the sum
print('The sum of {0} and {1} is {2}'.format(num1, num2, sum))

# Python program to swap two variables

x = 5
y = 10

# To take inputs from the user
#x = input('Enter value of x: ')
#y = input('Enter value of y: ')

# create a temporary variable and swap the values
temp = x
x = y
y = temp

print('The value of x after swapping: {}'.format(x))
print('The value of y after swapping: {}'.format(y))

x = 5
y = 10

x, y = y, x
print("x =", x)
print("y =", y)
