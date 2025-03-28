
Programming is process of converting ideas into instruction that computer can understand and execute
These instructions are specific and sequential
Something like a recipe.. first you need ingredients and set of instructions
Instruction need to be specific so that we can get our desired result

Bug is when something unexpected happens
Crash is when program stops early or freezes 

The order of the steps will  result in your final product
It is all about giving computers the right instructions and the correct sequence of steps to produce the desired result

Programming language is made of syntax (rules) and semantics (meaning)

The main reason why we have so many languages, it is because that each comes with its own set of strengths and weaknesses

Some are ideal for programming small devices with limited memory, where others are made to handle complex mathematical computations
That language has to be broken down to one that computer understands, it is a machine language.
Machine language is extremely complex for us to write directly because it is mostly just a series 0 and 1

Writing source code is what programmers do all day , it is the instructions we have for the computer and it is written in plain text 

We can use text editor, for programming for source code

file extensions 
Javascript - .js
Perl  .pl
kotlin  .kt

3 ways to convert programming code to machine language

-compile it 
-interpret it 
-combination of both 

Compilers take your high level language and turn it into an executable that contains low level machine code 

Iterpreters process your source code each time its run, line by line, and it up the the other user to have the needed interpreter available on their machine 

Compiled laguages C, C++, objective C are compiled languages
Interpreted languages are php, javascript,

Combination java, C# and python

IDE - integrated development environments 
provide features that speed up code development, to write, debug and compile code 


Five top languages 
Java
Python
Javascript
C++
C#


JavaScript is for web pages  and for some non web applications 

Python is designed to be a general purpose language
web apps, internal company tools , scientific analysis, games


Terminal is an application that lets you run commands to explore directories, execute scripts

Statements are the building blocks of any program and are the individual actions that you want your program to take
Each statement can be made up of keywords, expressions, operators 

Operators are symbols that tell the computer to perform an action with some input 
Like + / * - and rest of them 
3 +2 
3 and 2 are input - operands 
plus sign is an operator 
3 + 2  complete is an expression  
a result of completiton is value 
Computer programs are made of statements ,statements that can perform a mathmematical calculation,display something in the screen or even make a choose between more values
There are two ways to write error-free programs; only the third one works -Alan Perlis 
Programs tends to have bugs 
First you need to understand what type of bug or error you are dealing with
Errors tend to fall into three categories 

Syntax - language rules broken 
Runtime - unable to execute 
Semantic - unexpected output 


Writing code typically involves handling of information
If we are making a game, we need to save the user score
if we are creating a banking application we need to have their current balance

A variable is simply a container for a value 
When we use part in computers memory to store a data, this data is called a variable 
We declare variables in python by giving them a name and then  setting their value 
in C# we give them name and a type after that we set their value 

This is called assigning the value and this is done with the assignment operator which is an equal sign

In programming the equal sign means i wanna take the value on the right and store it in the variable on the left 
It doesn't meant the two sides are equal 

Datatype allows us to put our variable in a particular category so that computer knows how much memory space he will need to give us in its memory , and generally knows how we will use our variable later in our program.

Integer is whole number no decimal places 
Letters and symbols inside the double quotes are called a string -because it is made of string of characters

Depending on the programming language that you work with, variables can behave in different ways 
Some languages require that you define your types and variables before you use them like java, C#, and C++ 

We can not later change type of that value, if we try to change it, we will receive an error of type mismatch 
In python like in javascript we do not need to declare variable types before using it

Names contain letters, numbers, and underscores , 
1.name should not start with the number 
2.spaces are not allowed in a name
3.names are case sensitive 
4.variables cannot be keywords 

in general you want to use short descriptive names that make your code easy to understand
Naming this takes practice, it is often considered hardest part in programming 

Numbers 
2 +3  > 5
2*3 > 6
2**3 > 8 - 2 *2 *2  mnozenje tj eksponent 
3/2 > 1.5 
3//2 > 1   this is result of division but to see without remainder 
5 % 3 > 2   this is a remainder of 5 / 3 

In JavaScript a number is everything, the whole number and also a number with decimal places 
it is all considered a number , but in the most programming languages, there are more types
Float is any number with a decimal point, short for floating-point number it is used when more precision is required

Strings - the name is it is a string characters one after the other
The characters can be letters , numbers, symbols, spaces, they are typically represented by quotes in the beginning and in the end
String can be passed directly in functions or it can be stored in variables 

Whitespace to add extra space for code to be more readable 

Comments are notes to your future self and others to describe what your code does 

Comments can also be used to comment out code
Comments are a powerful tool for programmers, we can use them to serve as reminders, provide explanations for other developers and even help us with debugging code 

Conditional or boolean expression - any expression that breaks down to either true or false 

Relational operators work with two operands and they return a value, true or false 

Equality operator it is represented by a double equal sign and it is used to evaluate the equality of the operands 
4==5

Not equal sign if we want to check that they are not the same 
5!=4

5 > 4 True

if statement has this general structure 
if condition  is true then do the work inside, but if condition is not meet then we are doing next statement


if-else statement
if condition is true we are doing the work,
but if condition is something else then we do something else 


Function is a block of code package together with a name 
They are core features of all programming languages 
Can be called functions, methods, subroutines or other names 
It is a way to break up your code 

One key help to a functions is they help us to avoid writing the same lines of code again and again

We teach computer how to do it one time, and then on out we just call the function by its name and the work gets done
No need to repeat ourselves

Create a function in python : starting with 
def name_of_the_Function(): 
    print("Hello friends")


this is creating function

but to activate function we need to call it by its name follow by parentheses

name_of_Function()   - this is calling a function 

In programming we often want to provide different outputs to our users based on some input
Functions allow us to do this 

In programming this variable has a special name, a parameter 
Parameter allow functions to change their behavior based on some input

We have an arguments for the  values that we give to our functions

We give our functions arguments by placing a value between the open and close parentheses

function_definition(parameters)

function_call(arguments)

One thing to note is that sometimes parameters and arguments are used interchangeably , you have to rely on the context to figure out the meaning

The key thing to know is that functions have the ability to change their behavior based on their parameters and arguments

Functions can return value but it depends on their  signature 

Return statement consists of the return keyword and the value that the function should return
Since we want to user this value for later, we need to store it for later

then we are creating a variable that will store value of called function 
balance = called_function(100)

Function fall into four main categories 
- those that have no parameters and no return value 
- no parameters but do return a value 
- those that have parameters and don't return a value
- those that have parameters and returns a value

Breaking up our code int reusable chunks helps us to develop programs that are easier to read, write, and debug


Glossary for This Course
A
argument [Setting parameters and arguments]
The actual value given in a function call that “fills in” the parameter variable
assignment operator [Introduction to variables and data types]
The equals sign; the value on the right is assigned to (stored in) the variable named on the left-hand side.
B
block [Exploring conditional code]
A group of statements that belong together
bug [What is programming?]
Something that happens unexpectedly in a program
C
comment [Working with comments]
A note to describe what a program does
comment out [Working with comments]
Using comments to temporarily ignore a section of code
compile [Running your code]
Translate a program from high-level code to machine code
concise [Why Python?]
A concise programming language takes fewer lines of code to accomplish a goal.
conditional expression [Making decisions in code]
Any expression that evaluates to True or False; also called a Boolean expression, named after British mathematician George Boole
crash [What is programming?]
When a program stops early or freezes
D
data type [Introduction to variables and data types]
A category for values; for example, a value can be a number, or it can be a string of text characters. A data type also defines how we can operate on those values.
E
expression [Basic statements and expressions]
A combination of operands and operators that break down into a single value
F
file extension [Writing source code]
The characters after the last “.” in a file name; we usually use “.py” for Python, “.js” for JavaScript, etc.
float [Working with numbers]
Any number with a decimal point (short for “floating point” number)
function [Introduction to functions]
A block of code packaged together with a name, also called subroutine, procedure, or method
function body [Creating and calling functions]
The code block that belongs to a function; the code that the function will execute
function call [Creating and calling functions]
Making a function do its action by giving its name and possibly giving it argument values for parameters, also called invoking a function
G
gutter [Running Python in an IDE]
The left side of an IDE window, where line numbers appear
H
high-level language [What is a programming language?]
A programming language with structure, keywords, and syntax that are easier for humans to understand
I
IDE [Using an IDE]
Integrated development environment—an application that provides the tools needed to write, compile, run, and debug programs
if-else statement [Working with simple conditions]
A statement that tests a condition; when the condition is True, the program will perform a specified action. When the condition is False, the program does the action following the “else.”
if statement [Exploring conditional code]
A statement that tests a condition; when the condition is True, the program will do the action(s) following the “if.” When the condition is False, the program does not do the action(s).
integer [Working with numbers]
A whole number without any decimal places
IntelliSense [Using an IDE]
A feature of the Visual Studio Code IDE that makes code suggestions as you type
interpret [Running your code]
Translate a program from high-level code tomachine code one source code line at a time
K
keyword [Variables across languages]
Reserved words that mean something special in a programming language; for example, the word “for” is a keyword in many languages, including Python, Java, C, and C++.
M
machine language [What is a programming language?]
The language that a computer “understands”—directly using the instructions wired into the CPU
O
operand [Basic statements and expressions]
The value or values that an operator works on; for example, in 4 + 3, the operator is + and the operands are 4 and 3.
operator [Basic statements and expressions]
A symbol for an arithmetic operation, such as +, -, *, and /
order of operations [Basic statements and expressions]
The order in which operations are performed, also called priority of operations; for example, multiplication in an expression is done before addition, just as in mathematics—4 + 3 * 5 is 19, not 35.
P
parameter [Setting parameters and arguments]
Variable name in a function definition, used to modify the behavior of the function code; you can think of it as a “placeholder” that will be filled in when the function is called.
programming [What is programming?]
The process of converting ideas into instructions
R
relational operator [Making decisions in code]
An operator that yields a True or False value depending on the relation between its operands; for example, > is a relational operator; 4 > 2 evaluates to True.
return value [Returning values from functions]
The value that a function gives back to the code that called it
runtime error [Troubleshooting issues]
When the computer is unable to execute part of your code; for example, when 12 / 0 can't be calculated
S
semantic error [Troubleshooting issues]
When the output of the program is not what you expected, also called a logic error; for example, calculating area of a rectangle as length plus width instead of length times width
source code [Writing source code]
Instructions for the computer written in plain text
statement [Basic statements and expressions]
The individual actions you want a program to take; statements can combine keywords, operations, and expressions.
syntax [What is a programming language?]
The rules for how a programming language expects its code to be written
syntax error [Troubleshooting issues]
When a program does not follow the rules of the language; for example, 3 + * 5
syntax highlighting [Using an IDE]
Use of color in an IDE to point out keywords and improve readability of code
V
variable [Introduction to variables and data types]
A container for a value
W
white space [Properly using whitespace]
Blanks and/or blank lines; you add these to programs to make them more readable to humans.



