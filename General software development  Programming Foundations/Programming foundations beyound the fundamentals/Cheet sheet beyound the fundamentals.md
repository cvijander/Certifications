
Collection
grouping multiple items together and storing them with a single name , called a variable

Creating a Collection
 -uses your code structure to indicate that multiple pieces of data are related 
 -avoids creating a  potentially huge number of variables to track within our code
 -offers simplified syntax 

List
Simple collection that groups pieces of data together in a certain order and assigns the collection a name 

in python   guests = ['Maria','Gordon','Bob']

Dictionary data lets you store related information.

in python  food= {
    'appetizer':'hummus',
    'entree':'gyro wraps',
    'dessert':'baklava'
}


Each item in a list is automatically assigned a consecutive number based on its position known as an index number.Index number starts at 0 
To reference the data at a given list index you reference the variable name followed by the index number in square brackets 

print(guests[0])

Referencing data in a dictionary is similar to a list reference. To reference a dictionary item,
start by referencing the name of the variable that stores the dictionary value.Dictionary doesn't use index numbers because each item in a dictionary has a label 

print(food['entree'])


Iteration
Repeats the same procedure multiple times until it reaches a specified endpoint

Loop
code that iterates, moving from beginning to end of the process, then starting over
-specify the data
-what should happen to the data during each iteration
-indicate when the loop should stop

Infinite loop
Bug that can occur when the ending condition is omitted or specified incorrectly

for loop in python look like this
for spice in spices 

For 
specifies a variable name that we can use in each iteration of the loop to reference the current value

spice is single unit in that collection 

in indicates that what follows is the set of values that we want to iterate through

spices - list, group

for spice in spices: 
   print(spice)


   Using loops with lists or other collections allows us to works with sets of data without writing repetitive code 

 By  combining iteration with other programming tools   you can build your own complex and amazing projects 

 While 
 creates a loop in python 
 While statements let us write code that moves our program along a certain point before handling off control to other statements


 Module
 Python file that contains code, like variables or functions 

 Package or Library
 Using multiple modules together so they are distributed and used in a group

 Framework
 When a set of code is not just used together but used in a specific way

 When the application you are working on becomes large and complex it is common to split your code into different modules as a way of organizing it


String is a collection of characters assembled together in a specific way
Those characters can be taken apart and then reassembled differently

Concatenation
When multiple strings are combined into a single string
In python and many other languages we use + sign to concatenate strings

value = input('Enter a number: ')
print(value + ' is my favorite number')

Number in programming has different qualities than a string, 
programming languages don't treat a number like a collection of characters ,
instead number is amount.

In order to use number we need to convert a data input to a number data type so we can use as a number 

The ways you can change a peace of data are limited by the type of data .Sometimes accomplishing what you want involves first changing the data to the appropriate type

We can user different methods on string, we can break string in smaller pieces, on by one character, we can change order, we can even make it capitalize

in python
text = 'hello'
text.capitalize()
=> 'Hello'

we are calling a method on a variable , this is case in python

text = "borko"
capitalized = text.capitalize()
print(capitalized)  # Output: "Borko"
capitalize() is a instance method

 C# – Example  1: char.ToUpper + Substring (combination of static and instance methods)
 string text = "borko";
 string capitalized = char.ToUpper(text[0]) + text.Substring(1).ToLower();
 Console.WriteLine(capitalized);  // Output: "Borko"

C# – Example 2: Substring(0,1).ToUpper + rest (instance method)

string text = "bOrKo";
string capitalized = text.Substring(0, 1).ToUpper() + text.Substring(1).ToLower();
Console.WriteLine(capitalized);  // Output: "Borko"

C# – Example 3 -  Extension methods (Python-style Capitalize()) -creating a method

public static class StringExtensions
{
    public static string Capitalize(this string input)
    {
        if (string.IsNullOrEmpty(input))
            return input;

        return input.Substring(0, 1).ToUpper() + input.Substring(1).ToLower();
    }
}
Calling a method:
string name = "borko";
Console.WriteLine(name.Capitalize());  // Output: "Borko"

For searching a specific string, like word, phrase within a string
we can use methods .find() .index() .rfind() and also .rindex()
rfind() and rindex() provide last occurence

find() method return a location of the string that we are finding

Slicing
Getting part of a string value 
With slice notation, i add square brackets after the reference to the string and i specify the characters i want. I can indicate both the start position and end position, separated by  a colon.I can also leave out one or the other. Leaving out start means the slice starts at the beginning of the string, and leaving out the end means it goes to the last character

String methods provide your code lots of flexibility to deal with strings that may need some tweaking or massaging before you can put them to their indended use. We can also chain mathods one after the other to do more complex transformations.

















