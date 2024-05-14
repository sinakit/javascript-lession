# Javascript-lession
## Javascript code for server side!!
- [X ] what is Js?
JS or JavaScript is a programming language that is primarily used for web development. It is a versatile language that allows developers to add dynamic and interactive elements to websites. JavaScript can be used for tasks such as validating form inputs, creating interactive content, handling events, making HTTP requests, and manipulating HTML elements on web pages. It is supported by all major web browsers and can be used on both the client-side (in the browser) and the server-side (with the help of server-side frameworks like Node.js). JavaScript is known for its flexibility and wide range of libraries and frameworks that make web development more efficient and powerful.
- [ X] Js convention
Snake case:
Snake case Separates each word with an underscore (_).
Kebab Case:
In case we want to write a name, we have to put underscore. But if we can not put, but our work does not look pretty.
The difference between snake case and kebab case is that kebab case separates each word with a dash character, -, instead of an underscore.
Camel Case:
When using the camel case, you start by creating the first lowercase letter. You then capitalize the first letter of each word below.
 Pascal Case:
 The only difference between the two words is that the pascal case requires that the first letter of the first word be capitalized as well.

- [X ] Javascript statement
let x, y, z;    // Statement 1
x = 5;          // Statement 2
y = 6;          // Statement 3
z = x + y;      // Statement 4




- [ X] How to use variable? Declare and Use
Declaration:
To declare a variable, you use the var, let, or const keyword, followed by the variable name.
var: This keyword was traditionally used to declare variables in JavaScript. It has function scope or global scope, depending on where it is declared.
var myVariable;
let: Introduced in ECMAScript 6 (ES6), let allows you to declare block-scoped variables. Block scope means that the variable is limited to the block ({}) where it is declared or any nested blocks.
let myVariable;
const: Also introduced in ES6, const is used to declare variables that are constants. The value assigned to a const variable cannot be changed once it is assigned. const also has block scope.
const myVariable;
const: Also introduced in ES6, const is used to declare variables that are constants. The value assigned to a const variable cannot be changed once it is assigned. const also has block scope.
const myVariable;


- [ ] Js comment, single line and multiple line
- [ x] Js datatype, how to use `var`, `let` and `const`
type of Variable
var  is an old school variable declaration
let is a modern variable declaration
const is like let,but the variable of the variable cannot be changed.
- [x ] Js operator
Operators are used to perform different types of mathematical and logical calculations.
  - [ x] Arithmatic operator
  Arithmetic Operator is about simple algebraic methods such as addition, subtraction, multiplication, division.
  - [ x] Assignment operator
  <!DOCTYPE html>
<html>
<body>

<h1>JavaScript Operators</h1>
<h2>The Assignment (=) Operator</h2>

<p id="demo"></p>

<script>

let x = 5;

let y = 2;

let z = x + y;

document.getElementById("demo").innerHTML = "The sum of x + y is: " + z;
</script>

</body>
</html>


  - [ x] Comparison operator
  Comparative Operator is the operator used for comparison.
  - [ ] String operator

  
  - [ x] Logical operator
  The logical operator is a link for a technique that has a value but is only true and false. .
  - [ x] Bitwise operator
  JavaScript Bitwise Operators
Operator	Name	Description
&	AND	Sets each bit to 1 if both bits are 1
|	OR	Sets each bit to 1 if one of two bits is 1
^	XOR	Sets each bit to 1 if only one of two bits is 1
~	NOT	Inverts all the bits
<<	Zero fill left shift	Shifts left by pushing zeros in from the right and let the leftmost bits fall off
>>	Signed right shift	Shifts right by pushing copies of the leftmost bit in from the left, and let the rightmost bits fall off
>>>	Zero fill right shift	Shifts right by pushing zeros in from the left, and let the rightmost bits fall off
  - [X ] Ternery operatot
  Ternary Operator
The ternary operator is a simplified conditional operator like if / else.

Syntax: condition ? <expression if true> : <expression if false>

Here is an example using if / else:
if (authenticated) {
  renderApp();
} else {
  renderLogin();
}
- [X ] Count 8 data types in js?
JavaScript has 8 Datatypes
1. String
2. Number
3. Bigint
4. Boolean
5. Undefined
6. Null
7. Symbol
8. Object


- [x ] Count 3 type Object data type
The object data type can contain:

