# JavaScript - Warm up

## Learning Objectives
- Why JavaScript programming is amazing
- How to run a JavaScript script
- How to create variables and constants
- What are differences between `var`, `const` and `let`
- What are all the data types available in JavaScript
- How to use the `if`, `if ... else` statements
- How to use comments
- How to affect values to variables
- How to use `while` and `for` loops
- How to use `break` and `continue` statements
- What is a function and how do you use functions
- What does a function that does not use any `return` statement return
- Scope of variables
- What are the arithmetic operators and how to use them
- How to manipulate dictionary
- How to import a file

## Project Requirements
- Allowed editors: `vi`, `vim`, `emacs`
- All your files will be interpreted on Ubuntu 20.04 LTS using `node` (version 14.x)
- All your files should end with a new line
- The first line of all your files should be exactly `#!/usr/bin/node`
- A `README.md` file, at the root of the folder of the project, is mandatory
- Your code should be `semistandard` compliant (version 16.x.x). [Rules of Standard](https://standardjs.com/rules.html) + [semicolons on top](https://github.com/standard/semistandard). Also as reference: [AirBnB style](https://github.com/airbnb/javascript)
- All your files must be executable
- The length of your files will be tested using `wc`
* **Github repository:** `alx-higher_level_programming`
* **Directory:** `0x12-javascript-warm_up`

## More Info
### Install Node 14
```
$ curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
$ sudo apt-get install -y nodejs
```

### Install semi-standard
[Documentation](https://github.com/standard/semistandard)
```
$ sudo npm install semistandard --global
```

## Project Tasks
### 0. First constant, first print
**File:** `0-javascript_is_amazing.js`

Write a script that prints “JavaScript is amazing”:
- You must create a constant variable called `myVar` with the value “JavaScript is amazing”
- You must use `console.log(...)` to print all output
- You are not allowed to use `var`

### 1. 3 languages
**File:** `1-multi_languages.js`

Write a script that prints 3 lines:
- The first line: “C is fun”
- The second line: “Python is cool”
- The third line: “JavaScript is amazing”
- You must use `console.log(...)` to print all output
- You are not allowed to use `var`

### 2. Arguments
**File:** `2-arguments.js`

Write a script that prints a message depending of the number of arguments passed:
- If no arguments are passed to the script, print “No argument”
- If only one argument is passed to the script, print “Argument found”
- Otherwise, print “Arguments found”
- You must use `console.log(...)` to print all output
- You are not allowed to use `var`

Reference: [process.argv](https://nodejs.org/api/process.html#process_process_argv)

### 3. Value of my argument
**File:** `3-value_argument.js`

Write a script that prints the first argument passed to it:
- If no arguments are passed to the script, print “No argument”
- You must use `console.log(...)` to print all output
- You are not allowed to use `var`
- You are not allowed to use `length`

### 4. Create a sentence
**File:** `4-concat.js`

Write a script that prints two arguments passed to it, in the following format: “ is ”
- You must use `console.log(...)` to print all output
- You are not allowed to use `var`

### 5. An Integer
**File:** `5-to_integer.js`

Write a script that prints `My number: <first argument converted in integer>` if the first argument can be converted to an integer:
- If the argument can’t be converted to an integer, print “Not a number”
- You must use `console.log(...)` to print all output
- You are not allowed to use `var`
- You are not allowed to use `try/catch`

### 6. Loop to languages
**File:** `6-multi_languages_loop.js`

Write a script that prints 3 lines: (like `1-multi_languages.js`) but by using an array of string and a loop
- The first line: “C is fun”
- The second line: “Python is cool”
- The third line: “JavaScript is amazing”
- You must use `console.log(...)` to print all output
- You are not allowed to use `var`
- You are not allowed to use any `if/else` statement
- You can use only one `console.log`
- You must use a loop (`while`, `for`, etc.)

### 7. I love C
**File:** `7-multi_c.js`

Write a script that prints `x` times “C is fun”
- Where `x` is the first argument of the script
- If the first argument can’t be converted to an integer, print “Missing number of occurrences”
- You must use `console.log(...)` to print all output
- You are not allowed to use `var`
- You can use only one `console.log`
- You must use a loop (`while`, `for`, etc.)

### 8. Square
**File:** `8-square.js`
