JAVA-SCRIPT ` is a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles`

it can perform single task at a time .

Single threaded means it has `only one call stack`. Whatever is on the `top of the call stack is run first`. In the above program, functions are run sequentially

it can only interpret line to line which may take long time to find the errors and execute command, so this function is given to asyn which doea the function of inteperiting and compliling,

 powerful programming language that can add `interactivity to a website`, invented by Brendan Eich (co-founder of the Mozilla project, the Mozilla Foundation, and the Mozilla Corporation)

JS is versatile ,compact, yet very flexible. variety of tools on top of the core JavaScript language, unlocking a vast amount of functionality with minimum effort

Third-party frameworks and libraries that you can apply to HTML to accelerate the work of building sites and applications.
### working of JAVA SCRIPT 
       > 1.JS CODE is checked for errors and breaks into small parts by PARSER
       > 2.this parts are arranged in to `abstract syntax tree` 
       > 3. code is delivered to interpreter which executes code in 3 diff ways 
                    a.line by line w/o compilation 
                    b.parses source code imme. to translate 
                    c.executes precompiled code by compiler 
        in V8 engine interpreter outputs code into bytecode 
        >COMPILER converts into machine code /lower language ex BABEL, TYPESCRIPT 
        >PROFILER COMBO OF INTERPRETER AND COMPILER watches the frequently used code and interpretes line by line 
### what javascript can do ? 
JavaScript can  
> change HTML attribute values
>change the style of an HTML element
>can hide and show the html elements
>js file can be inserted in both head and body but at  the end of body tag if applied it gets interpreted fastly
### inserting javascript in html
1. inner html
        To access an HTML element, JavaScript can use the document.`getElementById(id) method`.
        The id attribute defines the HTML element. The innerHTML property defines the HTML content

2.Externally with "src" attribute `<script tag>`
    
3.above or below html 
>https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics

### DIFF bw JS vs ECMA (European Computer Manufacturers Association)
> ECMAScript specification is a `blueprint for creating a scripting language`
>https://wwwfreecodecamporgnewswhats-the-difference-between-javascript-and-ecmascript-cba48c73a2b5/
### JavaScript engine
A program or interpreter that understands and executes JavaScript code.
>JS is a general-purpose `scripting language that conforms to the ECMAScript specification`
>JavaScript implements the ECMAScript specification as described in ECMA-262.  to ensure the `interoperability of web pages across different web browsers`
>`variables` containers `store the values `begins with keyword (`let my variable;`)
Variables are necessary to do anything interesting in programming. If values couldn't change, then you couldn't do anything dynamic, like personalize a greeting message or change an image displayed in an image gallery
to declareany variable `var,let,const` are used , values assigned by the `=` .
### Operators
`operators` allow us to perform tests, do math, join strings together, and other such things.
>`Operators` is a mathematical symbol that produces a result based on two values (or variables).
arthmetic operatoins to compute values 
expression =` { combination of values+variables+operators}` resutls to give values 
 js names / identifiers are used to name variables , keywords and function.
 `js begins with letter (A-Z , a-z) & $ & (_)`


`Array` is a collection of items (in this case strings).
>`ARRAY` structure that allows you to store multiple values in a single reference 


>https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators

>`OBJECT` everything in JavaScript is an object and can be stored in a variable
`object` is a collection of related functionality stored in a single grouping


>`Conditionals`
Conditionals are code structures used to test if an expression returns true or not. A very common form of conditionals is the if ... else statement
here expression in  if (---)is the test

`Functions` Functions are a way of `packaging functionality` that you wish to reuse. 
 `function` is a block of JavaScript code, that can be executed when "called" for.It's possible to define a body of code as a function that executes when you call the function name in your code. This is a good alternative to repeatedly writing the same code. Functions often take `arguments: bits` of data they need to do their job. Arguments go inside the parentheses, separated by commas if there is more than one argument. we `want to run the code`, we type the `name of the function followed by the parentheses`


`concatenation`

