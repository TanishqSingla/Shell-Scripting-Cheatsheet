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
When running this script, the input given by the user would be stored in variable `name`. The `read` command automatically declare a variable named `name` and initialize it with the value give