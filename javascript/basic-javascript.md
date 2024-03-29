# Basic Javascript Exercises

I will compile all of the basic Javascript into this document and give the bigger projects docs of their own. I will provide small explanations along with the working code snippets.

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
### 3.) Storing values with the assignment operator

When you store values in a variable, you use the assignment operator =. Everything to the right of the = is stored in the variable on the left.

```javascript
var myName;
myName = "Fern"; // This stores the string "Fern" in the variable myName
```

#### freecodecamp soloution
```javascript
// Setup
var a;
var b = 2;

// Only change code below this line
a = 7;
b = a; // assigns the contents of a to the variable b
```
### 4.) Initializing variables with the assignment operator

It is common to have to set an initial value for your variable. You would do this on the same line that the variable is declared.

##### freecodecamp solution
```javascript
// Example
var ourVar = 19;

// Only change code below this line
var a = 9; // declares the variable a and sets the initial value to 9
```

### 5.) Understanding unitialized variables

When a JavaScript variable is declared, it is automatically set to the initial value of *undefined*. If you try to do a mathematical operation on an undefined variable you will get *NaN* (not a number). If you concatenate a string with undefined, you will get a literal string of "undefined".

##### freecodecamp soloution
```javascript
// Initialize these three variables
var a = 5; // set to a number 5
var b = 10; // set to a number 10
var c = "I am a"; // set to a string

// Do not change code below this line

a = a + 1;
b = b + 5;
c = c + " String!";

// Output if printed variable 'c' to the console would be "I am a String!"
```

### 6.) Understanding case sensitivity in variables

I previously stated that best practice is camelCase. Variables are case sensitive, meaning if you have a variable called *myVar* and another called *MYVAR* they would be seperate variables.

##### freecodecamp soloution
```javascript
// Declarations
var StUdLyCapVaR;
var properCamelCase;
var TitleCaseOver;

// Assignments
STUDLYCAPVAR = 10;
PRoperCAmelCAse = "A String";
tITLEcASEoVER = 9000;

// Modified (replace current names with these)
studlyCapVar;
properCamelCase;
titleCaseOver;
```

### 7.) Adding two numbers with JavaScript

`Number` is a data type in JavaScript which represents numeric data. To add numbers you just need to use the `+` operator between the two numbers.

##### freecodecamp soloution
```javascript
var sum = 10 + 10; // would output 20
```
### 8.) Subtracting two numbers with JavaScript

 To subtract numbers you just need to use the `-` operator between the two numbers.

##### freecodecamp soloution
```javascript
var difference = 45 - 33; // would output 12
```
### 9.) Multiplying two numbers with JavaScript

 To multiply numbers you just need to use the `*` operator between the two numbers.

##### freecodecamp soloution
```javascript
var product = 8 * 10; // would output 80
```

### 10.) Dividing two numbers with JavaScript

 To divide numbers you just need to use the `/` operator between the two numbers.

##### freecodecamp soloution
```javascript
var quotient = 66 / 33; // would output 2
```

### 11.) Increment a number with JavaScript

You can increment (add one) to a variable with the `++` operator.

```javascript

i++; //Equivalent of below
i = i + 1;
```

##### freecodecamp soloution
```javascript
var myVar = 87;

// Only change code below this line
myVar++; // adds one to myVar making it 88
```
A little more on this:

>
    If used postfix, with operator after operand (for example, x++),
     then it increments and returns the value before incrementing.
    If used prefix, with operator before operand (for example, ++x),
     then it increments and returns the value after incrementing.
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators#Increment_()

### 12.) Decrement a number with JavaScript

You can decrement (take one) to a variable with the `--` operator.

```javascript

i--; //Equivalent of below
i = i - 1;
```

##### freecodecamp soloution

```javascript
var myVar = 11;

// Only change code below this line
myVar--;
```

### 13.) Create decimal numbers with JavaScript

You can store decimals or *floating point* numbers in JavaScript.

##### freecodecamp solution

```javascript
var ourDecimal = 5.7;

// Only change code below this line
var myDecimal = 5.8;
```

### 14.) Multiply two decimals using javascript

##### freecodecamp solution
```javascript
var product = 2.0 * 2.5;
```

### 15.) Divide One Decimal by Another with JavaScript

##### freecodecamp solution
```javascript
var quotient = 4.4 / 2.0; // Fix this line

// output would be 2.2
```
### 16.) Finding a Remainder in JavaScript

In JavaScript you use the %, or *remainder* symbol to find the remainder.

E.G.
```javascript
5 % 2 = 1 because
Math.floor(5 / 2) = 2 (Quotient)
2 * 2 = 4
5 - 4 = 1 (Remainder)
```
##### freecodecamp solution
```javascript
// Only change code below this line

var remainder;
remainder = 11 % 3
```


### 17.) Compound Assignment With Augmented Addition

We use assignments to modify the value of a variable. Because we often need to modify a variable by adding or taking away, there is a common 'compund' symbol for this operation.

```javascript
var myVar = 1;
myVar += 5;
console.log(myVar); // Returns 6
```
##### freecodecamp solution
```javascript
var a = 3;
var b = 17;
var c = 12;

// Only modify code below this line

a += 12;
b += 9;
c += 7;
```

### 18.) Compound Assignment With Augmented Subtraction

The subtraction assignment uses the '-=' notation.

##### freecodecamp solution
```javascript
var a = 11;
var b = 9;
var c = 3;

// Only modify code below this line

a -= 6;
b -= 15;
c -= 1;
```

### 19.) Compound Assignment With Augmented Multiplication

The Multiplication assignment uses the '*=' notation.

##### freecodecamp solution
```javascript
var a = 5;
var b = 12;
var c = 4.6;

// Only modify code below this line

a *= 5;
b *= 3;
c *= 10;

```

### 20.) Compound Assignment With Augmented Division

The division assignment uses the '/=' notation.

##### freecodecamp solution
```javascript
var a = 48;
var b = 108;
var c = 33;

// Only modify code below this line

a /= 12;
b /= 4;
c /= 11;
```

### 21.) Declare String Variables

A string is a series of 0 or more characters wrapped in quotes. Eg. "This is a string."

```javascript
// Example
var firstName = "Alan";
var lastName = "Turing";

// Only change code below this line
var myFirstName = "Fern";
var myLastName = "Ritchie";
```