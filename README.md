# Lecture_2

# SCOPE 
![Tux, the Linux mascot](/images.png)
## What is SCOPE in JavaScript ?

The scope is the current context of execution in which values and expressions
are "visible" or can be referenced. If a variable or expression is not in the current
scope, it will not be available for use. Scopes can also be layered in a  hierarchy, 
so that child scopes have access to parent scopes, but not vice versa.

![Tux, the Linux mascot](/2.png)

# The 3 types of scope.
## Global scope :
-  The default scope for all code running in script mode.

![Tux, the Linux mascot](/123.jpg)

## Function scope : 
- The scope created with a function.

![Tux, the Linux mascot](/1.jpg)

## Block scope : 
- This scope restricts the variable that is declared.
- Block scope includes air Conditions and Loop

![Tux, the Linux mascot](/1_KxHwVbB0zhnSVrhrWtT-gg.jpg)

# what is Hoisting in JS ?

- Hoisting is a JavaScript mechanism where variables and function 
declarations are moved to the top of their scope before code 
execution.

- Hoisting in JavaScript is a behavior in which a function or a variable 
can be used before declaration.

![Tux, the Linux mascot](/9.webp)


# What is Temporal Dead Zone JS ?
- A variable declared
with let or const
cannot be accessed
until it is declared
within its scope.


# Hoisting – Variable (var)

- There’s a temptation to think that all of the code you see in a 
JavaScript
program is interpreted line-by-line, top-down in order, as the program
execute. While that is essentially true, there’s one part of that as‐
assumption that can lead to incorrect thinking about your program.


![Tux, the Linux mascot](/57.webp)


# Hoisting – function declaration 

- So, one way of thinking, sort of metaphorically, about this process, is that variable and 
function
declarations are “moved” from where they appear in the flow of the code to the top of the 
code. This gives rise to the name hoisting.

![Tux, the Linux mascot](/12345.webp)

- The function foo’s declaration (which in this case includes the implied value of it as an 
actual function) is hoisted, such that the call on the first line is able to execute.


# What is Recursion in JS ?

- Recursion is when a function calls itself until someone stops it. If no one stops it then it'll 
recurse (call itself) forever. Recursive functions let you perform a unit of work multiple times.
Modern programming languages like JavaScript already have the for and while statements as
alternatives to recursive functions. But some languages like Closure do not have any looping
statements, so you need to use recursion to repeatedly execute a piece of code.


![Tux, the Linux mascot](/Screenshot_1.png)

- A recursive function must have a condition to stop calling itself. Otherwise, the 
function is called indefinitely.
Once the condition is met, the function stops calling itself. This is called the base 
condition.
To prevent infinite recursion, you can use if...else statement (or similar approach) 
where one branch makes the recursive call, and the other doesn't.


# What is Closure in JS ?

A closure is the combination of a function bundled together (enclosed) with references to 
its surrounding state (the lexical environment). In other words, a closure gives you 
access to an outer function's scope from an inner function


![Tux, the Linux mascot](/Screenshot_2.png)