`Events` 
Events are the actions by which the user or browser interacts with the HTML Elements. Actions can be anything like clicking a button, pressing keyboard keys, scrolling the page, etc.
in response to which we can run blocks of code. Event listeners observe specific events and call event handlers, which are blocks of code that run in response to an event firing.
#### onclick event 
 onclick event occurs when the user clicks on an HTML Element. We will give the name of the function as a value for the HTML onclick attribute

`Strict - use strict` allows you to place a program, or a function, in a “strict” operating context, use strict’: Strict mode makes several changes to normal JavaScript semantics 
 purpose of "use strict" is to indicate that the code should be executed in "strict mode".
With strict mode, you can not, for example, use undeclared variables.

`LOOP` concept in programming, which allow you to keep running a piece of code over and over again, until a certain condition is met.


In JavaScript, most of the items you `will manipulate` in your code are `objects`.
`Annonymous function ` with no spl names for functions called as an Arrow function.
#### Types of errors 
`syntax error & logic errors`

#### What is a variable?
A variable is a container for a value, like a number we might use in a sum, or a string that we might use as part of a sentence.Variables are `case sensitive`.
> Variables can also contain complex data and even entire functions to do amazing things. 
VARIABLES are like containers to store values
	 for Creating variables we use "let" keyword and values are assigned 
	Ex let message ; 
	Message ='hello world' ( = asssignment operator )
	Console.log(message)
## DOM & EVENT FUNDAMENTALS 
	`Structure Representation` of content in doc created by browser 
	Tree , js can change structure ,style and content .
	DOC OBJECT 
	• Is entry point of DOM 
	• Any HTML is accessed by doc object 1st 
	• getElementById("headingelement")
	• console.log(document.getElementById("headingElement"))
	• To manipulate text within the property we use textContent
### PRIMITIVE TYPES & CONDITIONALS 
	>PRIMITIVE = string, number, bigint, boolean, undefined, symbol, and null.
	>>https://developer.mozilla.org/en-US/docs/Glossary/Primitive#primitive_wrapper_objects_in_javascript

	> Refernce
####	Number
	1. All no are number type 
	2.  to know typeof()   
	 ex console.log(typeof(a));
####	Boolean 
 >true / false based on the conditions

#### String 
        (stream of character only text in single or double/backticks  )
		>String object is used to represent and manipulate a sequence of characters.
		most used 
		>`to check their length , 
		>checking for the existence or location of substrings with the indexOf() method 
		>extracting substrings with the substring() method.


		 

#### Undefined
 value not assigned type is also undefined
 example = Counter application ?
 ### Scope-and its types
>Scope determines the accessibility (visibility) of variables
> types of scopes = block, function,global scope
>ES6 introduced two important new JavaScript keywords: `let and const.` These two keywords provide `Block Scope in JavaScript.`
### why to use let, const instead of var? 
### Hoisting
Variable declarations are one of the most basic aspects of any programming language. One thing that can be dangerous in JavaScript is that variable definitions are hoisted.
Javascript actually rearranges your variable declarations during the browser processing phase and moves them to the top of their functional scope. This means that variables can actually exist before you use them.

>https://medium.com/@LindaVivah/es6-javascript-understanding-let-const-9eba72b22f66#:~:text=Why%20were%20Let%20%26%20Const%20added%3F&text=Variables%20declared%20with%20let%20and,block%2C%20not%20to%20the%20function.

Variables declared inside a { } block cannot be accessed from outside the block
Variables declared with the `var keyword can NOT have block scope.`
Variables declared `inside a { } block can be accessed from outside the block.`
#### local scope
Variables declared within a JavaScript function, become LOCAL to the function &  can only be accessed from within the function.
#### Function scope
JS has function scope: Each function creates a new scope
Variables defined inside a function are not accessible (visible) from outside the function.
Variables `declared with var, let and const` are quite similar when declared inside a function
In most programming languages variables have a block scope → variables created in a code block or inside curly braces {}. They cease to exist outside of them → they are scoped to the block.
BUT `var` in javaScript has function scope → variables live within functions & are scoped to the function. Any variable you create with the `keyword VAR` is local to the function that they were created in. A variable that was created in a parent function lives also in the child function.
>https://medium.com/@ryan.spencer1220/javascript-scope-closure-c3a41c0cf605

