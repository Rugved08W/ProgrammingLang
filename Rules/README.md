Rules for ProgrammingLang

General Rules:

1. Modes:

Be ; is for beginners with simpler syntax.

Pro ; is for experienced coders, allowing complex logic.



2. Semicolon Requirement:

Every code must start with Be ; or Pro ; to define the mode.



3. Variable Declaration:

Variables are declared using x = value.

In Pro ;, func_ is used to define functions.



4. Comments:

Comments are not supported yet, but may be added in the future.



Commands and Syntax:

1. Printing and Displaying Data:

In Be ;, use show x to print values.

In Pro ;, use print x.



2. User Input:

Both modes use input("message") to receive user input.



3. Logical Operators:

Single & for AND.

Single | for OR.



4. Comparisons:

Use when for conditional checks in both modes.

Example: when x == y // show "Equal"



5. Loops:

loop is used for loops in both modes.

In Pro ;, /loop is an alternative for advanced loops.



Mode-Specific Rules:

Be ; Mode:

Variables follow the format x = value.

show is used for printing.

Supports simplified loops and conditional statements using when.

Indexed retrieval using show index, variable_name.

Strings use double quotes " ".

add(), subtract(), and other arithmetic functions are used instead of direct operators.

Example:

Be ;
x = input("Enter a number:")
when x > 0 // show "Positive"
when x = 0 // show "Zero"
when x < 0 // show "Negative"



Pro ; Mode:

Variables follow x = value.

Functions are defined using func_a == // and executed using /execute.

Advanced loops and conditions using /loop.

print is used instead of show.

Supports complex commands with logical operations and multiple comparisons using & and |.

Example:

Pro ;
x = 10
func_a == // while x > 0 // print x // x - 1
/execute func_a



Additional Notes:

Commands separated by // within func_ are executed sequentially.

/execute y : x ; 5 delays the execution of y by 5 seconds.

when supports multiple conditions using & and |.

Errors in Be ; return simple messages like "Error! Invalid syntax." while Pro ; provides detailed error messages.