1. An object
2. An array
3. A date
- [ X] Js function
A JavaScript function is a block of code designed to perform a particular task.

A JavaScript function is executed when "something" invokes it (calls it).
  - [ ] Legacy function
  - [ x] Arrow function
  Arrow functions were introduced in ES6.

Arrow functions allow us to write shorter function syntax:

let myFunction = (a, b) => a * b;


  - [X ] How to involk above 2 functions
  Invoking a JavaScript Function
The code inside a function is not executed when the function is defined.

The code inside a function is executed when the function is invoked.

It is common to use the term "call a function" instead of "invoke a function".

It is also common to say "call upon a function", "start a function", or "execute a function".

In this tutorial, we will use invoke, because a JavaScript function can be invoked without being called.


- [X ] Js object
Real Life Objects, Properties, and Methods
In real life, a car is an object.


- [ X] Js Event (Applied on frontend)
An HTML event can be something the browser does, or something a user does.

Here are some examples of HTML events:

An HTML web page has finished loading
An HTML input field was changed
An HTML button was clicked
Often, when events happen, you may want to do something.

JavaScript lets you execute code when events are detected.

HTML allows event handler attributes, with JavaScript code, to be added to HTML elements.

With single quotes:
- [ X] Js String
JavaScript provides a built-in object called String that represents a sequence of characters. You can create a string by enclosing text in single quotes (') or double quotes ("). For example:

let str1 = 'Hello, world!';
let str2 = "JavaScript is awesome!";
let str3 = new String('This is a string');
let str1 = 'Hello,';
let str2 = ' world!';
let result = str1 + str2; // Using the + operator
console.log(result); // Output: Hello, world!

let str3 = str1.concat(str2); // Using the concat() method
console.log(str3); // Output: Hello, world!
  - [X ] String Method
  JavaScript provides a variety of methods that you can use to manipulate and work with strings. Here are some commonly used methods:
  let str = 'Hello, world!';
console.log(str.length); // Output: 13
let str1 = 'Hello,';
let str2 = ' world!';
let result = str1.concat(str2);
console.log(result); // Output: Hello, world!
  - [X ] String search
  In JavaScript, you can use the search() method to search for a specified substring within a string. The search() method returns the index of the first occurrence of the substring, or -1 if the substring is not found.
  let str = 'Hello, world!';
let index = str.search('world');
console.log(index); // Output: 7
  - [ X] String template
  In JavaScript, you can use string templates, also known as template literals, to create strings that allow for easy embedding of expressions or variables. String templates are enclosed in backticks ( ) instead of single or double quotes.

Here's an example of using string templates:
let name = 'Alice';
let age = 30;

let message = `Hello, my name is ${name} and I am ${age} years old.`;
console.log(message); // Output: Hello, my name is Alice and I am 30 years old.
- [X ] Js number
  - [ ] Number method
  - [ ] Number properties
- [ ] Js Array
  - [ ] Array Methods
  - [ ] Array search
  - [ ] Array sort
- [ ] Js Date
- [ ] Js Math and its methods
- [ ] Js boolean
- [ ] Js comparision
      - check and understand what different between `==` and `===`
- [ ] Js Contol flow
  - [ ] For loop
  - [ ] For in
  - [ ] For of
  - [ ] While
  - [ ] Do While
  - [ ] Break
  - [ ] Iterables loop
- [ ] Set method
- [ ] Map Method
- [ ] Js `typeof`
  - [ ] Contain value `String`, `Number`, `Boolean`, `Object`, `Function`
  - [ ] Contain no value `null` and `undefined`
  - [ ] Type of objects `Object`, `Date`, `Array`, `String`, `Number`, `Boolean`
- [ ] Js conversion
  - [ ] convert string to number'
  - [ ] convert number to string
  - [ ] convert date to number
  - [ ] convert number to date
  - [ ] convert boolean to number
  - [ ] convert number to boolean
- [ ] Regular expression
- [ ] Js Errors
  - [ ] Try ... Catch ... Final
  - [ ] Throw
- [ ] Js Scope
  - [ ] Global
  - [ ] Local (Block and Function)
- [ ] Js keyword `this`
- [ ] Js class
- [ ] Js JSON
- [ ] Js history
- [ ] Js promise
- [ ] Js async/await
