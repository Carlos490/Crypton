Crypton is a programming language based on Python. This language can be used in various fields, including software development and object-oriented programming.

*System requirements:

Operating System: Windows

Character Set:

The following symbols are used in the Krypton programming language:

 **Letters and numbers**
 
 Capital letters: A-Z
 Lowercase letters: a-z
 Digits: 0-9

 **Special characters**

 Simple characters:`~`, `!`, `#`, `%`, `&`, `*`, `-`, `+`, `=`, `[`, `]`, `{`, `}`, `,`, `.`, `/`, `\`, `|`,`<`,`^`
 meaning:
 Operators**: `+`, `-`, `*`, `/`, `%` etc.
 Separators: `,`, `.`, `;`
 Brackets: `()`, `{}`, `[]`
 Characters for strings**: `"`

 **Characters that are not used**

 The Krypton language does not support the following characters:

- `$`, `@`,`;`, `?`,` ' `, `_`

# Syntax

This section describes the basic syntactic constructions of the Crypton language.

## Variables

To declare a variable as in Python, you do not need to specify the data type, just write the variable name, write the sign `=` and assign a value to the variable.

Example:

 x = 10

 and it turns out that this is the structure of the variable:

 [name] = [value]

 ## Types of data

 Crypton supports the following data types:

 Integers: 10, -5
 Real numbers: 3.14, -2.71
 Lines: "Hello, World!"
 Boolean values: true, false

 ## Operators

 **Arithmetic operators**
 Arithmetic operators perform mathematical operations.

 Addition (+): Adds two operands.

 a = 2 + 3 #a = 5

 Subtraction (-): Subtracts the second operand from the first.

 a = 8 - 5 #a = 3

 Multiplication (*): Multiplies two operands.

 a = 5  * 5 #a = 25

 Division (/): Divides the first operand by the second. The result is a real number.

 a = 20 / 5 #a = 4

 Exponentiation (**): Raises the first operand to the power of the second.

 a = 2 ** 3 #a = 8

 mathematical root (//)The first operand is an exponent, for example, 2 is the square root and 3 is the cubic root.and the second operand is the main operand.

 a = 2 // 64 #a = 8

Division remainder (%): Returns the remainder of the division of the first operand by the second.

a = 50 % 4 #a = 2

**Comparison operators**
Comparative operators are used to compare two values.

Equals (==): Checks whether two operands are equal.

a = (5 == 5) #a = true

Not equal to (!=): Checks if two operands are not equal.

a = (5 != 5) #a = true

Greater than (>): Checks whether the first operand is greater than the second.

a = (5 > 3) #a = true

Less than (<): Checks whether the first operand is smaller than the second.

a = (5 < 8) #a = true

Greater than or equal to (>=): Checks whether the first operand is greater than or equal to the second.

a = (5 >= 5) #a = true

Less than or equal to (<=): Checks whether the first operand is less than or equal to the second.

a = (5 <= 8) #a = true

**Logical operators**
Logical operators are used to perform logical operations.

And (&&): Returns true if both operands are true.

a = (true && false) #a = false

OR (||): Returns true if at least one of the operands is true.

a = (true || false) #a = true

NOT (!): Inverts the Boolean value.

a = !true #a = false

**Bitwise operators**
Bitwise operators perform operations on bits of numbers.

Bitwise And (&): Performs bitwise And between two operands.

a = 5 & 3 #a = 1

Bitwise OR (|): Performs bitwise OR between two operands.

a = 5 | 3 #a = 7

Bitwise exclusive OR (^): Performs a bitwise exclusive OR between two operands.

a = 5 ^ 3 #a = 6

Bitwise NOT (~): Inverts the bits of the operand.

a = ~5 #a = -6

Left shift (<<): Shifts the bits of the number to the left by the specified number of positions.

a = 5 << 1 #a = 10

Right Shift (>>): Shifts the bits of the number to the right by the specified number of positions.

a = 5 >> 1 #a = 2

**Assignment operators**
Assignment operators are used to assign values to variables.

Assignment (=): Assigns a value to a variable.

a = 10

**Operations with strings**
String operations allow you to perform various operations with strings.

String concatenation (+/): The concatenation operation combines two or more strings into one.

a = "Hello" +/ "world" #a = "Hello world"

Repeating lines (*/): The line repetition operation allows you to repeat a line several times.

a = "Hello" */ 3 #a = HelloHelloHello

**Conditional operators**
Conditional statements allow you to control the flow of program execution depending on the fulfillment of conditions.

The if statement: The if statement executes a block of code if the specified condition is true.

if (temperature > 30) {
print ("Very hot");
}

The else operator: The else statement executes a block of code when the condition in if is false.

if (temperature > 30) {
print("Very hot");
} else {
 print("Temperature within normal limits");
}

the else if: statement is activated when the condition is met and if the if is not met.

if (x > 10) {
print("x is greater than 10");
} else if (x == 10) {
print("x equals 10");
} else {
 print("x less than 10");
}

**List Operators**

The in operator: The in operator is used to check for the presence of an element in the list.

3 in [1, 2, 3, 4] #returns true

The not in operator: The not in operator is used to check for the absence of an element in the list.

3 in [1, 2, 3, 4] #returns true

## Comments

Comments in the Crypton language are used to add notes and explanations to the code. They are not executed and are intended solely to improve the readability and understanding of the code. Crypton supports single-line and multi-line comments.

**One-line comments**

Single-line comments start with a double slash `#`. The comment continues to the end of the line.

#This is a one-line comment

x = 10 #Initializing the variable x with the value 10

**Multiline comments**

Multiline comments start with ## and end with ##. They can take up several lines and are used for more detailed explanations or temporary exclusion of large blocks of code.

##c
This is a multi-line comment.
It can take up several lines.
##c

##c
A function for calculating the factorial of a number.
A recursive approach is used to solve the problem.
##c
function factorial(n) {
 if (n == 0) {
 return 1
 } else {
 return n * factorial(n - 1)
 }
}

## Lists

Lists in the Crypton language are ordered collections of items that can be modified. They allow you to store multiple values in a single variable and perform various operations on these values.

**Creating a list**

The list is created using square brackets []. The list items are separated by commas.

my_list = [1, 2, 3, 4, 5]

**Indexes**

The list items can be retrieved using an index. Indexes start from 0.

my_list = [10, 20, 30, 40, 50]
first_element = my_list[0]  #first_element will be 10
second_element = my_list[1] #second_element will be 2

**Sections**

Slices allow you to extract subsets of items from a list. It is a powerful tool for working with data collections that allows you to select items by a range of indexes.

Slices use square brackets and a colon`:` to specify a range of indexes.The syntax looks like this:

my_list = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]