Glossary for Programming Basics
A
algorithm [Introduction to algorithms]
A set of instructions that describes how to get the exact result you want
argument [Setting parameters and arguments]
The actual value given in a function call that “fills in” the parameter variable
array [Understanding collections]
A collection that groups pieces of data in a certain order and assigns the collection a name, also called an array or list in some programming languages; the position of each element is defined by an index.
assignment operator [Introduction to variables and data types]
The equals sign; the value on the right is assigned to (stored in) the variable named on the left-hand side.
attribute [Introduction to object-oriented programming]
Data that an object has, also called a field or property
autocompletion [Debugging code in an IDE]
Also known as code completion, this is a feature of IDEs that offer to finish code for you while you’re typing.
B
block [Exploring conditional code]
A group of statements that belong together
bug [What is programming?]
Something that happens unexpectedly in a program
C
class [Introduction to object-oriented programming]
A detailed description; the definition or template of what an object will be
collection [Understanding collections]
A programming construct that lets you group similar items together
comment [Working with comments]
A note to describe what a program does
comment out [Working with comments]
Using comments to temporarily ignore a section of code
compile [Running your code]
Translate a program from high-level code to machine code
concatenation [Combining and manipulating strings]
Combining multiple strings into a single string; in many languages, the + operator is used to concatenate strings.
concise [Why Python?]
A concise programming language takes fewer lines of code to accomplish a goal.
conditional expression [Making decisions in code]
Any expression that evaluates to True or False; also called a Boolean expression, named after British mathematician George Boole
constructor function [Creating custom classes and objects]
A function whose purpose is to specify the properties to use when you create an object; in many program languages, you invoke the constructor by giving the name of the class it belongs to.
crash [What is programming?]
When a program stops early or freezes
D
data type [Introduction to variables and data types]
A category for values; for example, a value can be a number, or it can be a string of text characters. A data type also defines how we can operate on those values.
debug [Introduction to debugging]
The process of identifying and fixing bugs in a program
dictionary (collection) [Understanding collections, Creating more complex collections]
A collection that lets you store related information with a label for each item, also called a map, hash map, table, or associative array in some programming languages
E
expression [Basic statements and expressions]
A combination of operands and operators that break down into a single value
F
field [Introduction to object-oriented programming]
Data that an object has, also called an attribute or property
file extension [Writing source code]
The characters after the last “.” in a file name; we usually use “.py” for Python, “.js” for JavaScript, etc.
float [Working with numbers]
Any number with a decimal point (short for “floating point” number)
for loop [Iterating through collections]
A programming construct in many languages that lets you specify iteration to a specified endpoint; usually used when you know exactly how many times the loop must iterate
framework [Understanding libraries and frameworks]
Code that is used together in a specific way; frameworks define how you should accomplish a task, with some decisions already made for you.
function [Introduction to functions]
A block of code packaged together with a name, also called subroutine, procedure, or method
function body [Creating and calling functions]
The code block that belongs to a function; the code that the function will execute
function call [Creating and calling functions]
Making a function do its action by giving its name and possibly giving it argument values for parameters, also called invoking a function
G
garbage collection [Memory management across languages]
A process by which the runtime system keeps track of which items in memory are no longer needed and deletes them
gutter [Running Python in an IDE]
The left side of an IDE window, where line numbers appear
H
high-level language [What is a programming language?]
A programming language with structure, keywords, and syntax that are easier for humans to understand
I
IDE [Using an IDE]
Integrated development environment—an application that provides the tools needed to write, compile, run, and debug programs
if-else statement [Working with simple conditions]
A statement that tests a condition; when the condition is True, the program will perform a specified action. When the condition is False, the program does the action following the “else.”
if statement [Exploring conditional code]
A statement that tests a condition; when the condition is True, the program will do the action(s) following the “if.” When the condition is False, the program does not do the action(s).
immutable [Collections in other languages]
Refers to variables or collections whose existing values cannot change after they are created
importing [Comparing types of external code]
Referencing a module by its name so your program can use its code
index [Understanding collections; Working with collections]
A number that gives an item’s position in a list; in most programming languages, the first item in a list has an index of zero.
index number [Understanding collections; Working with collections]
A number that gives an item’s position in a list; in most programming languages, the first item in a list has an index of zero.
infinite loop [Introduction to iteration]
A bug that occurs when a loop never stops
integer [Working with numbers]
A whole number without any decimal places
IntelliSense [Using an IDE]
A feature of the Visual Studio Code IDE that makes code suggestions as you type
interpret [Running your code]
Translate a program from high-level code to machine code one source code line at a time
int method [Combining and manipulating strings]
A method to convert a string to an integer in Python; many other languages have similar methods for type conversion.
IO [Introduction to input and output]
Input/output
iterate [Introduction to iteration]
Repeat a procedure multiple times until it reaches a specified endpoint
K
keyword [Variables across languages]
Reserved words that mean something special in a programming language; for example, the word “for” is a keyword in many languages, including Python, Java, C, and C++.
L
linting [Debugging code in an IDE]
An IDE feature that checks code for bugs before you execute it; the name comes from the process of removing lint from clothing.
list (collection) [Understanding collections]
A collection that groups pieces of data in a certain order and assigns the collection a name, also called an array or list in some programming languages; the position of each element is defined by an index.
loop [Introduction to iteration]
Code that iterates (repeats until reaching a specified endpoint)
loop, infinite [Introduction to iteration]
A bug that occurs when a loop never stops
M
machine language [What is a programming language?]
The language that a computer “understands”—directly using the instructions wired into the CPU
method [Introduction to object-oriented programming]
Also called a behavior, a function that specifies what actions an object can perform; it is a block of code that can be called to perform some action, and it may return a value.
module [Comparing types of external code]
In Python, a file that contains code, such as variables and functions that are related; for example, Python’s random module, which has several functions for generating random numbers
multi-threading [Introduction to multithreading]
An approach to writing code that executes multiple threads (tasks) concurrently
mutable [Collections in other languages]
Refers to variables or collections whose existing values can be changed
O
object-oriented programming [Introduction to object-oriented programming]
OOP—an approach to programming that breaks programs up into smaller parts known as objects, each of which has its own distinct focus
operand [Basic statements and expressions]
The value or values that an operator works on; for example, in 4 + 3, the operator is + and the operands are 4 and 3.
operator [Basic statements and expressions]
A symbol for an arithmetic operation, such as +, -, *, and /
order of operations [Basic statements and expressions]
The order in which operations are performed, also called priority of operations; for example, multiplication in an expression is done before addition, just as in mathematics—4 + 3 * 5 is 19, not 35.
P
package [Understanding libraries and frameworks]
Also called a library, this is a group of related modules in Python to help you accomplish a task. It is like a set of tools.
parameter [Setting parameters and arguments]
Variable name in a function definition, used to modify the behavior of the function code; you can think of it as a “placeholder” that will be filled in when the function is called.
PEP 8 [Choosing a code style]
Python Enhancement Proposal 8—the most commonly used style guide for Python
programming [What is programming?]
The process of converting ideas into instructions
property [Introduction to object-oriented programming]
Data that an object has, also called a field or attribute
pseudocode [Writing pseudocode]
A description of the logic you're trying to create using plain language
R
regular expression [Creating regular expressions]
An encoded description of a pattern that you want to match within a string
relational operator [Making decisions in code]
An operator that yields a True or False value depending on the relation between its operands; for example, > is a relational operator; 4 > 2 evaluates to True.
return value [Returning values from functions]
The value that a function gives back to the code that called it
runtime error [Troubleshooting issues]
When the computer is unable to execute part of your code; for example, when 12 / 0 can't be calculated
S
semantic error [Troubleshooting issues]
When the output of the program is not what you expected, also called a logic error; for example, calculating area of a rectangle as length plus width instead of length times width
slice [Finding patterns in strings]
In Python, a part of a string or a list; for strings, this operation is called substring in many other programming languages.
source code [Writing source code]
Instructions for the computer written in plain text
statement [Basic statements and expressions]
The individual actions you want a program to take; statements can combine keywords, operations, and expressions.
style guide [Choosing a code style]
A document describing a programmer’s (or company’s) approach to code
syntax [What is a programming language?]
The rules for how a programming language expects its code to be written
syntax error [Troubleshooting issues]
When a program does not follow the rules of the language; for example, 3 + * 5
syntax highlighting [Using an IDE]
Use of color in an IDE to point out keywords and improve readability of code
T
test case [Creating a test case]
Commands or scripts that use a program in a way designed to test a specific scenario or feature of the program
tuple [Collections in other languages]
In Python, an immutable list
V
variable [Introduction to variables and data types]
A container for a value
W
while loop [Iterating to a custom endpoint]
A programming construct in many languages that iterates until the program arrives at a certain state
white space [Properly using whitespace]
Blanks and/or blank lines; you add these to programs to make them more readable to humans.


