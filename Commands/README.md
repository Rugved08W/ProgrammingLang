Commands List

Be ; (Beginner Mode)

1. Variable Declaration

box_a = "Apples, Bananas, Cherries"

box_a stores a string separated by commas.

Numbers can be stored without quotes.



2. Printing Values

show 2, box_a

Prints the second value from box_a, in this case, Bananas.

If a number is passed directly, it prints the number itself.



3. Loops

loop x > 0 // show x // x = x - 1

Repeats until x is no longer greater than 0.



4. Conditional Statements

when x = 0 // show "Liftoff!"

Executes when the specified condition is true.



5. Input Command

x = input("Enter your age:")

Takes user input and stores it in variable x.



6. Boolean Operations

Bool_a : x = true

Declares a boolean variable.

true and false are not case-sensitive.



7. Comparisons

when x & y // show "Both are true"
when x | y // show "At least one is true"

& is used for logical AND and | for logical OR.




Pro ; (Advanced Mode)

1. Variable Declaration

str_a : x = "Apples, Bananas, Cherries"

Similar to Be ;, but uses str_a for strings, num_a for numbers, and bool_a for booleans.



2. Printing Values

/execute (2, str_a)

Prints the second value from str_a, which would be Bananas.



3. Input Command

/input x = number("Enter your age:")

Takes user input as a number and stores it in x.



4. Conditional Execution

/execute (x == 5 | x > 10)

Executes based on conditions using ==, >, <, >=, <=.

| for OR and & for AND.



5. Comparisons with Functions

func_a : y = // z = input("age:") // when z >= 18 // print "Eligible to vote" | z < 18 // print "Not eligible to vote"
/execute func_a

Functions can contain multiple commands and condition checks using when.



6. Loops

/loop x > 0 // print x // x = x - 1

/loop simplifies looping commands in Pro ;.



7. Delayed Execution

x = "Somebody once told me"
y = "The world is gonna roll me"
/execute y : x ; 5

Prints y 5 seconds after printing x.