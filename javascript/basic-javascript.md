# Basic Javascript Exercises

I will compile all of the basic Javascript into this document and give the bigger projects docs of their own.

### 1.) Comment your JavaScript code

This is pretty self explanitory. There are two ways of creating comments in JavaScript. You can create a 
single line comment or a multi-line comment. You can create single line comments in-line with your JavaScript
code.

```javascript
var exampleCode; // This is an inline comment

/* This is a multiline comment that could be used to
describe things in more detail*/
```

### 2.) Declaring variables

Declaring variables allows the computer to store and use data. When you declare a variable, you are creating 
a sort of 'label' which then can be used to store data.

Data in JavaScript could be any of these data types: undefined, null, boolean, string, symbol, number, and object.

To declare a variable in JavaScript we must use the *var* keyword.

```javascript
var myFirstVariable; //This declares that there is a variable named myFirstVariable
myFirstVariable = 5; //This then stores the number '5' in myFirstVariable
```
Variables may not contain spaces, start with a number or be named any of JavaScripts inbuilt key words,
such as *var*. Also it is best practice to name variables using camelCase, which is where the first word starts
with a lowercase letter and all subsequent words start with a capital letter. Eg. thisIsAnExampleOfCamelCase.

#### freecodecamp soloution
```javascript
// Example
var ourName;

// Declare myName below this line
var myName;
```