#Extracting elements from index 2 to index 5 (not including 5)
sublist = my_list[2:5] #sublist will be equal to [2, 3, 4]

#Extracting the first 3 elements
first_three = my_list[:3] #first_three will be equal to [0, 1, 2]

#Extracting items from index 6 to the end of the list
from_six_to_end = my_list[6:] #from_six_to_end will be equal to [6, 7, 8, 9]

**insert function**

The insert function is used to add an item to the list at the specified position.

numbers = [1, 2, 4, 5]
numbers.insert(2, 3) #Inserts 3 at position 2
#Now the list: [1, 2, 3, 4, 5]

**remove function**

The remove function is used to remove the first occurrence of the specified value from the list.

numbers = [1, 2, 3, 4]
logical result = numbers.remove(3) #Get 3 from the message
#result: true
#Now the list is: [1, 2, 4]

**remove.all function**

The remove.all function removes all items from the list, clearing it.

numbers = [1, 2, 3, 4, 5]
numbers.remove.all() #Removes all items from the list
#Now the list is: {}

**Insert.end function**

The insert.end function adds an item to the end of the list.

numbers = [1, 2, 3]
numbers.insert.end(4) #Adds 4 to the end of the list
#Now the list: [1, 2, 3, 4]

**The len function**

The len function returns the number of items in the list.

numbers = [1, 2, 3, 4, 5]
count = numbers.len() #Returns 5
#Now count is 5

**The min function**

The min function returns the smallest value from a list or set of numbers.

numbers = [7, 1, 5, 3];
smallest = min(numbers); #Returns 1

**The max function**

The max function returns the largest value from a list or set of numbers.

numbers = [7, 1, 5, 3];
largest = max(numbers); #Is 7

**The count function**

The count function returns the number of occurrences of a given item in the list.

numbers = [1, 2, 2, 3, 4, 2];
countOfTwos = numbers.count(2); #Returns 3

**The sort.large method**

