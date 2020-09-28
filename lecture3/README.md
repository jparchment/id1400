# Python Variables

In this lab you will learn about variables in Python.

## Variables

- A variable is data that can change.
- The type of a variable is determined by Python.
- A variable's value can change when a program is executed.

## Assign a value to a variable

A variable is created the first time it is assigned a value.  

To assign a variable a value, use the =

```
university = "Kean"
```
![Variables1](https://raw.githubusercontent.com/profpy/id1400/master/lecture3/variables1.gif)

Notice, Kean has quotations around it.  This is because it's a string.  More on that later!

{% next %}

## More variables

An assignment statement stores a value in a variable.

```
university = "Kean"
age = 100
money = 19.99
```

![Variables2](https://raw.githubusercontent.com/profpy/id1400/master/lecture3/variables2.gif)

{% next %}

## The value of a variable can change

Assigning a value to an existing variable replaces the previously stored value.

```
university = "Kean"
university = "William Paterson"
```

![Variables3](https://raw.githubusercontent.com/profpy/id1400/master/lecture3/variables3.gif)

{% next %}

# Python Data Types

Variables can store data of different types, and different types can do different things. Python has a number of different data types.

## string

string is a set of characters (letters, numbers, and/or special characters) enclosed by single or double quotation marks.

``` 
university = "Kean"
title = "Professor"
name = "Cheng"
```

![Variables4](https://raw.githubusercontent.com/profpy/id1400/master/lecture3/variables4.gif)

{% next %}

## int

int is a positive or negative whole number.

``` 
month = 9
day = 27
year = 2020
```

![Variables5](https://raw.githubusercontent.com/profpy/id1400/master/lecture3/variables5.gif)

{% next %}

## float

float is a floating point or decimal number.

```
coffee = 1.99
balance = 199.54
tuition = 5002.23
```

![Variables6](https://raw.githubusercontent.com/profpy/id1400/master/lecture3/variables6.gif)

{% next %}

## boolean

a boolean values is either True or False.

```
hot = True
summer = False
```

![Variables7](https://raw.githubusercontent.com/profpy/id1400/master/lecture3/variables7.gif)

{% next %}

## type() function

```
hot = True
type(hot)
```

![Variables8](https://raw.githubusercontent.com/profpy/id1400/master/lecture3/variables8.gif)

{% next %}

# More Output

To join a string, int or float variable with text, you can use a , 

Python adds a space to the output.

```
university = "Kean"
print(university, "University")
```

You can also use + but all data types must be the same.  

This is also known as string concatentation.  With string concatenation, Python does not add a space.

```
university = "Kean"
print(university + " University")
```