Glossary for Core Structures
A
abstract class [Abstract and concrete classes]
A class that exists purely for the sake of being inherited by other classes to provide some shared behavior
abstraction [Abstraction]
Focusing on the essential qualities of something rather than one specific example
access control [Access control, compliance, and injection]
Rules specifying who can access which parts of a database
accessor [Creating class diagrams: Behaviors]
See getter method.
ACID [ACID and transactions]
An acronym that refers to the requirement that database transactions be atomic, consistent, isolated, and durable
actor (use case) [Identifying the actors]
Anything that lives outside the application but interacts with it to accomplish some goal
aggregate functions [Aggregate functions]
SQL functions that use more than one piece of data to generate a value
aggregation [Aggregation]
An object relationship in which one object is built of other objects, often referred to as a has-a relationship; the subsidiary objects have an existence independent of the containing object.
analysis (object-oriented) [Analysis, design, and programming]
Figuring out what a program should do; what problem you are trying to solve
ANSI [Basic SQL]
American National Standards Institute. Their web site says ANSI is “a private, non-profit organization that administers and coordinates the U.S. voluntary standards and conformity assessment system.”
approximate algorithm [What are algorithms?]
An algorithm that tries to find an answer that might or might not be exact (such as a facial recognition algorithm, which might not give the same answer every single time)
array [Arrays; What are arrays?]
A collection that groups pieces of data in a certain order and assigns the collection a name, also called an array or list in some programming languages; the position of each element is defined by an index.
array index out of bounds error [What are arrays?]
An error that happens when a program tries to access an item at an index position outside an array’s limit
array indexing [Arrays]
A constant-time operation to access an element of an array
array insertion/deletion [Arrays]
A linear time operation to insert or delete an element at an arbitrary location in an array; at the end of an array, this is usually a constant time operation.
array, jagged [Jagged arrays]
A multidimensional array where each row can have a different length
array, ragged [Jagged arrays]
A multidimensional array where each row can have a different length
array, resizable [Resizable arrays and language support]
An array whose length can be modified; programs can add additional elements to such an array.
ASCII [Understanding hash functions]
American Standard Code for Information Interchange—a format for text where each character has a single numerical representation; this encoding has only 256 possible entries.
associative table (database) [Relationships]
A table that contains columns for foreign keys from the tables being associated
atomic transaction [ACID and transactions]
A transaction must be indivisible; pieces of it can’t be separated out.
attribute [Objects]
Data that an object has, also called a field or property
auto-increment [Primary and foreign keys]
A database field whose value increases by one every time a row is added; usually used for a primary key
B
behavior [Objects]
An action that an object can do, also called a method
behavioral patterns [Design patterns]
Design patterns concerned with communication between objects as a program is running
big O notation [Measuring algorithm performance; Big O notation]
A notation used to describe how a particular algorithm performs as the size of the set of inputs grows over time; the O stands for orderof operation.
binary search [Ordered list search; Search arrays]
An algorithm that determines whether an item is in a sorted list; it works by starting in the middle of the list and, depending on whether the value sought is less or greater than the item, discards the “wrong half” of the list. It repeats this process until the item is found or there are no elements left to search. Its time complexity is logarithmic, O(log n).
binary search tree [Understand binary search trees]
A binary tree in which the left child must be less than its parent and the right child must be greater than its parent
bit [Numerical data types]
A single zero or one
black boxing [Encapsulation]
The principle that an object should not make anything about itself available except what is absolutely necessary for other parts of an application to work
Boolean data type [Booleans and characters]
A data type with two possible values: True or False; usually used to perform logical operations, most commonly to determine whether some condition is true
BST [Understand binary search trees]
A binary tree in which the left child must be less than its parent and the right child must be greater than its parent
bubble sort [The bubble sort]
A sorting algorithm that works by repeatedly comparing each item to its neighbor and swapping them if needed; its time performance is quadratic, O(n2).
bucket [Understanding hash tables]
A place for a key-value pair to go in a hash table
C
camel case format [Creating class diagrams: Attributes]
Naming convention that starts with a lowercase letter and uses uppercase for additional words, such as priceAfterDiscount; Java tends to use this convention.
cascading delete [Relationship rules and referential integrity]
A process in which associated records are removed in order to maintain consistency; for example, deleting a restaurant customer would also remove all their orders.
chaining [Pros and cons of hash-based structures]
Creating a linked list with additional values to handle collisions in a hash table
CHAR [Columns and data types]
A database data type that contains a string with a fixed length of characters
character data type [Booleans and characters]
A data type that can store a single symbol or letter
child class [Inheritance; Identifying inheritance situations]
See subclass.
child node [Introduction to tree data structures]
A node in a tree that is referred to by another node
class [Classes]
A detailed description; the definition or template of what an object will be
class, child [Inheritance; Identifying inheritance situations]
See subclass.
class, parent [Inheritance; Identifying inheritance situations]
See superclass.
class relationships [Identifying class relationships]
A diagram showing how objects in an application are related to one another
class responsibilities [Identifying class responsibilities]
Determination of the actions that a class must perform and which classes are responsible for which actions
clause, SQL [Basic SQL]
A part of an SQL statement that has a keyword specifying some action to take and something to act on or use
code smell [General development principles]
Valid code that somehow doesn’t seem right; it doesn’t pass the “smell test”
collaborator [CRC cards]
A class that will interact with a class being described in a CRC card
collection algorithms [Common algorithms in programming]
Algorithms that involve manipulating or navigating among sets of data that are stored within a particular structure
collision [Hash Tables; Understanding hash functions]
An event that occurs when two separate keys in a hash table map to the same slot in the table
column (database) [Relational databases; Understanding databases: Benefits of spreadsheets]
Columns represent attributes of each row. For example, each customer’s row might contain information about their name, email address, and phone number.
compile-time polymorphism [Polymorphism]
Choosing which of several overloaded methods to call by looking at the method signature, also called static polymorphism
composite key [Keys and unique values]
A key that is made up of two or more fields in the data
composition [Composition]
An object relationship in which one object is built of other objects; the subsidiary objects are owned by the containing object.
computational algorithms [Common algorithms in programming]
Algorithms that take one set of data and derive another set of data from it
conceptual model [Identifying the objects]
Model that identifies the most important objects in an application and the relationship between them
concrete class [Abstract and concrete classes]
A class that implements any missing functionality from an abstract class
consistent transaction [ACID and transactions]
Whatever a transaction does, it must leave the database in a valid or consistent state.
constant time [Measuring algorithm performance; Big O notation]
A big O of one; an operation that doesn’t depend on the number of elements in a dataset
CRC cards [CRC cards]
Class, responsibility, collaboration—index cards containing the same information as a conceptual object diagram
creational patterns [Design patterns]
Design patterns focused on the instantiation of objects
CRUD [Basic SQL]
An acronym for common database operations: Create, Read, Update, and Delete
D
data structure [Introduction to data structures]
A container that allows programmers to combine several pieces of data into a single structure; this helps connect and group data.
data type [Introduction to data and data types]
A category for values; for example, a value can be a number, or it can be a string of text characters. A data type also defines how we can operate on those values.
data type (database) [Columns and data types]
The kind of information stored in each column
database [Why use a database?]
A structure that stores information in an organized, consistent, reliable, and searchable way
database column [Relational databases; Understanding databases: Benefits of spreadsheets]
Columns represent attributes of each row. For example, each customer’s row might contain information about their name, email address, and phone number.
database field [Understanding databases: Benefits of spreadsheets]
See database column.
database index [Indexes, transactions, and stored procedures]
A reference to each value in a field and where it’s located for quick access; this makes retrieval faster but can increase time for some operations like inserting a record.
database key [Keys and unique values]
A unique value used to refer to only one specific row or record
database, relational [Relational databases]
A database in which data are organized into relations—tables of related data
database row [Relational databases; Understanding databases: Benefits of spreadsheets]
An instance of a given entity; for example, each customer in a database has their information in a table row.
database table [Relational databases]
A collection of rows (representing individual entities) and columns (the attributes of those entities)
database transaction [Indexes, transactions, and stored procedures]
A group of queries or statements treated as a block of activities; if one of the components fails for any reason, the whole group of statements is not executed, and anything that is partially completed is rolled back.
DATETIME [Columns and data types]
A database type that stores a time along with a date
DBMS [What you should know]
Database management system—this is the software we use to interact with a database.
DCL [Basic SQL]
Data control language—commands for controlling access to database tables
DDL [Basic SQL]
Data definition language—commands for defining a database
delete, cascading [Relationship rules and referential integrity]
A process in which associated records are removed in order to maintain consistency; for example, deleting a restaurant customer would also remove all their orders.
DELETE statement [Modifying data]
An SQL statement that lets you remove specific rows in a database table
denormalization [Denormalization]
The process of intentionally duplicating information in database tables in violation of normalization rules
deque [Stacks and queues; Specialized queues]
Double-ended queue—a data structure that is optimized for adding and removing elements from both ends of the collection
dequeue [Stacks and queues; Implement queues in Swift]
Remove an element from a queue; Note: this is not the same as a deque, although the spellings are similar.
design (object-oriented) [Analysis, design, and programming]
Figuring out how a program should accomplish its task
design pattern [Design patterns]
A common, repeatable solution for creating software programs; these patterns define code architectures and best practices for common problems that occur across all kinds of applications.
desktop databases [Software options]
Database tools intended for small solutions with just a few users, usually hosted on a workstation rather than a dedicated server
destructor [Classes with multiple constructors]
A method that is called when an object is no longer needed and is being disposed of, also called a finalizer
deterministic algorithm [What are algorithms?]
An algorithm where each step has an exact decision
dictionary (collection) [Hash Tables; What are associative arrays?; Using dictionaries in Python]
A collection that lets you store related information with a label for each item, also called a map, hash map, table, or associative array in some programming languages
difference (set) [Sets in Python 3]
Given two sets, the difference is a new set that contains all the items in the first set that are not in the second set; for example, the difference of A, B, C and B, D, E is A, C.
divide-and-conquer algorithm [The merge sort]
An algorithm that works by dividing a problem into smaller parts and solving those
DML [Basic SQL]
Data manipulation language—commands for interacting with database data
doubly linked list [Singly vs. doubly linked lists]
A linked list in which each node has both a pointer to the next node and a pointer to the previous node in the list
DRY [General development principles]
“Don’t repeat yourself”—a principle that says you should avoid copying and pasting large sections of code without any changes
durable transaction [ACID and transactions]
The information changed in a transaction must actually get written to the database.
dynamically typed language [OOP support in different languages]
A language where a variable’s type does not need to be specified; Python and Ruby are dynamically typed.
E
encapsulation [Encapsulation]
Bundling an object’s attributes and methods within the same class; this is often done to restrict access to some of an object’s components.
enqueue [Stacks and queues; Implement queues in Swift]
Add an element to a queue
enterprise database management systems [Software options]
Database systems intended to be used by huge numbers of people and run on infrastructure that can serve millions of interactions simultaneously
ER diagram [Modeling and planning a database]
Entity-relationship diagram—shows a table’s fields and its relationships to other tables
exact algorithm [What are algorithms?]
An algorithm that produces a known predictable value
execution flow [Use cases]
In a use case, the steps needed to accomplish a goal
expression, SQL [Basic SQL]
Part of an SQL statement that sets parameters within which to operate
F
factorial [Power and factorial]
A mathematical operator that is the product of a number and all the numbers before it; thus, 5 factorial (written as 5!) is 5 × 4 × 3 × 2 × 1, or 120.
factory method [Design patterns]
A design pattern providing a structured way to instantiate different types of objects
field [Objects]
Data that an object has, also called an attribute or property
field (database) [Understanding databases: Benefits of spreadsheets]
See database column.
FIFO [What are queues?]
First in, first out—the policy that a queue follows
filter [Unique filtering with hash table]
A filtering algorithm goes through a data structure, retaining only those elements that satisfy some condition and discarding the others; for example, you might want to go through a list of items and keep only the unique items, discarding all the duplicates.
final class [Abstract and concrete classes]
In Java, a class that cannot be extended or inherited from
finalizer [Classes with multiple constructors]
See destructor.
finite set [Sets in Python 3]
A set with a specific set of elements that cannot be added to
first normal form [First normal form]
A database requirement that values in each field in each table have only one value in them and there are no columns representing repeated kinds of data for each row
foreign key [Relationships]
A key that is a primary key in one table but not in another
frozen set [Sets in Python 3]
A set with a specific set of elements that cannot be added to
function, hash [Hash Tables; Understanding hash functions]
A function that uses a key to compute an index to the slots in the hash table and map the key to the value
functionality [FURPS+ requirements]
The capabilities and features of an app
functions, aggregate [Sorting results]
SQL functions that use more than one piece of data to generate a value
FURPS [FURPS+ requirements]
Functionality, usability, reliability, performance, and supportability—a checklist of key qualities to consider when determining requirements
FURPS Plus [FURPS+ requirements]
FURPS with four more categories: design constraints, implementation, standards, and physical requirements
G
garbage collection [Classes with multiple constructors]
A process by which the runtime system keeps track of which items in memory are no longer needed and deletes them
getter method [Creating class diagrams: Behaviors]
A method that retrieves the value of an object’s attribute, also called an accessor
“god object” [Identifying class responsibilities]
In object-oriented design, an object that knows too much or does too much
H
hash function [Hash Tables; Understanding hash functions]
A function that uses a key to compute an index to the slots in the hash table and map the key to the value
head (linked list) [What are linked lists?]
The first node in a linked list
heap (using trees) [Understand heaps]
A data structure implemented as a binary tree to hold a collection of objects; these can be used for a priority queue.
I
identity [Objects]
An object’s existence; an object’s identity is different from every other object’s identity.
index [What are arrays?]
A number that gives an item’s position in a list; in most programming languages, the first item in a list has an index of zero.
index, database [Indexes, transactions, and stored procedures]
A reference to each value in a field and where it’s located for quick access; this makes retrieval faster but can increase time for some operations like inserting a record.
index number [What are arrays?]
A number that gives an item’s position in a list; in most programming languages, the first item in a list has an index of zero.
infinite set [Sets in Python 3]
A set with an infinite number of elements, such as a set containing all negative numbers
inheritance [Inheritance; Identifying inheritance situations]
A process for passing on attributes and methods from other existing classes to a new class
initialize [Use arrays in Swift]
To give a piece of data or data structure a starting (initial) value
instance [Classes]
An individual object; different instances can have different values for their attributes even if they share the same class.
instantiation [Classes; Instantiating classes]
Creating an object based on a class
interface (object-oriented) [Interfaces; Lists in other languages]
A structure that declares a set of methods for a class to implement; the methods are not implemented—the method signatures specify a capability for a class to implement. Every class that implements the interface must provide a body for all the methods.
intersection (set) [Sets in Python 3]
Given two sets, the intersection is a new set that contains the items in the first set that also belong to the second set; for example, the intersection of A, B, C and B, D, E is B (it is the only item in both sets).
isolated transaction [ACID and transactions]
While activities in a transaction are being completed, nothing else can make changes to the data involved.
J
jagged array [Jagged arrays]
A multidimensional array where each row can have a different length
JOIN keyword [Joining tables]
An SQL keyword that tells the database to consider two or more tables when making a selection
K
key, composite [Keys and unique values]
A key that is made up of two or more fields in the data
key, database [Keys and unique values]
A unique value used to refer to only one specific row or record
key, foreign [Relationships]
A key that is a primary key in one table but not in another
key, surrogate [Keys and unique values]
A field that is added to a table and has no natural key so that each row can have a unique value
key, synthetic [Keys and unique values]
A field that is added to a table and has no natural key so that each row can have a unique value
key-value pair [What are associative arrays?]
Entries in a dictionary; the key is used for indexing the dictionary to find the corresponding value.
L
leaf node [Introduction to tree data structures]
A node in a tree that has no child nodes
LIFO [What are stacks?]
Last in, first out—the policy that a stack follows
linear time [Measuring algorithm performance; Search arrays; Big O notation]
A big O of n; the operation takes time proportional to the number of elements in the dataset.
linked list [Linked lists; What are linked lists?]
A linear collection of data elements, sometimes called nodes; the data items in a linked list need not be contiguous—they are linked using pointers.
linking table (database) [Relationships]
A table that contains columns for foreign keys from the tables being associated
list (collection) [Arrays; What are arrays?]
A collection that groups pieces of data in a certain order and assigns the collection a name, also called an array or list in some programming languages; the position of each element is defined by an index.
log-linear time [Measuring algorithm performance]
A big O of n log n; the operation takes time proportional to the number of elements in a dataset times the logarithm of the number of elements.
logarithmic time [Measuring algorithm performance]
A big O of log n; the operation takes time proportional to the logarithm of the number of items in the dataset.
M
many-to-many relationship [Relationships; Many-to-many relationships]
A relation that associates many records in one table with multiple records in another table; for example, associating many customers with many purchases if you want to keep a record of each purchase each customer has ever ordered
master object [Identifying class responsibilities]
An object filled with many unrelated behaviors, seemingly existing to control everything else around it; this is something to avoid.
max heap [Understand heaps]
A heap (using trees) in which the root node always contains the largest value in the entire heap
memento design pattern [Design patterns]
A design pattern outlining a proven approach for restoring an object to a previous state
merge sort [The merge sort]
A sorting algorithm that recursively divides a set of data into smaller parts, sorts them, and then recombines the parts; in general, its time performance is log linear, O(n log n). This sort requires additional memory.
method [Classes]
Also called a behavior, a function that specifies what actions an object can perform; it is a block of code that can be called to perform some action, and it may return a value.
method signature [Polymorphism]
In Java, the method’s name and the number and types of its parameters
method, static [Static attributes and methods]
A variable or method that is shared across all objects in the same class, also referred to as a class-level or shared variable/method
min heap [Understand heaps]
A heap (using trees) in which the root node always contains the lowest value in the entire heap
minimum viable product [Defining requirements]
The bare necessities required to have a usable product
multidimensional array [Multidimensional arrays]
An array that has other arrays embedded in it, also called a multidimensional list in some programming languages
multiple inheritance [OOP support in different languages]
The condition where a derived class can inherit from more than one base class; C++ and Python support this.
multiplicity [Identifying class relationships]
In a UML diagram, a representation of one or more of something
mutator [Creating class diagrams: Behaviors]
See setter method.
MVP [Defining requirements]
The bare necessities required to have a usable product
N
node [Linked lists; What are linked lists?]
An element in a linked list
node, child [Introduction to tree data structures]
A node in a tree that is referred to by another node
node, leaf [Introduction to tree data structures]
A node in a tree that has no child nodes
node, parent [Introduction to tree data structures]
A node in a tree that refers to another node; the root node in a tree does not have a parent node—no other nodes refer to it.
node, root [Introduction to tree data structures]
The specific starting node in a tree
node, sibling [Introduction to tree data structures]
Two child nodes in a tree with the same parent node
non-deterministic algorithm [What are algorithms?]
An algorithm that attempts to produce a solution using successive guesses that become more accurate over time
non-functional requirements [Defining requirements]
Requirements that place constraints on how an application should function; for example, a banking transaction may have to comply with regulations.
normalization rules [Normalization]
Rules that help reduce redundancy and improve the integrity of data in a database
null [Numbers and other types]
A database value that indicates that a value is missing
numerical data type [Numerical data types]
Different ways numbers are classified, for example whole numbers and decimal numbers.
O
object [Primitive vs. reference types in memory]
A value in memory referenced by an identifier
one-to-many relationship [Relationships; One-to-many relationships]
A relation that associates one record in one table with multiple records in another table; for example, one item on a menu might be associated with multiple customers who choose it as their favorite.
one-to-one relationship [Relationships; One-to-one relationships]
A relation that associates only one record on one table with one—and only one—record on another table
ORDER BY clause [Sorting results]
An SQL clause that lets you specify the order in which results should be sorted; Ascending order is abbreviated as ASC and descending order as DESC.
ordered list search [Ordered list search; Search arrays]
An algorithm that determines whether an item is in a sorted list; it works by starting in the middle of the list and, depending on whether the value sought is less or greater than the item, discards the “wrong half” of the list. It repeats this process until the item is found or there are no elements left to search. Its time complexity is logarithmic, O(log n).
overloaded methods [Polymorphism; Classes with multiple constructors]
Several methods in the same class with the same name but a different set of input parameters
P
parallel algorithm [What are algorithms?]
An algorithm that can split up its data into parts and work on the parts simultaneously
parent class [Inheritance; Identifying inheritance situations]
See superclass.
parent node [Introduction to tree data structures]
A node in a tree that refers to another node; the root node in a tree does not have a parent node—no other nodes refer to it.
performance [FURPS+ requirements]
Measurement based on factors such as an app’s speed, efficiency, memory usage, and response time throughput
performance requirements [Defining requirements; FURPS+ requirements]
Constraints on an application’s performance, such as response time or number of simultaneous users
pointer [Primitive vs. reference types in memory]
An address that points to where a data structure is in memory
polymorphism [Polymorphism]
From the Greek words for “many forms”; see run-time polymorphism and compile-time polymorphism.
pop [Resizable arrays and language support; Implement stacks in Swift]
An operation that removes items from the end of an array or the top of a stack
precision (numerical) [Numerical data types]
The range of numerical values that a data type can store
precondition (use case) [Use cases]
A condition that must be true to begin the use case
predicate, SQL [Basic SQL]
Part of an SQL statement that sets parameters within which to operate
primary actor [Use cases]
In a use case, the person who will interact with the application
primary actor (use case) [Identifying the actors]
The person who initiates a scenario; this person might not be the most important actor.
primary key (database) [Keys and unique values]
The most important key in a table
primitive data type [Primitive types in memory]
Basic or value types; they have a fixed size that does not depend on the data inside them.
priority queue [Specialized queues]
A queue in which each element has a priority associated with it; the next item to be dequeued is the item with the highest priority.
procedural programming [Object-oriented thinking]
Writing a program as a long series of operations to execute
programming paradigm [Object-oriented thinking]
A set of ideas that is supported by many languages
property [Objects]
Data that an object has, also called a field or attribute
push [Resizable arrays and language support; Implement stacks in Swift]
An operation that adds items to the end of an array or the top of a stack
Q
quadratic time [Measuring algorithm performance]
A big O of n2; the operation takes time proportional to the square of the number of elements in a dataset.
queue [Stacks and queues; What are queues?]
A data structure where the first entry stored is also the first item removed; you can think of a queue like the line of customers in a store—the first person in line is the first person to be served.
quicksort [The quicksort]
A sorting algorithm that recursively divides a set of data into parts that are greater and less than a pivot point, sorts the subparts, and recombines them; its time performance is log linear, O(n log n). This sort does not require additional memory.
R
ragged array [Jagged arrays]
A multidimensional array where each row can have a different length
random access [Pros and cons of lists]
Access to a data structure in which you give an index and get the value at that slot immediately, as in an array
recursion [Understanding recursion]
When a function calls itself from within its own code
reference type [Primitive vs. reference types in memory]
A data type that uses a reference (pointer) to its specific value from an address where the item is stored rather than giving direct access to the data itself
referential integrity [Relationship rules and referential integrity]
A design principle in which ta database is aware of a relationship and will not let you modify data in a way that violates that relationship
relational database [Relational databases]
A database in which data are organized into relations—tables of related data
relationship [Relationships]
How records should be connected to one another
relationship, many to many [Relationships; Many-to-many relationships]
A relation that associates many records in one table with multiple records in another table; for example, associating many customers with many purchases if you want to keep a record of each purchase each customer has ever ordered
relationship, one to many [Relationships; One-to-many relationships]
A relation that associates one record in one table with multiple records in another table; for example, one item on a menu might be associated with multiple customers who choose it as their favorite.
relationship, one to one [Relationships; One-to-one relationships]
A relation that associates only one record on one table with one—and only one—record on another table
reliability [FURPS+ requirements]
Usually expressed in terms of how much system downtime is acceptable and how the system can be recovered
requirements [Defining requirements]
What an application or product needs to do
resizable array [Resizable arrays and language support]
An array whose length can be modified; programs can add additional elements to such an array.
root node [Introduction to tree data structures]
The specific starting node in a tree
row (database) [Relational databases; Understanding databases: Benefits of spreadsheets]
An instance of a given entity; for example, each customer in a database has their information in a table row.
run-time polymorphism [Polymorphism]
A process that allows programmers to access methods using the same interface on different types of objects that may implement those methods in different ways
runtime stack [Error tracing with stacks]
A stack that keeps track of the state of a program, including values and function calls; related to a call stack
S
search, binary [Ordered list search; Search arrays]
An algorithm that determines whether an item is in a sorted list; it works by starting in the middle of the list and, depending on whether the value sought is less or greater than the item, discards the “wrong half” of the list. It repeats this process until the item is found or there are no elements left to search. Its time complexity is logarithmic, O(log n).
search, ordered list [Ordered list search; Search arrays]
An algorithm that determines whether an item is in a sorted list; it works by starting in the middle of the list and, depending on whether the value sought is less or greater than the item, discards the “wrong half” of the list. It repeats this process until the item is found or there are no elements left to search. Its time complexity is logarithmic, O(log n).
search, unordered list [Unordered list search]
An algorithm that determines whether an item is in a list whose elements are in no particular order by examining each item in turn; its time complexity is linear, O(n).
searching algorithms [Common algorithms in programming]
Algorithms that find a specific piece of data inside a larger data structure
second normal form [Second normal form]
A database requirement that, for every non-key table column, each of the values must rely on only the whole key; the values must describe something about the row that can’t be determined from just the part of a key.
secondary actor (use case) [Diagramming use cases]
An actor that takes more of a reactive role than the primary actor
security requirements [Defining requirements]
Requirements that determine what security an application will need
SELECT statement [Narrowing query results]
An SQL statement that asks for specific rows in a database table
sequential access [Pros and cons of lists]
Access to a data structure in which you need to go through each item in turn to get to a specific index, as in a linked list
sequential algorithm [What are algorithms?]
An algorithm in which each operation is done in sequence
set [What are sets?]
A collection of different objects where the order doesn’t matter; no two objects in the set are identical.
SET statement [Modifying data]
An SQL statement that lets you update data in a database
setter method [Creating class diagrams: Behaviors]
A method that allows a program to set the value of an object’s attribute, also called a mutator
short int [Numerical data types]
An integer data type that is usually 16 bits long
sibling nodes [Introduction to tree data structures]
Two child nodes in a tree with the same parent node
signed data value [Numerical data types]
A numerical value that contains negative, zero, or positive values
single inheritance [Inheritance]
The condition where a derived class can only inherit from one class; Java is one such language.
singly linked list [Singly vs. doubly linked lists]
A linked list that only has a pointer to the next node in the list
snake case format [Converting class diagrams into code]
Naming convention where words in a variable name are separated by underscores, such as price_after_discount; Python tends to use this convention.
SOLID [General development principles]
A set of five separate but interrelated principles that apply to object-oriented design
sort, bubble [The bubble sort]
A sorting algorithm that works by repeatedly comparing each item to its neighbor and swapping them if needed; its time performance is quadratic, O(n2).
sort, merge [The merge sort]
A sorting algorithm that recursively divides a set of data into smaller parts, sorts them, and then recombines the parts; in general, its time performance is log linear, O(n log n). This sort requires additional memory.
sort, quicksort [The quicksort]
A sorting algorithm that recursively divides a set of data into parts that are greater and less than a pivot point, sorts the subparts, and recombines them; its time performance is log linear, O(n log n). This sort does not require additional memory.
sorting algorithms [Common algorithms in programming; Sort arrays]
Algorithms that take a set of data and place it into a particular order
space complexity [What are algorithms?]
The amount of memory and storage space an algorithm needs to do its work
SQL [Basic SQL]
Structured Query Language—a set of commands for interacting with the data in a database
SQL clause [Basic SQL]
A part of an SQL statement that has a keyword specifying some action to take and something to act on or use
SQL expression [Basic SQL]
Part of an SQL statement that sets parameters within which to operate
SQL injection [Access control, compliance, and injection]
A technique in which a user enters a value that is part of an SQL command to alter the query that should be running and change how it works
SQL predicate [Basic SQL]
Part of an SQL statement that sets parameters within which to operate
stack [Stacks and queues; What are stacks?]
A data structure where the first entry stored is the last entry removed; you can think of it as a stack of mail, where you handle the top items (most recently put on the stack) first and the bottom items (least recently put on the stack) last.
static analysis tool [General development principles]
A tool that will analyze your code and highlight things such as duplicated or unnecessary code
static variable/method [Static attributes and methods]
A variable or method that is shared across all objects in the same class, also referred to as a class-level or shared variable/method
statically typed language [OOP support in different languages]
A language in which the type of all variables is known at compile time; Java and C++ are statically typed.
stored procedure [Indexes, transactions, and stored procedures]
In databases, a kind of program that’s stored in the database server; it contains a series of commands that you can then reference and use when interacting with the database.
string [Primitive types in memory]
A data type composed of a sequence of characters
string data type [Primitive types in memory]
A data type composed of a sequence of characters
structural patterns [Design patterns]
Design patterns describing how classes are designed, using inheritance, composition, and aggregation
subclass [Inheritance; Identifying inheritance situations]
A class that inherits from another class, also called a child class; for example, a Car is a subclass of a Vehicle.
superclass [Inheritance; Identifying inheritance situations]
The class from which another class inherits attributes and methods, also called a ; for example, a Vehicle is a superclass of a Car.parent class
support requirements [Defining requirements; FURPS+ requirements]
Requirements that determine how an application will be supported
supportability [FURPS+ requirements]
How well an application can be tested, extended, serviced, and installed and configured
surrogate key [Keys and unique values]
A field that is added to a table and has no natural key so that each row can have a unique value
synthetic key [Keys and unique values]
A field that is added to a table and has no natural key so that each row can have a unique value
T
table, associative (database) [Relationships]
A table that contains columns for foreign keys from the tables being associated
table (database) [Relational databases]
A collection of rows (representing individual entities) and columns (the attributes of those entities)
table, linking (database) [Relationships]
A table that contains columns for foreign keys from the tables being associated
third normal form [Third normal form]
A database requirement that it should not be possible to determine any value in a column from a field that isn’t a key
time complexity [What are algorithms?]
How efficient an algorithm is relative to the size of the input it is given
TIMESTAMP [Columns and data types]
A database type that captures and stores the date and time when a row is updated
transaction, atomic [ACID and transactions]
A transaction must be indivisible; pieces of it can’t be separated out.
transaction, consistent [ACID and transactions]
Whatever a transaction does, it must leave the database in a valid or consistent state.
transaction, database [Indexes, transactions, and stored procedures]
A group of queries or statements treated as a block of activities; if one of the components fails for any reason, the whole group of statements is not executed, and anything that is partially completed is rolled back.
transaction, durable [ACID and transactions]
The information changed in a transaction must actually get written to the database.
transaction, isolated [ACID and transactions]
While activities in a transaction are being completed, nothing else can make changes to the data involved.
tree [Introduction to tree data structures]
A collection of nodes in which a node might be linked to one, two, or more nodes
tree, binary search [Understand binary search trees]
A binary tree in which the left child must be less than its parent and the right child must be greater than its parent
tree, unbalanced [Understand binary search trees]
A tree in which there are more levels of nodes on one side than the other
U
UML [Unified modeling language (UML)]
Unified Modeling Language— a graphical notation for drawing diagrams to visualize object-oriented systems
unbalanced tree [Understand binary search trees]
A tree in which there are more levels of nodes on one side than the other
union (set) [Sets in Python 3]
Given two sets, the union is a new set that contains all the items in both sets; for example, the union of A, B, C and B, D, E is A, B, C, D, E.
unit test [Software testing]
Code that tests a specific part of a program
unordered list search [Unordered list search]
An algorithm that determines whether an item is in a list whose elements are in no particular order by examining each item in turn; its time complexity is linear, O(n).
unsigned data value [Numerical data types]
A numerical value that can only contain zero or positive values
usability [FURPS+ requirements]
How intuitive an app is; accuracy and completeness of documentation
use case diagram [Diagramming use cases]
A UML diagram showing the relationship between actors and the different use cases in which they’re involved
use case scenario [Identifying the scenarios]
A description of a goal that an actor can accomplish in a single encounter; this should focus on the user’s intention—what they really want to accomplish.
V
VARCHAR [Columns and data types]
A database data type that contains a variable-length character string
variable, static [Static attributes and methods]
A variable or method that is shared across all objects in the same class, also referred to as a class-level or shared variable/method
visibility [Creating class diagrams: Behaviors]
Whether a method or attribute is exposed to other classes; in general, this can be public (accessible by other objects) or private (not accessible by other objects).
W
WHERE clause [Narrowing query results]
An SQL clause that lets you choose only specific records or records that match given criteria
Y
YAGNI [General development principles]
“You ain’t going to need it”—a principle that says you should avoid trying to account for every possible variation of everything you could ever possibly see



