# Crypton
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
sublist = my_list[2:5] # sublist will be equal to [2, 3, 4]

#Extracting the first 3 elements
first_three = my_list[:3] # first_three will be equal to [0, 1, 2]

#Extracting items from index 6 to the end of the list
from_six_to_end = my_list[6:] # from_six_to_end will be equal to [6, 7, 8, 9]

**insert function**

The insert function is used to add an item to the list at the specified position.

numbers = {1, 2, 4, 5};
numbers.insert(2, 3); // Inserts 3 at position 2
#Now the list: {1, 2, 3, 4, 5}

**remove function**

The remove function is used to remove the first occurrence of the specified value from the list.

int[] numbers = {1, 2, 3, 4};
logical result = numbers.remove(3); #Get 3 from the message
#result: true
#Now the list is: {1, 2, 4}

**remove.all function**

The remove.all function removes all items from the list, clearing it.

int[] numbers = {1, 2, 3, 4, 5};
numbers.remove.all(); #Removes all items from the list
#Now the list is: {}

**Insert.end function**

The insert.end function adds an item to the end of the list.

int[] numbers = {1, 2, 3};
numbers.insert.end(4); #Adds 4 to the end of the list
#Now the list: {1, 2, 3, 4}

**The len function**

The len function returns the number of items in the list.

int[] numbers = {1, 2, 3, 4, 5};
int count = numbers.len(); #Returns 5
#Now count is 5

**The min function**

The min function returns the smallest value from a list or set of numbers.

int[] numbers = [7, 1, 5, 3];
int smallest = min(numbers); #Returns 1

**The max function**

The max function returns the largest value from a list or set of numbers.

int[] numbers = [7, 1, 5, 3];
int largest = max(numbers); #Is 7



 






 
