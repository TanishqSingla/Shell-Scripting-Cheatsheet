# Index
- [Hello World](#Hello-World)
- [Comments](#Comments)
- [Variables](#Variables)
- [Reading Variables](#Reading-Variables)

# Hello World
This is the code snippet for 'hello world' in shell

```bash
echo "Hello World"
```
`echo` is a keyword in shell used for printing content as shown in the example.

# Comments
Comments as you know are the most important part of a programmer's life.
In shell a comment can be declared by adding '#' symbol before the content of the comment
Example:
```bash
# this is a comment
echo "Hello World" # this is a comment
```
# Variables
Variable declaration in shell is as follows
```bash
x=1
```
Here 'x' is a variable. Notice there is no space between any of the symbol.
This a note to point while writing shell. While declaring variables there should not be any space between the key and the value assigned to the key.

# Reading Variables
Reading Variable or reading input values can be done by command 'read'
Example:
```bash
read name
```
When running this script, the input given by the user would be stored in variable `name`. The `read` command automatically declare a variable named `name` and initialize it with the value given.

# Accessing Variables
Now that we learned how to declare and read variable, now it's time to use how access the value in the variable.
The value in the variable can be accessed by using `$` symbol before variable name.
```bash
name="Tanishq Singla"
age=18
echo "This cheatsheet is created by $name when he was $age years old"
```
This code would yield output
```
This cheatsheet is created by Tanishq Singla when he was 18 years old
```
In the above example we see initialization of 2 variables `name` and `age`.
If you know high level languages like Python and JavaScript, you must have noticed that the variables are interpolated in the string.
In bash by putting `$` symbol before a valid variable name, in most of the situation it doesn't matter where your vaiable is the you will get the value of the variable there.
I personally find `$` as deferencing operator in this case, but `$` is used far more differently.