The sort.large method is used to sort lists in ascending order. This method uses efficient sorting algorithms to process large amounts of data.

large_numbers = [100, 5, 42, 89, 67, 23, 95];
large_numbers.sort.large() #Sorts the list in ascending order
print(large_numbers); #Outputs: [5, 23, 42, 67, 89, 95]

**The sort.small method**

The sort.small method is designed to sort lists in descending order. This method uses algorithms optimized for fast sorting on small amounts of data.

small_numbers = [7, 1, 5, 3];
small_numbers.sort.small(); #Writes the message in descending order
print(small_numbers); #Output: [7, 5, 3, 1]

## The print method

The print method is used to output data to the screen. It can accept various types of data and output them to the console.

print("Hello, World!") #Outputs: Hello, World!

x = 10
y = 3.14
print(x, y); #Outputs: 10 3.14

string name = "Alice"
int age = 30
type("Name:", name, "Age:", age) #Enter: Name: Alice Age: 30

## Cycles

Loops allow you to execute a block of code multiple times depending on conditions or data collections. Crypton supports two main types of loops: for and while.

**The for loop**

The for loop is used to iterate through items in collections or execute a block of code a certain number of times.

for (int i = start; I < end; I++) {
#Code block
}

**The while loop**

The while loop executes a block of code as long as the specified condition is true. The loop continues execution as long as the condition remains true.

int i = 0;
while (i < 5) {
print(i); // Outputs: 0 1 2 3 4
i++;
}

**The break operator**

The break statement is used to exit the loop immediately. This can be useful when you need to interrupt the execution of a loop before completing all iterations based on the fulfillment of a certain condition.

for i in [1, 2, 3, 4, 5] {
 if i == 3 {
 break
 }
 print(i)
}

**The continue statement**

The continue statement is used to skip the current iteration of the loop and move on to the next iteration. This is useful when you need to skip certain steps in the execution of a loop based on the fulfillment of a condition.

for i in [1, 2, 3, 4, 5] {
if i % 2 == 0 {
continue
}
output(i)
}

## Mathematical functions

The Crypton language provides a set of mathematical functions for working with numeric values. These functions include the calculation of logarithms, sines, cosines, and tangents.

**The log function**

The log function calculates the logarithm of a number based on a given basis.

log_result = log(8, 2) #log(8) with base 2
print(log_result) #Outputs: 3.0

**The sin function**

The sin function calculates the sine of the angle given in radians.

sin_result = sin(3.14 / 2) #sin(π/2)
print(sin_result) #Outputs: 1.0

**The cos function**

The cos function calculates the cosine of the angle given in radians.

cos_result = cos(3.14) #cos(π)
print(cos_result) #Outputs: -1.0

**The tan function**

The tan function calculates the tangent of the angle given in radians.

tan_result = tan(3.14 / 4) #tan(π/4)
print(tan_result) #Outputs: 1.0

**The asin function**

The asin function calculates the arcsine (or inverse sine) of a given value. Returns the angle in radians.

asin(0.5) #Returns 0.5236 (π/6 radians)

**The acos function**

The acos function calculates the arccosine (or inverse cosine) of a given value. Returns the angle in radians.

acos(0.5) #Returns 1.0472 (π/3 radians)

**The atan function**

The atan function calculates the arctangent (or inverse tangent) of a given value. Returns the angle in radians.

atan(1) #Returns 0.7854 (π/4 radians)

**the Atan function of two variables**

The atan function of two variables calculates the arctangent of the ratio of two numbers, y and x. Returns the angle in radians.

atan2(1, 1) #Returns 0.7854 (π/4 radians)

**The sinh function**

The sinh function calculates the hyperbolic sine of a given value.

sinh(1) #Returns 1.1752

**The cosh function**

The cosh function calculates the hyperbolic cosine of a given value.

cosh(1) #Returns 1.5431

**The tanh function**

The tanh function calculates the hyperbolic tangent of a given value.

tanh(1) #Returns 0.7616

**The asinh function**

The asinh function calculates the hyperbolic arcsine of a given value.

asinh(1) #Returns 0.8814

**The acosh function**

The acosh function calculates the hyperbolic arccosine of a given value.

acosh(1) #Returns 0

**The atanh function**

The atanh function calculates the hyperbolic arctangent of a given value.

atanh(0.5) #Returns 0.5493










 






 