Glossary for Key Approaches
A
acceptance criteria [Where to start?; Write acceptance criteria]
The criteria that must be fulfilled to satisfy a user story and be accepted by a project stakeholder
access control [Authorization and access control issues]
Rules specifying who can access which parts of a database
ACID [SOAP overview]
An acronym that refers to the requirement that database transactions be atomic, consistent, isolated, and durable
ACL [Authorization and access control issues]
Access control list—lists which users have what kinds of access to system resources
adapter design pattern [The Adapter pattern defined]
A pattern that is used to convert the interface of a class into another interface that clients expect
@Afterall [Test structure]
in JUnit, an annotation for code that is to be executed after all tests are completed
@AfterEach [Test structure]
In JUnit, an annotation for code that is to be executed after every test
aggregate object [Understanding the Iterator pattern]
In the iterator design pattern, a collection of objects, like an array or arrayList
agile [TDD and agile]
A software development methodology characterized by a collaborative approach with continuous improvement and delivery of usable software
allocation, memory [Why do we need to manage the memory?; Allocating memory]
Reserving a chunk of memory for a certain bit of information
API [Web services, APIs, and microservices]
Application programming interface—the communication and data sharing mechanism between two different applications or systems; these are typically more lightweight than a web service and may not depend on a protocol such as SOAP.
arena (Python) [Memory management in Python]
The largest bits of memory, containing sequential blocks of memory
argument (GraphQL) [The structure of GraphQL queries]
A set of key-value pairs attached to a specific field
assert statement [Writing test cases]
A statement in a programming language that ensures that a certain condition is true at a given point in a program’s execution; if the condition is not true, the program generates an error.
assertEquals [Assertions]
An assert statement that checks that the values of an actual and expected object are the same
assertions, type-specific [Assertion frameworks]
Assertions that allow the use of use tests that are specific to a particular data type; for example, when testing a String data type, one can use a test such as endsWith.
AssertJ [TDD tools and frameworks]
A third-party assertion framework that extends core xUnit libraries
assertSame [Assertions]
An assert statement that checks that the actual and expected object refer to the same place in memory
assertThrows [Testing exceptions]
An assert statement that checks that a given exception occurs
attack tree [Embrace security in testing]
A diagram or flowchart showing how a resource might be attacked
authentication [Secure web services]
Validating the identity of a client who is attempting to call a web service that accesses secure data
authorization [Secure web services]
Deciding which data an authenticated user can access or modify
automated [Make a test plan]
Part of a test plan that tells whether a test is automated or not
automatic memory management [Why do we need to manage the memory?]
A system of managing memory that is built into the programming language and runtime; Python, Java, and JavaScript take care of memory management for you.
automatic variables (C language) [The C way: Allocating memory]
Another name for local variables; they are automatically freed when no longer needed.
B
base object [Extending behavior with composition]
In the decorator design pattern, the object that has other objects “wrapped around it” by composition
@BeforeAll [Test structure]
in JUnit, an annotation for code that is to be executed before the test class instance is created
@BeforeEach [Test structure]
In JUnit, an annotation for code that is to be executed before every test
bind variables [Database issues]
Variables whose values are inserted into an SQL statement (as opposed to concatenating with user input strings)
black box testing [Box testing]
A form of box testing where you know the input and output but have no knowledge about the internals of an application
blacklisting [Input validation issues]
Looking for key patterns (such as <script> tags in HTML) and filtering them out
block (Python) [Memory management in Python]
The actual memory addresses that are going to be assigned when doing memory management
block starting symbol (C language) [The C way: Allocating memory]
Block starting symbol—a special area of memory in the C runtime for static and global variables that are un-initialized at compile time
body (SOAP) [SOAP overview]
A required part of a SOAP message that contains the actual XML data that the server transmits
bottom-up approach [What is test-driven development (TDD)?]
An approach to building software that involves taking small, incremental steps that are joined together to create the product
box testing [Box testing]
Testing performed so that there is a holistic approach
broken cryptographic routine [Cryptography issues]
A cryptographic algorithm that has been cracked, theoretically can be cracked, or has a flaw that has been identified
brute-force attack [Authentication and password issues]
An attack in which the malicious actor continuously submits many passwords with the hope of finding one that works
BSS [The C way: Allocating memory]
Block starting symbol—a special area of memory in the C runtime for static and global variables that are un-initialized at compile time
buffer overflow vulnerability [Memory management issues]
An attack that writes, for example, a 10-byte buffer with 13 bytes of data, which may cause code to be executed
bug bash [Have bug bashes]
A week in which team members focus entirely on fixing bugs; it is recommended to have these two to four times a year.
bug book [Document what you understand]
A document describing security bugs found in a system
bug priority [Triage bugs]
How fast a bug should be fixed
bug severity [Triage bugs]
How impactful a bug is to the business
bug triage [Triage bugs]
Classification of an application bug (problem) by its severity and the priority for fixing it
build phase [Get involved throughout the SDLC]
The part of the SDLC where the software is actually constructed
C
call stack [Stack memory]
A stack that keeps track of the order of function calls
certificate [Communication channel issues]
An electronic document that verifies the identity of its owner
changing functional declaration [Refactor to improve the design]
In TDD, changing the name of a method to make it easier to understand what it does
CI/CD [Embrace security in testing]
Continuous integration/continuous deployment—frequent rebuilding and delivery of a software system
client-side validation [Input validation issues]
Validating input in the browser or client application; this should be done in addition to, but not as a substitute for, server-side validation.
code smell [Refactor to improve the design]
Valid code that somehow doesn’t seem right; it doesn’t pass the “smell test”
compacting [Actual removing or sweeping]
Closing gaps in heap memory when removing objects
composition, vs. inheritance [Why HAS-A is better than IS-A]
A design principle that says, if you have a choice, use composition rather than inheritance because typically, composition leads to a more flexible design
concurrency [Heap vs. stack memory]
Multiple things happening at the same time
configuration [Configuration issues]
The feature flags, options, and other data elements that an application needs to run but that can be optionally modified at startup or runtime
containerized [Embrace security in deployment]
A situation in which software is packaged with all its dependencies and configuration information
convention [Writing test cases]
An unwritten rule that software developers are expected to follow; for example, in unit testing, a convention is to keep code and test cases separate. Another example: when writing Java, variable names by convention begin with lowercase letters; class names begin with uppercase letters.
copy, deep [Best practices with memory]
A copy of the object and its attributes, and their attributes, and so on; the data itself is copied.
copy, shallow [Best practices with memory]
A copy of an object reference; the data referred to is not copied.
CPU [What is memory?]
Central processing unit of a computer
cross-site scripting [Input validation issues]
An attack in which a bad actor injects a script (in a programming language) that is executed in the browser
CVE [Dependency issues]
Common Vulnerabilities and Exposures—a catalog of publicly disclosed security vulnerabilities
CWE [Dependency issues]
Common Weakness Enumeration—a listing of common software and hardware weaknesses with security ramifications (from https://cwe.mitre.org)
cyclic reference [Garbage collection]
Two objects that reference each other
D
dangling pointer [The C way: Deallocating and reallocating memory]
A reference to a memory area that has been deallocated
data segment (C language) [The C way: Allocating memory]
Data segment—an area of memory in the C runtime for initialized global and static variables
DBA [Database issues]
Database Administrator -- the person who manages a database. This may include configuration, security, updates, etc.
deallocation, memory [Why do we need to manage the memory?; Deallocating memory]
Releasing memory when information is no longer needed
decorator design pattern [Understanding the Decorator pattern]
A design pattern in which additional responsibilities are added to an object dynamically
deep copy [Best practices with memory]
A copy of the object and its attributes, and their attributes, and so on; the data itself is copied.
define phase [Get involved throughout the SDLC]
The part of the SDLC where requirements are defined for the developers; writing of specifications and acceptance criteria
DELETE operation (REST) [REST overview]
An operation to remove a resource
dependency graph [Dependency issues]
A document showing which software dependencies are vulnerable to an attack
dependent object [The Observer pattern defined]
In the observer design pattern, the “many” objects in a one-to-many relationship; for example, one publisher has many subscribers, and the subscribers are dependent objects.
deploy phase [Get involved throughout the SDLC]
The part of the SDLC where the product is released to the customer
design pattern, adapter [The Adapter pattern defined]
A pattern that is used to convert the interface of a class into another interface that clients expect
design pattern, decorator [Understanding the Decorator pattern]
A design pattern in which additional responsibilities are added to an object dynamically
design pattern, factory method [The Factory Method pattern]
A pattern that allows programmers to decouple the process of creating objects from the clients that use those objects; it defines an interface for creating an object but lets subclasses decide which classes to instantiate.
design pattern, iterator [Understanding the Iterator pattern]
A design pattern that provides a way to access the elements of an aggregate object sequentially without exposing its underlying representation
design pattern, observer [The Observer pattern defined]
A pattern that defines a one-to-many dependency between objects so that when one object changes state, all its dependents are notified and updated automatically
design pattern, strategy [What are design principles?]
A pattern that separates out an object’s behavior in a flexible and extensible way
design phase [Get involved throughout the SDLC]
The part of the SDLC where the team builds mockups and prototypes
design principle, open-closed [Understanding the open-closed principle]
A principle that says classes should be open for extension but closed for modification
design principle, single responsibility [The single responsibility principle]
A principle that says a class should have only one reason to change
design principles [What are design principles?]
General guidelines for developing programs, as opposed to design patterns, which are specific design solutions for common object-oriented programs
development sprint [Getting bugs fixed]
A specific block of time in which developers are to complete a set of goals; this is part of the agile development methodology.
DevOps [Roles and responsibilities]
Practices for integrating and automating development and information technology operations
DevSecOps [Break what you build]
A methodology for integrating and automating a system’s development, security, and operations
DoS [Security testing]
Denial of service (DoS)—an attack in which a bad actor uses automated scripts to flood a server with traffic so it cannot handle legitimate requests
DS [The C way: Allocating memory]
Data segment—an area of memory in the C runtime for initialized global and static variables
dummy object [Test doubles]
A test double object created just to make code compile
dynamic analysis [Implement best practices]
Analysis of run-time performance of a system: time and memory usage, etc.
dynamic memory allocation [Why do we need to manage the memory?; Allocating memory]
Memory allocation that occurs during runtime
E
endurance testing [Performance testing]
A form of performance testing done to make sure an application can handle the expected load over a long period of time
envelope [SOAP overview]
An XML file that contains the multiple parts of a SOAP message
error messaging, information disclosure through [Error handling issues]
A situation in which an error message provides information useful to an attacker, such a stack trace or an authentication error that tells that a username is valid but the password is not
error, out of memory [Out of Memory error]
An error that occurs when the system cannot allocate a requested memory block anymore
error, stack overflow [Stack memory]
An error that occurs when a program exceeds the size limit of stack memory
escaping references [Best practices with memory]
The situation when an object is accessed unintentionally through another function
expected result [Make a test plan]
Part of a test plan that describes what the outcome will be for a given result
extract function refactoring [Refactor to improve the design]
The technique of moving out a certain functionality to make a method’s implementation align with its intention
F
factory method design pattern [The Factory Method pattern]
A pattern that allows programmers to decouple the process of creating objects from the clients that use those objects; it defines an interface for creating an object but lets subclasses decide which classes to instantiate.
fake object [Test doubles]
A test double method that provides some functionality but is not production ready—it is better than having nothing at all.
faking it [TDD and agile]
In TDD, writing code only to pass the test and no more
fault (SOAP) [SOAP overview]
An optional part of a SOAP message containing information about any errors that might occur during message processing
field name (GraphQL) [The structure of GraphQL queries]
Each field represents a unit of data you are asking for.
fragmentation, heap [Deallocating memory]
The situation where gaps occur in the heap when memory is allocated and deallocated
free (C language) [The C way: Deallocating and reallocating memory]
A function that deallocates memory
functional declaration, changing [Refactor to improve the design]
In TDD, changing the name of a method to make it easier to understand what it does
G
garbage collection [Deallocating memory]
A process by which the runtime system keeps track of which items in memory are no longer needed and deletes them
GET operation (REST) [REST overview]
An operation to retrieve a resource
given [Write acceptance criteria]
Part of an acceptance criteria that specifies the precondition or beginning state
GraphQL [GraphQL overview]
A query language for APIs; it is a syntax that describes how to ask for data and is generally used to load data from a server to a client.
gray box testing [Box testing]
A form of box testing where scenarios examine the interaction between the outside and inside of the box; this includes such things as integration testing.
H
Hamcrest [TDD tools and frameworks]
A third-party assertion framework that extends core xUnit libraries
happy path scenario [Manual testing]
A scenario with a successful result
hasNext method [Using the Iterator pattern]
A method in the iterator design pattern that determines whether there are more items to iterate over in the aggregate object
HATEOAS [HATEOAS overview]
Hypermedia as the Engine of Application State—the principle that specifies that a RESTful API should provide enough information to the client to interact with the server.
header (SOAP) [SOAP overview]
An optional part of a SOAP message that contains message attributes
heap fragmentation [Deallocating memory]
The situation where gaps occur in the heap when memory is allocated and deallocated
heap memory [Heap memory]
A part of RAM used for storing values that need to be accessed throughout the entire application; it also holds larger values that might not fit in the limited stack memory.
I
infected file upload [File and I/O issues]
A file that a malicious actor uploads; the file contains some form of malware.
information disclosure through error messaging [Error handling issues]
A situation in which an error message provides information useful to an attacker, such a stack trace or an authentication error that tells that a username is valid but the password is not
inheritance [Revisiting inheritance]
A process for passing on attributes and methods from other existing classes to a new class
inheritance, vs. composition [Why HAS-A is better than IS-A]
A design principle that says, if you have a choice, use composition rather than inheritance because typically, composition leads to a more flexible design
initialization vector [Cryptography issues]
A random (or pseudorandom) number used to prevent malicious actors from repeating or mimicking previous valid transactions
injection attack [Input validation issues]
An attack in which a bad actor introduces input that is executed as code
input validation issues [Input validation issues]
Security problems caused by improper validation of input, allowing malicious input into the system
integration testing [Integration testing]
Testing that focuses on the interaction between components at lower layers of the application, seeing how the system reacts to certain actions; these tests have some knowledge of how the system works internally.
interface (object-oriented) [Trying interfaces]
A structure that declares a set of methods for a class to implement; the methods are not implemented—the method signatures specify a capability for a class to implement. Every class that implements the interface must provide a body for all the methods.
iteration pattern as language feature [The Iterator pattern as language feature]
Language features that hide an iterator design pattern behind the scenes and make it easy to iterate through collections of values; in Java, this is the enhanced for; in Python, it is the for/in statement; in JavaScript, it is the for/of statement.
iterator design pattern [Understanding the Iterator pattern]
A design pattern that provides a way to access the elements of an aggregate object sequentially without exposing its underlying representation
iterator object [Understanding the Iterator pattern]
In the iterator design pattern, an object that knows how to iterate over an aggregate object
J
Java EE [Create web service]
Java Enterprise Edition—a version of Java with specifications for enterprise capabilities such as web services and distributed computing.
JAX-WS [Create web service]
Java API for XML-Based Web Services
Jira [Report bugs]
A tool used for tracking features, user stories, tasks, and bug reports
JSON [Benefits of REST]
JavaScript Object Notation. The json.org website describes it as “a lightweight data-interchange format. It is easy for humans to read and write. It is easy for machines to parse and generate. It is based on a subset of the JavaScript Programming Language...”
JUnit [xUnit and jUnit]
The xUnit framework, translated to Java
L
language transparency [Advantages of web services]
The capability to have a web service in one language with the client written in a totally different language; they communicate through a common language, such as XML or JSON.
latency [Considerations of web services]
The amount of time it takes once a request is made to receive a response
latest result [Make a test plan]
Part of a test plan that gives the most recent result of executing a test (pass or fail)
load testing [Performance testing]
Testing that checks an application’s ability to perform under anticipated user loads; the objective is to identify the maximum operating capacity of an application.
log aggregation attack [Logging and output issues]
An attack in which someone with access to system logs can find sensitive information in error logs
loose coupling (REST) [Benefits of REST]
Systems designed so that changes and enhancements to web services don’t break clients that are already using them
loosely coupled [Understanding the observer pattern; The Observer pattern and loose coupling]
A situation in which objects interact with one another but don’t know a lot about each other
M
main memory [What is memory?]
Analogous to human short-term memory; when you shut down a computer, the main memory gets erased. This is called volatile.
malloc (C language) [The C way: Allocating memory]
A function that allocates heap memory
man in the middle [Communication channel issues]
An attack in which a bad actor intercepts, and possibly alters, the communication channel between two parties
manual memory management [Why do we need to manage the memory?]
A system of managing memory in which the developer has to allocate and deallocate memory; this is the way C and C++ work.
manual testing [Manual testing]
Testing that follows the steps as a user performing workflows in the application; its goal is to uncover any issues in application functionality and usability.
matcher [Assertion frameworks]
In Hamcrest, a predicate (condition) that returns true if an object matches what the condition specifies
Maven [What you should know]
A framework for building Java applications
memory allocation [Why do we need to manage the memory?; Allocating memory]
Reserving a chunk of memory for a certain bit of information
memory allocation, dynamic [Why do we need to manage the memory?; Allocating memory]
Memory allocation that occurs during runtime
memory allocation, static [Why do we need to manage the memory?; Allocating memory]
Memory allocation that occurs before a program is executed
memory deallocation [Why do we need to manage the memory?; Deallocating memory]
Releasing memory when information is no longer needed
memory, heap [Heap memory]
A part of RAM used for storing values that need to be accessed throughout the entire application; it also holds larger values that might not fit in the limited stack memory.
memory leak [Garbage collection]
A situation where memory should be deallocated but has not and therefore cannot be reached anymore
memory management [Why do we need to manage the memory?]
The allocation and releasing of memory
memory management, automatic [Why do we need to manage the memory?]
A system of managing memory that is built into the programming language and runtime; Python, Java, and JavaScript take care of memory management for you.
memory management, manual [Why do we need to manage the memory?]
A system of managing memory in which the developer has to allocate and deallocate memory; this is the way C and C++ work.
memory profiler [Best practices with memory]
A program that lets you see how memory is used when a program runs
memory, stack [Stack memory]
A stack that stores the variables created by functions; when entering a function, memory is allocated on the stack. When the function is done, the stack memory is deallocated.
microservice [Web services, APIs, and microservices]
Fully contained, individual components that communicate with each other in calling clients
mob testing session [Have bug bashes]
A one-hour interval when team members get together to test particular features in an application
mock [Mocking]
An object that simulates the expected behavior of some external dependency (as opposed to its state)
mocking framework [Mocking]
A framework that complements xUnit and can be integrated into the regular TDD setup
Mockito [Mocking]
An API that is the most popular mocking framework among Java developers
multi-threading [Memory management in Python]
An approach to writing code that executes multiple threads (tasks) concurrently
mutation (GraphQL) [The structure of GraphQL queries]
A GraphQL operation for modifying server-side data
N
next() method [Using the Iterator pattern]
A method in the iterator design pattern that retrieves the next item in the aggregate object
nonce [Cryptography issues]
A random (or pseudorandom) number used to prevent malicious actors from repeating or mimicking previous valid transactions
O
observer design pattern [The Observer pattern defined]
A pattern that defines a one-to-many dependency between objects so that when one object changes state, all its dependents are notified and updated automatically
on-the-wire attack [Communication channel issues]
An attack on a communication channel in which the bad actor has access to the network of either the client or server
open-closed design principle [Understanding the open-closed principle]
A principle that says classes should be open for extension but closed for modification
OpenAPI [Document an API]
A standard, language-agnostic interface to HTTP APIs
out of memory error [Out of Memory error]
An error that occurs when the system cannot allocate a requested memory block anymore
OWASP [Configuration issues]
Open Worldwide Application Security Project —described by their website as “a nonprofit foundation that works to improve the security of software.”
P
partial failure [Considerations of web services]
The condition in which a component like a server or network fails to respond to a request
password hashing algorithm [Authentication and password issues]
An algorithm that encrypts a password
pen test [Break what you build]
penetration test—a simulated attack on a system to evaluate its security
performance testing [Performance testing]
Testing to benchmark how a system performs under load
plan phase [Get involved throughout the SDLC]
The part of the SDLC where business requirements and use cases are gathered from the customer
pointer (C language) [The C way: Allocating memory]
A reference to a memory address where a value is stored
POJO [Create web service]
Plain old Java object—an object that has no special restrictions beyond those imposed by the Java programming language.
polymorphism, replace conditional with [Refactor to improve the design]
In TDD, a more complex refactoring technique requiring changes at the class level
pool (Python) [Memory management in Python]
A subdivision of an arena containing blocks of memory of a specific same size
POST operation (REST) [REST overview]
An operation to create a resource
Postman [Consume a RESTful API via Postman]
A tool used to test an API
profiler, memory [Best practices with memory]
A program that lets you see how memory is used when a program runs
PUT operation (REST) [REST overview]
An operation to update a resource
Q
QA [What is quality assurance?]
Quality assurance—a systematic process used to determine whether a product meets specifications
QA deliverables [Create a test strategy]
Part of the test strategy that describes what QA will provide to the team; this may include test plans for each feature, issues reported for bugs, and a release process document.
quality assurance [What is quality assurance?]
Quality assurance—a systematic process used to determine whether a product meets specifications
query document [The structure of GraphQL queries]
A string you use in GraphQL that is sent to the server to process and request data
query (GraphQL) [The structure of GraphQL queries]
Part of the GraphQL type system that allows you to get information about specific fields from objects
R
rainbow table [Cryptography issues]
A precomputed table of results of a cryptographic hash algorithm
RAM [What is memory?]
Random-access memory; see main memory.
range-act-assert pattern [Test structure]
A TDD test structure that arranges the elements required to test, acts on the elements, and then asserts that the result is as expected
realloc (C language) [The C way: Deallocating and reallocating memory]
A function that re-allocates memory
red-green-refactor cycle [The iterative red-green-refactor cycle]
The process of taking a failing test case to writing the code to pass the test case; this may involve refactoring to, for example, get rid of test cases that are no longer necessary.
refactoring [What is test-driven development (TDD)?; Refactor to improve the design]
Improving the internal structure of code to make it easier to understand or modify without changing its external behavior
refactoring, extract function [Refactor to improve the design]
The technique of moving out a certain functionality to make a method’s implementation align with its intention
reference counter [Garbage collection; Memory management in Python]
A counter that tells how many references exist to an object on the heap
references, escaping [Best practices with memory]
The situation when an object is accessed unintentionally through another function
replace conditional with polymorphism [Refactor to improve the design]
In TDD, a more complex refactoring technique requiring changes at the class level
resolver (GraphQL) [The structure of GraphQL queries]
Part of the GraphQL type system that is responsible for getting data to the client
REST [Web services overview; REST overview]
Representational State Transfer—a service that uses a web protocol, HTTP (HyperText Transfer Protocol), to access resources
RESTful API [REST overview]
An API that uses REST for communicating between client and server
risk register [Document what you understand]
A document detailing a system’s security risks and how to mitigate those risks
ROM [What is memory?]
Read-only memory—slower than RAM but is non-volatile and doesn’t disappear when the computer is shut down; usually used for the logic needed to start a computer and operating system
S
sad path scenario [Manual testing]
A scenario that returns errors or does not have results
salt [Cryptography issues]
Random data that is part of a cryptographic hash; this prevents bad actors from building tables of cryptographic hash results.
sandboxing [File and I/O issues]
Running a program in its own environment, separate from other programs
scenario [Make a test plan]
Part of a test plan that explains the steps or actions that will be executed
scenario, happy path [Manual testing]
A scenario with a successful result
scenario, sad path [Manual testing]
A scenario that returns errors or does not have results
schema (GraphQL) [The structure of GraphQL queries]
Part of the GraphQL type system that defines a set of types
scope of testing [Create a test strategy]
Part of the test strategy that describes what types of tests exist for this project, which tools are used to write each type, and who owns them
scripting attack [Input validation issues]
An attack in which a bad actor injects a script (in a programming language) that is executed in the browser
scrum [Embrace security in design]
A team collaboration approach to software design
SDLC [Embrace security in design; Get involved throughout the SDLC]
Software development life cycle—a process that produces high-quality software in the shortest amount of time; it includes detailed steps for how to effectively develop, change, and maintain a software system.
secondary storage [What is memory?]
Analogous to human long-term memory. This storage persists even when the computer is shut down. An example is files and programs on your hard drive. This is called non-volatile.
secret storage service [Internal data management issues]
A way to store passwords or other authentication information securely
security testing [Security testing]
Testing performed to reveal flaws or vulnerabilities that can be exposed by users, causing an app to behave in unexpected ways or stop it from working
selection set [The structure of GraphQL queries]
A set of key-value pairs attached to a specific field
server-side validation [Input validation issues]
Validating user input when it is received by the server; this should always be done, and be done before the input is processed further.
service, denial of [Security testing]
Denial of service (DoS)—an attack in which a bad actor uses automated scripts to flood a server with traffic so it cannot handle legitimate requests
session [Session management issues]
Data that contains application state; it may be necessary when using HTTP, which is a stateless protocol.
session fixation attack [Session fixation]
An attack in which a bad actor uses a pre-authentication token that was not updated to a secure token after logging in
session hijacking [Session hijacking]
A vulnerability caused when a bad actor can predict a session token and use it to access a user’s session data
set up-test-tear down pattern [Test structure]
A TDD test structure that sets up a fixture, does the test, and then destroys any older objects or re-initializes any other variables modified in previous tests; this can sometimes make test cases run faster.
shallow copy [Best practices with memory]
A copy of an object reference; the data referred to is not copied.
single responsibility design principle [The single responsibility principle]
A principle that says a class should have only one reason to change
soak testing [Performance testing]
A form of performance testing done to make sure an application can handle the expected load over a long period of time
SOAP [Web services overview; SOAP overview]
Simple Object Access Protocol—a service that uses XML (Extensible Markup Language) to send messages
SoapUI [Consume a SOAP web service via SoapUI]
A tool for testing SOAP web services
source control [Implement best practices]
Software that helps keep track of changes and updates to the source code for a project
spoofing attack [Communication channel issues]
An attack in which a bad actor presents false data on the network; for example, giving a false IP (Internet Protocol) address
spy [Test doubles]
A test double variable used to check that, for example, some event has occurred or count how many times something has happened
SQL injection [Input validation issues; Security testing]
A technique in which a user enters a value that is part of an SQL command to alter the query that should be running and change how it works
SSL [Communication channel issues]
Secure Sockets Layer—a now-deprecated predecessor of TLS
stack, call [Stack memory]
A stack that keeps track of the order of function calls
stack memory [Stack memory]
A stack that stores the variables created by functions; when entering a function, memory is allocated on the stack. When the function is done, the stack memory is deallocated.
stack overflow error [Stack memory]
An error that occurs when a program exceeds the size limit of stack memory
stateless [REST overview]
The condition in which a server will not remember or store any state about the client that made the call
static analysis [Implement best practices]
Analysis of the source code for such things as performance, memory usage, unused variables, etc.
static memory allocation [Why do we need to manage the memory?; Allocating memory]
Memory allocation that occurs before a program is executed
strategy design pattern [What are design principles?]
A pattern that separates out an object’s behavior in a flexible and extensible way
stress testing [Performance testing]
A form of performance testing that tests an application under extreme workloads; the objective is to identify the breaking point of an application.
stub [Test doubles]
A test double method that returns a value, feeding desired inputs into the tests rather than reflecting real behavior
subject object [The Observer pattern defined]
In the observer design pattern, the “one” object in a one-to-many relationship; for example, one publisher has many subscribers, and the publisher is the subject object.
subscription (GraphQL) [The structure of GraphQL queries]
A GraphQL operation that allows for notification of changes to data in real time
sweeping [Actual removing or sweeping]
The actual removal of objects on the heap during garbage collection
T
TDD [Small steps to great things]
Test-driven development
test-code-refactor [What is test-driven development (TDD)?]
A development cycle in which a programmer first writes a failing test case and then writes the code that passes that test case
test double [Test doubles]
A proxy to represent an external dependency when doing tests in TDD
test-driven approach [What is test-driven development (TDD)?]
An approach to building software in which, given requirements, a programmer writes a set of unit test cases that will drive the rest of development
test fixture [Test structure]
In TDD, a block of code that represents a certain state of the system for test cases to run
test management [Create a test strategy]
Part of the test strategy that describes what resources are needed to carry out testing in terms of tooling, environments, supported platforms and versions, and test data
test phase [Get involved throughout the SDLC]
The part of the SDLC where QA has the major role: testing that the software meets specifications
test plan [Make a test plan]
A QA plan for testing a feature
test strategy [Create a test strategy]
A plan that describes how a product will be tested; it usually consists of an introduction, references (relevant project links), QA deliverables, test management, and scope of testing.
testing, black box [Box testing]
A form of box testing where you know the input and output but have no knowledge about the internals of an application
testing, box [Box testing]
Testing performed so that there is a holistic approach
testing, endurance [Performance testing]
A form of performance testing done to make sure an application can handle the expected load over a long period of time
testing, gray box [Box testing]
A form of box testing where scenarios examine the interaction between the outside and inside of the box; this includes such things as integration testing.
testing, integration [Integration testing]
Testing that focuses on the interaction between components at lower layers of the application, seeing how the system reacts to certain actions; these tests have some knowledge of how the system works internally.
testing, load [Performance testing]
Testing that checks an application’s ability to perform under anticipated user loads; the objective is to identify the maximum operating capacity of an application.
testing, manual [Manual testing]
Testing that follows the steps as a user performing workflows in the application; its goal is to uncover any issues in application functionality and usability.
testing, performance [Performance testing]
Testing to benchmark how a system performs under load
testing, scope of [Create a test strategy]
Part of the test strategy that describes what types of tests exist for this project, which tools are used to write each type, and who owns them
testing, security [Security testing]
Testing performed to reveal flaws or vulnerabilities that can be exposed by users, causing an app to behave in unexpected ways or stop it from working
testing, soak [Performance testing]
A form of performance testing done to make sure an application can handle the expected load over a long period of time
testing, stress [Performance testing]
A form of performance testing that tests an application under extreme workloads; the objective is to identify the breaking point of an application.
testing, UI automation [UI automation testing]
Testing of a user interface (UI) accomplished by running scripts rather than manually entering input
testing, white box [Box testing]
A form of box testing that focuses on the internals of the application and what is happening at the code or system level
text segment (C language) [The C way: Allocating memory]
An area of memory for compiled code that is being stored
then [Write acceptance criteria]
Part of an acceptance criteria that specifies the expected outcome of a scenario
thread [Heap vs. stack memory]
A part of execution within a concurrent application; every thread has its own stack.
TLS [Communication channel issues]
Transport Layer Security—a cryptographic protocol on the transport layer of the communications network
token [Session management issues]
A unique identifier generated at the start of a session
top-down approach [What is test-driven development (TDD)?]
An approach to building software that starts from the “big picture” and breaks it down into smaller steps
triage, bug [Triage bugs]
Classification of an application bug (problem) by its severity and the priority for fixing it
Truth [Assertion frameworks]
A third-party assertion framework that extends core xUnit libraries
two-way certificate pinning [Internal data management issues]
Having a client and server authenticate each other
type-specific assertions [Assertion frameworks]
Assertions that allow the use of use tests that are specific to a particular data type; for example, when testing a String data type, one can use a test such as endsWith.
U
UI automation testing [UI automation testing]
Testing of a user interface (UI) accomplished by running scripts rather than manually entering input
unit test [What is test-driven development (TDD)?]
Code that tests a specific part of a program
unit testing [Implement best practices]
Tests for individual units (parts) of source code
update method [The Observer pattern defined]
In the observer design pattern, this is a method that the subject object calls to update its dependent objects.
URI [REST overview]
Uniform Resource Identifier, accessed by web links
use case [Where to start?]
An informal description, written in a natural language, that describes a feature of a software product
user persona [Embrace security in testing]
A fictional character representing a user of a system
user story [Where to start?]
An informal description, written in a natural language, that describes a feature of a software product
V
virtual memory [What is memory?]
Secondary storage used to manage data that cannot fit into main memory
W
waterfall [Embrace security in design]
A top-down approach to software design
web service [Web services overview]
A service that allows different systems to talk to each other over the internet
when [Write acceptance criteria]
Part of an acceptance criteria that specifies the input or action of a scenario
white box testing [Box testing]
A form of box testing that focuses on the internals of the application and what is happening at the code or system level
whitelisting [Input validation issues]
Ensuring that input matches a specific pattern before being accepted
WSDL [SOAP overview]
Web Services Description Language—a language used to give the client information on what services a web service can offer
X
XSS [Input validation issues]
An attack in which a bad actor injects a script (in a programming language) that is executed in the browser
xUnit [xUnit and jUnit]
A framework for unit testing
Z
zero-day [Memory management issues]
A vulnerability that was previously unknown; the developers have had “zero days” to fix it before it is exploited.
























