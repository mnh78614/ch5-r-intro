# Intro to R
## Jan 11th, 2018

- You can run R on the command line, _**not as efficient**_

- **Script**: A list of instructions (in order for the computer to **execute**; a "script" that our computer should follow.

## Using R Studio

- Type your script into the **Script pane**
  - Press <kbd>cmd + enter</kbd>
  - Code will execute

## R Syntax

- Comments are created by pressing the <kbd>#</kbd> button
- "print" command in R will print out text
- Example:
 ```
 print("Hello world")
 ```
 Will print: Hello world

- You need to add the <kbd>() and ""</kbd> to be able to print successfully
  - If you don't add these in your code you will get an error message, these are known as _**bugs**_ in code.

## Bugs in Programming
- Syntax Error
  - An error in the use of the R language. A problem with how you said something.
  - Interpreter will error at the site of the problem.

- Logical Error
  - An error in the algorithm you used. A problem with what you said
  - Interpreter will error, but possibly __**after**__ the problem.

- Semantic error
  - An error in your approach to solve a problem.
  - Interpreter will not error, but will not do what you want.

## Variables

- Variables: A label that refers to a **value** (data)
- Example:
```
my.num <- 201
```
- my.num is the variable, 201 is the value.
- Once we have a variable, we can use that label to **refer** to a value
  - When a label is on the _**left**_, it means the _**variable**_
  - When a label is on the  _**right**_, it means the _**value**_

## Data Types
- **Numeric Data**: Used to store numbers (whole or decimal). Default computational data type.
  - Example:
  ```
  x <- 3
  y <- 1
  z <- x + y
  ```
- **Character Data**: Used to store _**strings**_ of characters. Written in single or double quotes.
  - Example:
  ```
  my.name <- "Muhammad"
  ```
- **Logical (Boolean Data)**: Used to store "yes or no" data: TRUE or FALSE
  - Example:
  ```
  is.lunch.time <- TRUE # Not the string "TRUE"
  is.monday <- FALSE
  ```
- We can apply boolean values to **logical data** like & (and), | (or), ! (not)

## Functions
- **Function**: A named sequence of instructions (lines of code). We **call** a function to do those steps.

```
paste function: paste("Hello", "World") # Will print Hello world

round function: round(5/7) # Will round to nearest .01
```

- May **return** a value (the "output"). This value must be _stored in a variable_ for the machine to use later.
