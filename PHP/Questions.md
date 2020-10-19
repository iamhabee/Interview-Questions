# Question 1
How to execute a PHP script from the command line?
To execute a PHP script, use the PHP Command Line Interface (CLI) and specify the file name of the script in the following way:

# Answer 
php script.php

# Question 2
Is PHP a case sensitive language?

# Answer
PHP is partially case sensitive. The variable names are case-sensitive but function names are not. If you define the function name in lowercase and call them in uppercase, it will still work. User-defined functions are not case sensitive but the rest of the language is case-sensitive.

# Question 3
What is the meaning of ‘escaping to PHP’?

# Answer
The PHP parsing engine needs a way to differentiate PHP code from other elements in the page. The mechanism for doing so is known as ‘escaping to PHP’. Escaping a string means to reduce ambiguity in quotes used in that string.

# Question 4
What are the characteristics of PHP variables?

# Answer
Some of the important characteristics of PHP variables include:
All variables in PHP are denoted with a leading dollar sign ($).
The value of a variable is the value of its most recent assignment.
Variables are assigned with the = operator, with the variable on the left-hand side and the expression to be evaluated on the right.
Variables can, but do not need, to be declared before assignment.
Variables in PHP do not have intrinsic types – a variable does not know in advance whether it will be used to store a number or a string of characters.
Variables used before they are assigned have default values.

# Question 5
What are the different types of PHP variables?

# Answer
There are 8 data types in PHP which are used to construct the variables:

Integers − are whole numbers, without a decimal point, like 4195.
Doubles − are floating-point numbers, like 3.14159 or 49.1.
Booleans − have only two possible values either true or false.
NULL − is a special type that only has one value: NULL.
Strings − are sequences of characters, like ‘PHP supports string operations.’
Arrays − are named and indexed collections of other values.
Objects − are instances of programmer-defined classes, which can package up both other kinds of values and functions that are specific to the class.
Resources − are special variables that hold references to resources external to PHP.

# Question 6
What are the rules for naming a PHP variable?

# Answer
The following rules are needed to be followed while  naming a PHP variable:
Variable names must begin with a letter or underscore character.
A variable name can consist of numbers, letters, underscores but you cannot use characters like + , – , % , ( , ) . & , etc.

# Question 7
What is the purpose of constant() function?

# Answer
The constant() function will return the value of the constant. This is useful when you want to retrieve value of a constant, but you do not know its name, i.e., it is stored in a variable or returned by a function. For example –

<?php define("MINSIZE", 50); echo MINSIZE; echo constant("MINSIZE"); // same thing as the previous line ?>

# Question 8
What is the purpose of break and continue statement?

# Answer
Break – It terminates the for loop or switch statement and transfers execution to the statement immediately following the for loop or switch.

Continue – It causes the loop to skip the remainder of its body and immediately retest its condition prior to reiterating.

# Question 9
Name some of the popular frameworks in PHP. 
# Answer
Some of the popular frameworks in PHP are:
CakePHP
CodeIgniter
Yii 2
Symfony
Zend Framework

# Question 10
What are the different types of Array in PHP?

# Answer
* Indexed Array – An array with a numeric index is known as the indexed array. Values are stored and accessed in linear fashion.

* Associative Array – An array with strings as index is known as the associative array. This stores element values in association with key values rather than in a strict linear index order.

* Multidimensional Array – An array containing one or more arrays is known as multidimensional array. The values are accessed using multiple indices.
