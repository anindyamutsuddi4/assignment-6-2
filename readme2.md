#### 1) What is the difference between var, let, and const?
-Reassigning var and let is possible but reassigning const is not accepted in JS.
-Var is function scoped,means the variable which is declared as var can be accessed outside of the block but let and const are block scoped that means the variables that are declared as let and const can not be accessed outside of the block

#### 2) What is the difference between map(), forEach(), and filter()? 
-Map() loops through every element of an array,do any kind of operation and also return an array.
-forach() loops through every element of an array or object.
-filter() loops through an array and returns a new array of the elements which match the given condition

#### 3) What are arrow functions in ES6?
-arrow function is a shorter way of declaring a function introduced in ES6. It can be used with array methods like map,find,filters etc.

#### 4) How does destructuring assignment work in ES6?
-Destructuring assignment work by assigning elements of array,object or functions to a variable,for example
//array destructuring=
let arr=[1,2,3]
let [a,b,c]=arr;
Console.log(a,b,c)//1,2,3

#### 5) Explain template literals in ES6. How are they different from string concatenation?
-Template literals give the access of passing any value of variables or expressions directly in a string. Here expressions are declared inside backticks(``) sign 
-In string concatenations + or \n sign is used for declaring multiline expression,but template literal can directly write on multiple lines.