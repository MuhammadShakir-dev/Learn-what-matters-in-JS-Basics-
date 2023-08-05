# Learn-what-matters-in-JS-Basics-
If you are a beginner and want to learn JavaScript Basics then here you will find the best notes.

# Basic JavaScript Notes.

# Keyword Vs Words.

1. Anything which has some meaning in JavaScript is called Keywords.
2. Anything which doesn’t have any meaning in JavaScript is called Words.

### E.g. Keyword and Word.

1. is = word 
2. myName = word
3. myAge  = word
4. student = word
5. and  = word
6. this = keyword
7. if = keyword
8. else if = keyword
9. else = keyword
10. for = keyword
11. each = keyword
12. while = keyword
13. switch = keyword
14. break = keyword

# What are variables and constants?

1. If you want to store some data in your code you will need variables that store your data.

### E.g Variables.

The variable is something that changes.

```jsx
var myAge  = 21;
```

```jsx
myAge = 22;
```

### E.g Constants.

The constant is something that doesn’t change its value.

const myName = “Muhammad Shakir”;

if you re-update this value you will get an error.

# Undefined vs Not defined.

1. Anything which has some existence but you are not sure of their value is called undefined.
2. Anything which doesn’t exist is called not-defined    

### E.g Undefined and Not-defined

# Hoisting in JavaScript.

Variables and functions are hoisted which means their declaration is moved on the top of your code.

### For e.g

```jsx
console.log(a); // undefined
```

```jsx
var a  = 12; 
```

```jsx
console.log(b) // not-defined
```

```jsx
var a = 12;
```

java-script breaks this code into two parts.

var a; this part moves at the top of your code and this is called hoisting and due to this their value is undefined.

a - 12 ; 

# Types in JavaScript.

There are two types of JavaScript.

1. Primitive.
2. Reference.  

## Primitives.

1. Numbers
2. BOOLEAN
3. null
4. Undefined
5. String

## References.

1. []
2. ()
3. {}

## Explanation.

1. Asi koi bhi value jisko copy karny par real copy nahi hota hai balki us mein value ka reference pass hota hai use hum reference value reference value  kehty hein.
2. Asi values jisko copy karne par real copy ho jaaye wo value primitive type hoti hai.

### E.g

```jsx
// primitive type

var a = 12;
var b = a;
console.log(a); // 12

b = 12+1; // b = 13;

console.log(b); // 13
console.log(a); // 12
```

```jsx
// reference type

var c = [1,2,3,5];
var d = c; // [1,2,3,5]

d.pop();

console.log(d); // [1,2,3];
console.log(c); // [1,2,3];  
```

# Loops.

Loop means repeat. 

There are different types of loops in JavaScript but in the basics we cover only for and while.

1. for
2. while

## for - loop.

for consists of three parts

```jsx
// eg

for(starting pint ; end point;  what to change){

// on change what to print?

}

for(let i = 0; i <= 10; i++){
	console.log(i);
};

// print 25 to 50 using for loop.

for(let i = 25; i <= 50; i++){
	console.log(i);
}
```

## While - loop.

while loop also consists of three parts or you can say there are three thing that need to runs a while loop.

```jsx
// eg 

starting point

while(condition that must false in future){
	what to change ?
}

let a = 0;

while(a < 20){
	console.log(a);
	a++;
}

```

# Functions in JavaScript.

**Function are nothing but you write some code and then named that block of code. And then reuse that code when needed with that name as many time as you want.**

 

**Functions are mainly used for three things.**

1. If you don’t want to run your code instantly, but want to run your code in future.   
2. If you want to reuse your code.
3. If your want to run your code. But with different data.  

## Function styling.

There are six ways to style function in JavaScript.

Three are in ES-5.

Three are in ES-6.   

```jsx
// pint 1 and 2 examples.

function count(){
	for(let i = 0; i <= 20; i++) {
			console.log(i);
	};
};

count();

// point 3 example.

// Function with arguments and parameters.

function stdName(s){ // this s here which is variable and holds the value of the argument that you have passed below-called parameter.  
 	console.log(s);
};

stdName("Muhammad Shakir") // this string inside of a function is called an argument. 
```

## Arguments.

The argument in the function is nothing but real value that you have passed every time you call the function.

## Parameters.

The variable that stores the value of arguments is called parameters.   

# Arrays in JavaScript.

The array is a type of Data structure that stores multiple values of multiple data-types. You can also call it a group of values. Array uses index numbers to store value and the index number starts from 0 for the 1 element and so on. The index is called the counting of the array.

```jsx
// eg

let stdInfo = ["Muhammad Shakir", 21, "Grade-A"]; // array []
console.log(stdInfo); 

// i want to print the grade of that student.
console.log(stdInfo[2]);

// 0 = Muhammad Shakir;
// 1 = 21;
// 2 = Grade - A;
```

# Objects in JavaScript.

Let’s understand it with an example.

1. **If you want to store multiple data of multiple persons let’s say names of different persons then here you can use array.**
2. **But if you want to store multiple data of a single person in a key-value pair then here you can use Objects.**    

## Types of Objects.

1. Blank Objects.
2. Filled Objects.

```jsx
// eg of Blank Object

let b = {} //This is called a blank object in JavaScript. 

// eg of filled Object.  

let classCrInfo = {
		
	name : "Muhammad Shakir",
	age = 22,
	class = "BS-7A",
	grade = "A+" 
	
};

console.log(classCrInfo);

//In the filled object name is called a Property which stores a value called "Muhammad Shakir " Now if you want to print the Muhammad Shakir you have to write.

console.log(classCrInfor.name) // and the name which holds the value simply prints Muhammad Shakir.
```

## What is the method?

A property that has a value of function is called a method.

```jsx
// eg    

let a = {
	
		sayHi : function() {
			   console.log("Hello World")
    } 
	
}
```

## Updating Object Properties.
```jsx
// eg

let stdInfo = ["Muhammad Shakir", 21, "Grade-A"]; // array []
console.log(stdInfo); 

// i want to print the grade of that student.
console.log(stdInfo[2]);

// 0 = Muhammad Shakir;
// 1 = 21;
// 2 = Grade - A;
```

