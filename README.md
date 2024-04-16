# Introduction-To-JavaScript
# DAY 1-5
What is Javascript?
-JavaScript is one of the most popular and widely used programming language in the world ,it is also one of the three pilars of the web of whic the other two are CSS and HTML .
-JavaScript was purposely designed to intergrate into HTML.
JavaScript Arithmetic Operators
Arithmetic operators are used to perform artimetic on numbers (literals or variables), a typical arithmetic operation operates on two numbers .
Operates and operands
the numbers (in an arthmetc operation) are called operands and te operation (to be performed between the two operands) is defined by an operator
What does JavaScript do?
-It programs around the web 
-Creates interactivity (allows things that were previously in the early days of the web generally static)
JavaScipt Variables
-We define variables with the keword> var
-Variables are containers for storing dta which can be declared in 4 ways
1. Automatically
2. Using var
3. Using let
4. Using const
-Var was used or elemented in 1995 -2015, let and const were added in 2015 however var should only be used in code written for older browser.
Increment(++)
-The increment operator adds one to its operand and returns a value.
Syntax
-Operator: x++ or ++x
Decrement(--)
-The decrement operator subtracts one from its operand and returns a vales
-Variables hold values
example using let               example using const                   mixed example
let x= 5;                        const x= 5;                          const 5;
let y=6;                         const y= 6;                          const 6;
let z=x+y;                       const z= x+y                          let total= price1 + price2
-variables price 1 and price 2 are declared with the const keyword ,these constant values cannot be changed
Syntax
-Operator: x-- or --x
One of the most fundamental characteristics of a programming language is the set of data types it supports , these are the types of values that can be represented and manipulated in a programming language .
JavaScript Comments
-can be used to explain Javascript code and to make it more readable ,JavaScript comments can also be used to prevent excecution when testing alternative code.
Single Line Comments
-single line comments start with // and any text between // and the end of the line with be ignored by JavaScript it will not be executed
Multi Line Comments
-start with /* and end with*/ and any text between /* and */ will be ignored by javascript
JavaScript allows you to work with three primitive data types which are -
   -Number e.g 123, 120.50 etc
   -Strings of text e.g "This text string " etc
   -Boolean e.g true or false
   JavaScript also defines two trival data types null and undefined each of which defines only a single value ,in addition to these primitve data types, JavaScript supports a composite data type known as a object.
   * Use the var keyword only for declaration or initialization once for the life of any variable name in a document ,you should not re-declare the same variable twice.
  JavaScrpt is an untyped language ,this means that a variable can hold a value of any data type unlike many other languages you dont have to tell JavaScript during a variable declaration what type of value the variable will hold ,the value tpe of a variable can chnage during the execution of a program and JavaScript takes care of it automatically.
JavaScript Identifers
-All JavaScript variables must be identified with unique names , and these unique names are called identifers these can also be short names like x and y or even more descriptive names like age ,sum or total volume
General rules for constructing names for variables (unique identifers) are:
-names can contai letters ,digits , underscores ,and dollar signs
-names must begin with a letter
-names can also begin with - and $
-reserved words cannot be used as names
*identifers are case-sensitive
JavaScript Assignment
The Addition Assignment Operator +
-In JavaScript the equal sign(=) is an "assignment" operator
x= x+5
-it assigns the value of x + 5  to x
-it calculates the value of x+5 and puts the result into x ,the value of x is incremented by 5
-Adds value to a variable
The Subtration Assignment Operator -
-subtracts value from a variable
let x = 10;
x -= 5;
The Multiple Assignment Operator *
-multiple a variable
The Exponentation Operator **
-raises a variable to the power of the operand
Data Types(JavaScript)
-JavaScript has eight datatypes
*string-A string (or a text string) is a series of characters like "John Doe".
* number- All JavaScript numbers are stored as decimal numbers (floating point).
* bignit-All JavaScript numbers are stored in a a 64-bit floating-point format
* undefined-In JavaScript, a variable without a value, has the value undefined. The type is also undefined.
* boolean-Booleans can only have two values: true or false.
* null-
* symbol-
* object -JavaScript objects are written with curly braces {}.
-JavaScript variables can hold numbers like 100 and text values like like "John Doe"
-In programming ,text values are called text strings , strings are written inside double or single quotes and numbers are written without quotes , if you written in quotes it will be treated as a text string .
Declaring a JavaScript Variable
-creating a variable in JavaScript is called "declaring" a variable , you can declare a variable with var or let .
-after declaration the variable has no value (technically it is undefined) , to assign a vaue to the variable use the equal sign.
-you can declare many variables in one statement start the statement with let and separate the variables by comma, a declaration can span multiple lines.
Value= Undefined
-In computer programmes variables are often declared without a value ,the value can be something that has to be calculated or something that will be provided later like user input
-A variable declared without a value will have the value undefined
RE-declaring JavaScript Variables
- If you re-daclare a JavaScript  variable declared with var it will not lose its value
The Object Datatype
the object data type can contain
1. An object
2. An array
3. A date

JavaScript Basics
JavaScript has eight Datatypes of which on this day we speak about two of them which are ;
STRINGS AND ARRAYS
# Strings
Strings are for storing text, and are written in quotes .
A JavaScript string is zero or more characters written inside quotes -you can use single or double quotes .
JavaScript strings are primitive and immutable ,all string methods produces a new string without altering the orginal string.
# Arrays
JavaScript arrays are written with square brackets ,arrays are items that are separated by commas
Arrays are a special type of objects. The typeof operator in JavaScript returns "object" for arrays.
But, JavaScript arrays are best described as arrays.
Arrays use numbers to access its "elements".Objects use names to access its "members"

Functions
A function is a group of reuseable code which can be called anywhere in your program . This eliminates the need of writing the same code again and again ,it helps programmes in writing modular codes.
Functions allow a programmer to divide a big program into a number of small and manageable functions ,like any other advanced programming language JavaScript also supports all the features necessary to write modular code using functions .
You must have seen fuctions like alert() and write () in the earlier chapters, we were using these functions again and again, but they had been written in core JavaScript only once.
JavaScript allows us to write our own functions as well ,this section explains how to write your own functions in JavaScript .
Function Definition
Before we use a function ,we need to define it and the most common way to define a function in JavaScript is by using the function keyword followed by a unique function name a list of parameters (that might be empty) and a statement block surrounded by curly braces.
Syntax
The basic syntax is shown here 
<script type="text/javascript">
   <!---
      function functionname(parameter-list){
         statements
      }
   //--->
   Example
   try the folowing example as it defines a function called sayHello that takes no parametrs-
      <script type="text/javascript">
      <!--
      function sayHello.(){
         alert("Hello there");
      }
   //-->
      </script>
      
Booleans
-Booleans are values that can only be one of two things :true or false
-Anything on or off ,yes or no or temporary is usually good fit for a boolean ,however it is useful to store booleans in variables to keep track of their values and change them over time
example:
var kitchenLights=false;
kitchenLights=true;
kitchenLights;
Output:
true
Comparing two JavaScript objects always return false.
The Boolean() Function
You can use the Boolean() function to find out if an expression (or a variable) is true:
Boolean(10 > 9)
The Boolean value of an expression is the basis for all JavaScript comparisons and conditions.
Operator	Description	Example
==	        equal to	                 if (day == "Monday")
>	             greater than	                 if (salary > 9000)
<	              less than	                             if (age < 18)
Everything With a "Value" is True , however everything without a "Value" is False
Normally JavaScript Booleans are primitive values created from literals:
let x = false;
But Booleans can also be defined as objects with the keyword new:
let y = new Boolean(false);
 # Week 2 Day1-5
 Type Conversions
 -Most of the time,operators and functions automatically convert the values given to them to the righ type for example,alert automatically converts any value to a string to show it.
 -Mathematical operations convet values to numbers,there are also cases when we need to explicity convert a value to the expected type.
 String Conversion
 String conversion happens when we need the string form of a value  for example ,alert (value) does it to show the value ,we can also call the string(value) function to convert a value to a string .
 String conversion is mostly obvious ,a false becomes "null" etc.
 Numeric Conversion
 Numeric conversion happens in mathematical functions and expressions automatically for example ,when division / is applied to non-numbers:
 alert("6"/"2"); //3  ,strings are converted to numbers  ,we can use the Number (value) function to explicitly convert a vale to a number 
 let str="123";
 alert(typeOfStr);//string
 let num=Number(str);//becomes a number123
 alert(typeOfnum);//number
 Explicit conversion is usually required when we read a value from a string-based source like a text form but expect a number to be entered,if the string is not a valid number the result of such a conversion is NaN.For instance:
 letage=Number("an arbitary string instead of a number");
 alert(age);//NaN ,conversion failed.
 Numeric conversion rules:
 VALUE
 -undefined-becames NaN
 -null-becames 0
 -true and false-becomes 1 and 0
 -string-becomes whitespaces from the start and end are removed,if the remaining string is empty the result is 0, otherwise the number is "read" from the string  , an error gives NaN.
 Examples:
 alert(Number("123"));//123 string.An eeror gives NaN.
 alert(number(123z));//NaN (error reading a number at "Z")
 alert(Number(false));//0
 Please note that null and undefined behave differently here; null becomes zero while undefined becomes NaN.
 Most mathematical operators also perform such conversion , we`ll see that in the next chapter .
 Boolean Conversion
 Boolean conversion is the simplest one , it happens in logical operations but can also be performed explicitly with a call to boolean(value)
 The conversion rule:
 -Values that are intuitively "empty" , like 0 , an empty string ,null , undefined and NaN becomes false, other values become true .
 Formatting Numbers 
 JavaScript Number format: Main tips
 -several JavaScript number format methods are offered with this language that you can use to manipulate new values instead of changing the one being used for the method.
 -every javascript number format method may be used on any type of number, including literals , variables , expressions.
 Methods used for numbers
 There are a few JavaScript number format methods to keep in mind if you want to manipulate and change numeric values , these are the go-to methods while working with numeric values.
 However , some JavaScript number format methods are specifically used on numbers only  .
 toExponential()
 -toExponential () turns numbers into strings as well , but in addition to that , the number that is returned is also rounded and written with exponential notation , you can also have access to a parameter , which is used to define the nmber of digits after a decimal point .
 -The JavaScript to fixed() also turns the number into a string , but with a specific amount of decimals this time ,the number of decimals should be specified in the parentheses after the methods name.
 toPrecision
 -the toPrecision () also turns the number into a string , but with a specified inside the parenthese after the methods name, it is quite similar to JavaScript to fixed() method but counts all numbers not only decimals .
 Converting variables to Numbers
 -if you find yourself in need to turn a variable into a number ,these are the three methods you can use ;
 Number()
 Parselnt()
 Parsefloat()
 Note:these are global JavaScript methods , not number methods , therefore tey can be used eveywhere not only in numeric values.
 Number()
 Number() method is widely used to convert JavaScrpt variables into numbers , although if a number cannot be returned , the program will return NaN (Not a Number)
 If you want to create a JavaScript integer you should use parselnt()  , it works bu parsing a string and then returning the number .
 Spaces may be present in the string but only the first number will be returned.
 JavaScript Number format:Summary
 -JavaScript number format can be changed through various methods into multiple different values .
 -Most popular methods are Number() ,parselnt() , an parseFloat().
 -If you want JavaScript to convert to integer, you should use parselnt() method.
 -Each time JavaScript converts to integer, it returns a new value instead of rewriting.
 # The Document Object Model
 The Document Object Model is an Application programming interface(API) for HTML and XML documents ,it does two things for web developers
 -Provides a structural representation of the document.
 -Defines the way that the structure is to be accessed from script.
 This allows you to get at the web page as a group of nodes,essentially it connects web pages to scripts or programming languages,the JavaScript syntax has to do with objects to access an object ,property, or method its refernce must include every object that contain it separated by a dot its called the "dot. syntax"
 Lets difine the terms introduced above.
 # OBJECT
 -A JavaScript object is any scriptable HTML element that may be accessed through the JavaScript language,although the browser window is not an HTML element it too is a scriptable object ,outside the context of a web page are core objects these objects are not associated with HTML elements but with the language itself.
 -Then there are the homemade objects are both associated with the JavaScript object model.
 The following are some of the JavaScript objects :
 *window
 *document
 *form
 *image
 # PROPERTY
 - Objects have properties which you can think of as characteristics of an object, a JavaScript property has a similar relationship to the object it belongs to that an HTML tag attribute has to the tag that contains it e.g. , the JavaScript "value" property is to a text field object as the HTML "width" attribute is to a table tag.
 - There is one major exception :JavaScript properties can also be be objects ,in that case the object-property relationship is more like the relationship an<option> tag has to the <select> tag that contains it but in JavaScript there is no difference in how you refer to a plain old property and a property that is also an object.
  -A document , although contained by te window and therefore a property of the window object is also considered an object,the same is true for a form and an image-they are properties of the document object but also objects themselves.
   -The rule for the dual identities is this: a property is also an object if that-property has its own properties and methods ,its best to think of objects that way its clear what you may and may not do with them.
   # Method
   -Methods are actions that can be applied directly to objects within a web page methods cause a boring old HTML document to react to the end user, this results in a a meaningful experience for the end user which would otherwise be completely one-sided.
   # Method Parameters
   - Syntacically speaking methods are signified by parenthesis immediately  following their name e.g. alert(), these parenthesis sometimes hold values called parameters which are required by some methods
 -A parameter is simply information needed by a method in order to accomplish its task ,for instance the alert() methods pop up an alert box without a parameter the alert method will generate a dialo box(using in Internet Explorer) alert() which is meaningless ,but with a parameter the alert method will generate a dialog box alert("Hello World") which communicates a messages to the end user.
-Here are a few JavaScript methods:
-alert()causes an alert dialog box appear over the page that launched it
-write() writes content to a page.
-focus()causes the mouse cursor to be inserted into a form element .
Notice the parenthesis following the above methods?That is how you distinguish a method from a property or object .
NB:Please note that these definitions are given in the context of web web programming ,they may also be loosely be used to define the terms in Java as well.
Core APIs in the DOM
-document and window objects are the objects whose interfaces you generally use the most often in DOM programming ,In simple terms the window objet represents something like the browser and the document object is the root of the document itself.
-Element inherits from the generic node interface and together these two interfaces provide many of the methods and properties you use an individual elements
The following is a brief list of common APIs in web and XML page scripting using the DOM
-document.getElementById(id)
-document.getElementByTagName(name)
-document.CreateElement(name)
-parentNode.appendChild(node)
-element.innerHTML
-element.setAttribute
-element.getAttribute
-element.addEventListener
-window._content
-window._onload
-window._dump()
-window._ScrollTo()
# Functions in Action
A function is a subprogram designed a particular task, a function will only evecute if and only when it has been called (invoking a function) values can be passed into functions and used within that function as well and all functions should have a return value otherwise they become undefined (value is unknown ) but most importantly you must know that a function is an object(an HTML element ,with properties and methods) A function declaration is as follows
function name(parameters){
statements
}
-Name is the unique name of the function ,all function names in a script must be unique .
-Parameters one or more parameter variables you pass to the function.
-Statements are the instructions carried out by the function ,you can put mosly anything here.
# Calling a function with an event handler
A common way of calling a function is to include a refernce to it in a form button or hypertext link , processing a user-defined function when the user clicks a form button is perphaps the easiet of all you use onClick event handler to tell JavaScript that when the user clicks on the button the function specified should be processed .
JavaScript Methods and "this" keyword ,In JavaScript, objects can also contain functions e.g 
//objects containing method 
let person= {
name:`john`
greet:function(){
console.log(`hello`)
}
In the above example , a person object has a key (name and greet) and string value and a function has a function value .
# Accessing object methods
-You can access an object method by calling an object method using a dot notation ,the syntax is objectName.Methodkey().
You can access a method by calling an objectName and a key for that method along with() and you can access property only by calling an objectName and a key ,if you try to access the method with only person greet it will give you a function definition.
# JavaScript Built-in Methods
In JavaScript there are many built-in methods e.g
let number=`23.32`;
let result=parselnt(number);
console.log(result);//23
Here , the parselnt() method of Number object is used to convert numeric string value to an integer value , adding a method to a JavaScript ,object you can also add a method in an object e.g 
//creating an object
let student={}; 
//adding a property
student.name=`John`;
//adding a method
student.greet=function() {
console.log(`hello`);
}
//accessing a method 
student.greet(),//hello
In the above example, an example , an empty student object is created , then the name property is added similarly the greet method is also added in this way you can add a method as well as property to an object.
# JavaScript this keyword <br><br>
-to access a property of an object from witin a method of the some object you need to use the keyword.
# JavaScript Switch Statement
-The switch statement is used to perform different actions based on different conditions.
Syntax
-switch(expression){
case x:
//code block
break;
case y:
//code block
break;
default:
//code block
}
This is how it works:
-The switch expression is evaluated once.
-The value of the expression is compared with values of each case.
-If there is a match , the associated block is executed.
-If there is no match , the default code block is executed.
The break keyword
-When JavaScript reaches a break keyword it breaks out of the switch block,this will stop the execution of inside te block so it is not necessary to break the last case in a switch block the block breaks (ends) there anyway.
The default keyword
-The default keyword specifies the code to run if there is no case match however if default is not the last case in the switch block, remember to end the default case with a break.
Common Code Blocks.
-Sometimes you will want different switch cases to use the same code .
Switching Details
-If multiple cases matches a case value , the first case is selected but if no cases are found the program continues to the default label however if there is no default label found the program continues to the statements after the switch.
Strict Comparsion
-Switch cases we use strict comparsion(===) ,the values must be of the same type to match .
-A strict comparsion can only be ttrue if the perands are of the same type .
The Window Object
-The Window object represents a window in a browser , where as an object of window is created automatically by the browser and the window is the object of the browser not an object of JavaScript .
-JavaScript objects are strings , arrays , date , .etc.
# Week3 1-5
# Strings operations
-Strings in programming are sequences of characters. You can create strings in different ways: by just typing them out, using a constructor function called String(), or by using backticks for what's called a template literal.
-You can access individual characters in a string using methods like charAt() or by treating the string like an array and accessing characters by their numerical index.
-In JavaScript, you don't need a special function like in some other languages to compare strings. You can just use the less-than (<) or greater-than (>) operators. If you need to compare without considering uppercase or lowercase differences, you can use the localeCompare() method.
-It's important to note that JavaScript treats strings created directly with quotes differently from those created with the String() function. However, JavaScript automatically converts between them when needed.
When using eval(), there's a difference between passing a string directly and passing a string object. The code might behave unexpectedly if it receives a string object when it expects a simple string. But you can always convert a string object back to a simple string using the valueOf() method.
-In simpler terms, you can create strings in different ways, access their characters, compare them, and convert between different types of string representations in JavaScript.
Event handlers are like helpers for web elements that manage how they respond to user actions like clicks, key presses, or gaining focus. You can set them up in HTML attributes or through JavaScript properties. Each element can have one event handler per action. To handle multiple actions or events better, addEventListener() is preferred.
# On hand Event handlers
-Event handlers take parameters, and the this keyword refers to the element the handler is attached to. Their return value determines if the event should proceed.
-When we talk about event handling, we might refer to functions or objects that respond to events, or specifically to methods of registering these listeners, like addEventListener() for more flexibility.
# Event handler specifications
-Event handlers are used to manage how elements react to user actions like clicks or key presses.
-They can be set up in HTML attributes or through JavaScript properties.
-Each HTML element, as well as document and window objects, can support specific event handlers.
-Event handlers can handle various events like clicks (onclick), key presses (onkeydown), media playback (onplay), and many others.
-These handlers are automatically called when certain events occur, like clicking on an element or pressing a key.
-They can be used to perform actions or execute functions in response to user interactions.
-Understanding event handlers is crucial for creating interactive and dynamic web applications.
# Dynamic HTML
Dynamic HTML (DHTML) involves combining CSS and JavaScript with HTML to create interactive web pages.
-Changes on a webpage can be triggered by events, allowing for dynamic alterations such as font, color, style changes, and even content manipulation.
-HTML objects can be modified in two primary ways:
-Changing the class of the object to adjust its style.
-Using the style property directly to modify the object's style.
-JavaScript functions can be designed in various ways:
-Directly referencing an object in the function using its ID to change its style.
-Passing an object's ID as an argument to the function for flexible style changes.
-Accessing objects based on the event that occurred, allowing for targeted changes based on user interactions.

Static HTML Pages:
-Static HTML pages are pre-defined and do not change based on user interactions.
-Content is fixed and doesn't update without manual changes to the HTML file.
-There is no interaction with the server or backend systems.
-Basic HTML pages without scripting or dynamic content fall under this category.
Dynamic HTML Pages:
-Dynamic HTML pages change and update based on user interactions or server-side data.
-Content can be modified without reloading the entire page.
-Utilizes technologies like JavaScript, AJAX, and server-side scripting languages (e.g., PHP, Python) to generate content dynamically.
-Allows for interactive features like form submissions, real-time updates, and data fetching from databases or APIs.
-Offers a more engaging and responsive user experience compared to static pages.
# Date Object
-The Date object in JavaScript helps handle dates and times. It allows you to work with dates and times, like finding out the current date and time, or creating specific dates for your programs.
Here's a simple explanation of the Date object with examples:
Creating a Date object:
-You can create a Date object using the new Date() constructor. If you don't pass any arguments, it will give you the current date and time.
example:
let currentDate = new Date();
console.log(currentDate); // Output: current date and time
-Specifying a specific date and time:
-You can also create a Date object by passing specific parameters such as year, month, day, hour, minute, and second.
eample:
let specificDate = new Date(2024, 3, 25, 12, 30, 0); // Year, month (0-indexed), day, hour, minute, second
console.log(specificDate); // Output: Mon Apr 25 2024 12:30:00 GMT+0000 (Coordinated Universal Time)
Getting different components of a date:
You can extract various components of a Date object like year, month, day, etc., using specific methods such as getFullYear(), getMonth(), getDate(), etc.
example:
console.log(currentDate.getFullYear()); // Output: current year
console.log(currentDate.getMonth());    // Output: current month (0-indexed)
console.log(currentDate.getDate());     // Output: current day of the month
-Formatting dates:
-You can format dates as strings using methods like toDateString(), toLocaleDateString(), toLocaleTimeString(), etc.
example:
console.log(currentDate.toDateString());        // Output: "Thu Mar 25 2024"
console.log(currentDate.toLocaleDateString()); // Output: "3/25/2024"
console.log(currentDate.toLocaleTimeString()); // Output: current time in local time format
-Performing operations with dates:
You can perform operations like adding or subtracting days, hours, etc., using methods like setDate(), setHours(), getTime(), etc.
example:
currentDate.setDate(currentDate.getDate() + 7); // Adding 7 days to the current date
console.log(currentDate.toDateString());        // Output: Date increased by 7 days
Overall, the Date object is handy for dealing with dates and times in JavaScript, allowing you to perform various operations and manipulations with ease.
Retrieving the Date with get  
-The Date object in JavaScript allows us to access different components of a date using various built-in methods.
-These methods return each part of the date relative to the local timezone.
-Each method starts with "get" and returns a relative number representing the specific component of the date.
-Here's a summary of the "get" methods of the Date object:
getFullYear(): Returns the year (YYYY) ranging from 1970 onwards.
getMonth(): Returns the month from 0 to 11, where 0 represents January.
getDate(): Returns the day of the month from 1 to 31.
getDay(): Returns the day of the week from 0 to 6, where 0 represents Sunday.
getHours(): Returns the hour from 0 to 23, where 0 represents midnight.
getMinutes(): Returns the minute from 0 to 59.
getSeconds(): Returns the second from 0 to 59.
getMilliseconds(): Returns the millisecond from 0 to 999.
getTime(): Returns the milliseconds since Epoch time.
# Dynamic Events
The Date object in JavaScript offers methods starting with "get" to access date components, returning associated numbers relative to the instantiated object.
Corresponding to the "get" methods, there are "set" methods for modifying date components.
"Set" methods allow for changing one or multiple components of a date.
UTC methods, like getUTCFullYear(), provide date components based on the UTC standard, ensuring international time consistency.
UTC methods mirror regular "get" methods but calculate based on Coordinated Universal Time.
Adding or subtracting from a given date can be done with set methods, with values sometimes rolling over into the next or previous months for convenience.
# Keyboard, forms and document/windows events
# Keyboard Events
Keydown Event (onkeydown):
-Occurs when a user presses down a key.
-Handled with the onkeydown event handler.
Example:
document.addEventListener('keydown', function(event) {
    alert('Key down event occurred');
});
Keyup Event (onkeyup):
-Occurs when a user releases a key.
-Handled with the onkeyup event handler.
Example:
document.addEventListener('keyup', function(event) {
    alert('Key up event occurred');
});
Keypress Event (onkeypress):
-Occurs when a user presses down a key with a character value.
-Certain keys like Ctrl, Shift, Alt, etc., do not generate this event.
-Handled with the onkeypress event handler.
Example:
document.addEventListener('keypress', function(event) {
    alert('Key press event occurred');
});
# Form Events
Focus Event (onfocus):
-Occurs when an element receives focus.
-Handled with the onfocus event handler.
Example:
<input type="text" onfocus="this.style.backgroundColor='yellow'">
Blur Event (onblur):
-Occurs when an element loses focus.
-Handled with the onblur event handler.
Example:
<input type="text" onblur="alert('Input lost focus')">
Change Event (onchange):
-Occurs when the value of a form element changes.
-Handled with the onchange event handler.
Example:
<select onchange="alert('Option changed')">
    <option value="1">Option 1</option>
    <option value="2">Option 2</option>
</select>
Submit Event (onsubmit):
-Occurs when a form is submitted.
-Handled with the onsubmit event handler.
Example:
<form onsubmit="alert('Form submitted')">
    <!-- Form inputs -->
    <button type="submit">Submit</button>
</form>
 # Document/Windows Events
  -The onload event is one of the most important events in web development. Here's more information on the onload event:
What is the onload event?
-The onload event occurs when a web page, including all its resources like images, scripts, stylesheets, etc., has finished loading in the web browser.
Purpose of the onload event:
-The onload event is used to execute JavaScript code or perform actions after the entire web page has been loaded, ensuring that all resources are available for manipulation or interaction.
Common use cases:
Initialization: You can use the onload event to initialize elements, set up event listeners, or perform any setup tasks required for the functionality of the page.
Manipulation: You can modify elements, change styles, or dynamically load content based on the page's layout or state after it has fully loaded.
Integration: It's often used to integrate third-party scripts or resources that require the full page to be loaded before they can be executed or interacted with.
How to use the onload event:
Inline HTML attribute: You can directly specify the onload event handler in the HTML element like <body onload="myFunction()">.
DOM event listener: You can add an event listener for the load event on the window or specific elements using JavaScript.
   example:
window.onload = function() {
    // Code to execute after page load
};
Example:
Suppose you want to display a greeting message after the page has fully loaded:
<body onload="displayGreeting()">
<script>
    function displayGreeting() {
        alert("Welcome to our website!");
    }
</script>
Best practices:
-Keep JavaScript code related to the onload event minimal to avoid delaying the page load unnecessarily.
-Consider using asynchronous loading techniques for resources that are not critical to the initial page rendering to improve performance.
-Cross-browser compatibility:
-The onload event is well-supported across modern web browsers, including Chrome, Firefox, Safari, Edge, and others.
Load Event (onload):
-Occurs when a web page finishes loading in the browser.
-Handled with the onload event handler.
Copy code
<body onload="alert('Page loaded')">
Unload Event (onunload):
-Occurs when a user leaves the current web page.
-Handled with the onunload event handler.
Example:
<body onunload="alert('Leaving page')">
Resize Event (onresize):
-Occurs when the browser window is resized.
-Also occurs when the window is minimized or maximized.
-Handled with the onresize event handler.
Example:
<body onresize="alert('Window resized')">
# Creating a image-slider and wrapper with HTML,CSS and JavaScript
 HTML:
-Create a container (wrapper) to hold the image slider.
-Inside the wrapper, create a div for the slider images and navigation buttons.
CSS:
-Style the slider wrapper, slider container, slider images, and navigation buttons.
JavaScript:
-Create functions to handle sliding between images.
   Summary:
-The HTML code creates a wrapper div .slider-wrapper to contain the slider and navigation buttons.
-Inside the wrapper, a div .slider holds the slider images, and navigation buttons .prev and .next allow users to navigate through the slides.
-CSS styles the wrapper, slider, images, and buttons for layout and appearance.
-JavaScript code handles the sliding functionality by showing and hiding images based on the current slide index.
-An interval is set to automatically advance slides every 2 seconds.
-showSlides() function is called initially to display the first slide.
 # Week4 Day1-5
# Program flowchart
-After a problem or opportunity has been analysed,the program to be used in solving the problem must be designed.
-The result of this design process is a program flowchart ,the program flowchart illustrates the logic of the program and gives details on manipulating the data it is less costly to dtermine,arrange and rearrange complex logic on a flowchart than to correct logic errors in an implemented program.
   -A program flowchart is vital if the program is to be maintained easily and efficiently or if modifications are necessary .
   # Program flowchart symbols
   -Program flowcharts are constructed with a set of standardised symbols that make it easier for persons other than the original programmer to read and maintain the program.
   # JavaScript for Loop
   -Loops can execute a block of code a number of times and are handy if you want to run the same code over and over again , each time with different values often this is the case when working with arrays .
   Instead of writing:
   text+=cars[0]+"<br>"
   text+=cars[1]+"<br>"
   text+=cars[3]+"<br>"
   text+=cars[4]+"<br>"
   text+=cars[5]+"<br>"
You can write:
var i;
for(i=0;i<cars.length;i++){
            text+=cars[i] + "<br>"
}
Different kinds of Loops.
-JavaScript supports different kinds of loops :
#for-loops through a block of code a number of lines
#for/in-loops through the properties of an object.
#for/of-loop through the value of an iterable object
#while-loops through a block of code.
#do/while-also loops through a block of code while a specified condition is true .
   The for Loop
   -The for Loop has the following syntax:
for(statement1;statement2;statement3){
   //code block to be excuted
}
Statement1 is executed(one time) before the execution of the code block
Statement2 defines the condition for executing the code block.
Statement3 is excuted(every time) after the code block has been executed.
Example
for(i=0;i<5;1++){
   text+="The number is"+i+"<br>"
}
from the example above you can read :
Statement1 sets a variable before the loop starts(var i=0).
Statement2 defines the condition for the loop to run (i must be less then 5).
Statement3 increases a value(i++) each time the code block in the loop has been executed.
-Statement1 
Normally you will use statement1 to initialize the variable used in the loop (i=0), this is not always the case , JavaScript doesnt care.
Statement 1 is optional you can initate many values in statement1 (separated by comma).
-Statement2
Normally statement2 is used to evaluate the condition of the initial variable ,this is not always the case JavaScript doesnt care but statement2 is also optional .
If statement 2 again if it returns false the loop will end , if you omit statement2 you must provide a break inside the loop otherwise the loop will never end and this will crash the browser.
-Statement3 
Often statement3 increments the value of the inital value ,this is not always the case JavaScript doesnt care either and statement 3 is also optional .
Statement3 can do anything like negative increment (i--), postive increment(i=i+15),or anything else ,statement 3 can also be omitted(like when you increment your values inside the loop. )  
General Web Optimization
-General web optimization refers to the process of improving various aspects of a website to enhance its performance, visibility, user experience, and ultimately achieve specific business goals.
-Website Speed Optimization: This involves minimizing the loading time of web pages by optimizing images, reducing server response times, leveraging browser caching, and minimizing redirects.
   -Faster-loading websites tend to have lower bounce rates and higher user engagement.
-Mobile Optimization: With the increasing use of smartphones and tablets, it's crucial for websites to be optimized for mobile devices. 
   -This includes using responsive design techniques to ensure that the website adapts seamlessly to different screen sizes and resolutions.
-Search Engine Optimization (SEO): SEO involves optimizing various elements of a website to improve its visibility in search engine results pages (SERPs). 
   -This includes keyword research, on-page optimization (such as optimizing meta tags, headings, and content), off-page optimization (such as link building), and technical SEO (such as improving website structure and ensuring crawlability).

-Content Optimization: High-quality, relevant content is essential for engaging users and improving search engine rankings. 
-Content optimization involves creating valuable, informative, and engaging content that addresses the needs and interests of the target audience.
-This includes optimizing content for specific keywords, using proper formatting and structure, and regularly updating and refreshing content.
-User Experience (UX) Optimization: Providing a positive user experience is critical for keeping visitors engaged and encouraging them to return to the website. 
-UX optimization involves improving website navigation, readability, accessibility, and overall usability. 
-This includes optimizing page layouts, designing clear calls-to-action, and minimizing distractions.
-Conversion Rate Optimization (CRO): CRO focuses on improving the percentage of website visitors who take a desired action, such as making a purchase, signing up for a newsletter, or filling out a contact form.
-This involves testing and optimizing various elements of the website, such as headlines, images, forms, and checkout processes, to maximize conversions.
-Technical Optimization: This includes various technical aspects of website optimization, such as optimizing code, fixing broken links, improving site security, and implementing structured data markup to enhance search engine visibility.
 # Node js
 -The history of Node.js spans over a decade, starting in 2009 when Ryan Doll created it as a JavaScript runtime on Chrome's VA engine. Its pivotal moment came in 2011 with the release of npm 1.0, enabling easy sharing of open-source node libraries.
 -This established Node.js as a key player in the JavaScript ecosystem. In 2015, amidst community disputes, the Node.js Foundation was formed, backed by major entities like IBM, Microsoft, and PayPal, ensuring collaborative growth and evolution under the Linux Foundation. Today, Node.js boasts a flourishing community with global conferences and wide applications across industries.
-The text introduces Node.js as a platform that expands JavaScript's capabilities beyond front-end development, allowing tasks like building command line tools and servers.
-Major companies like PayPal, Netflix, and Microsoft have embraced Node.js since its inception in 2009 for scalable event-driven applications. 
-The course aims to cover fundamental aspects of Node core, including standard input/output, the module system, and the file system, with practical examples applicable in real-world scenarios.
the advantages of using JavaScript for both front-end and back-end development, highlighting the elimination of syntax disparities and the ability to seamlessly share code and data structures. 
-It presents examples such as utilizing libraries like Underscore for encryption functions uniformly and ensuring consistency in user authentication systems and algorithms between front-end and back-end. 
-The text emphasizes the importance of minimizing redundancy and maximizing efficiency by unifying development in a common language for both front-end and back-end tasks.
 -The benefits of JavaScript, particularly with Node.js, emphasizing its use for both back-end and front-end development, which enables seamless code sharing. 
 -It discusses JavaScript's dynamic typing and its integration with JSON, simplifying data transfer between back-end and front-end components. 
 -While acknowledging that JavaScript may not suit all scenarios, its versatility and the ability to share code enhance the development experience for web applications.
 -Synchronous and asynchronous tasks in computer programming. 
 -Synchronous tasks make us wait for each task to finish before moving on to the next, causing delays.
 -Asynchronous tasks allow us to continue with the next task without waiting for the current one to complete, which is helpful for tasks like networking or file system access in web applications. 
 -Node.js is efficient in handling such tasks. Asynchronous code often uses callbacks, like leaving a phone number for a callback in tech support, which triggers a function once the task is done. 
 -The text gives an example of loading directories from a drive using Node.js, showing how asynchronous code works with callbacks to execute tasks efficiently without waiting for each one to finish. 
 # Node Globals
 -In Node.js, global variables are accessible throughout the entire application without needing to require them explicitly. 
 -These variables are part of the global object, which in Node.js is called 'global'. Node.js provides several built-in global variables that are commonly used in Node.js applications.
 -Here are some of the commonly used global variables in Node.js:
__dirname: Represents the directory name of the current module. It provides the absolute path to the directory containing the currently executing script.
__filename: Represents the file name of the current module. It provides the absolute path to the currently executing script.
exports: Used to define the exports of a module. It is an alias for module.exports.
--module: Represents the current module. It contains information about the current module, such as its filename and exports.
--process: Provides information about the current Node.js process. It allows you to access information such as command-line arguments, environment variables, and standard input/output streams.
--console: Provides methods for printing messages to the console, such as console.log(), console.error(), and console.warn().
# Node Modules
-In Node.js, modules are reusable blocks of code that encapsulate related functionality, such as functions, objects, or variables. 
-Modules help organize code into logical units, making it easier to manage, maintain, and reuse.
There are two types of modules in Node.js:
-Core Modules: These are built-in modules provided by Node.js. They are available globally and can be accessed using the require() function without specifying a file path. 
-Examples include modules for working with file systems (fs), handling HTTP requests (http), and managing paths (path).
-Example of using a core module:
const fs = require('fs');
-Local Modules: These are user-defined modules created by developers to encapsulate specific functionality.
-Each local module resides in its own file and can be imported into other modules using the require() function by specifying the file path.
-Example of creating and using a local module:
// math.js
module.exports.add = (a, b) => a + b;
module.exports.subtract = (a, b) => a - b;
// app.js
const math = require('./math.js');
console.log(math.add(5, 3)); // Output: 8
# Writing to flies
-In Node.js, you can write data to files using the built-in fs (File System) module. This module provides various methods for interacting with the file system, including writing data to files.
-Here's a basic overview of how you can write to files in Node.js:
-Require the fs Module: First, you need to require the fs module in your Node.js application.
-Use fs.writeFile() or fs.createWriteStream():
There are two main methods for writing data to files in Node.js:
-fs.writeFile(): This method is used to asynchronously write data to a file. 
-fs.createWriteStream(): This method is used to create a writable stream to a file.
-It provides better performance for writing large amounts of data to a file.
-It creates a new file if it doesn't exist or overwrites the existing file's contents.
-Handling Errors: Both fs.writeFile() and fs.createWriteStream() methods accept a callback function as their last argument, which will be called with an error object if an error occurs during the write operation. 
-It's essential to handle errors properly to ensure the robustness of your application.
-Stream Events: If you're using fs.createWriteStream(), you can listen for the 'finish' event to know when all data has been written to the file.
-Specifying Encoding: By default, data is written to files in binary mode.
-You can specify the encoding to write data as strings. Common encodings include 'utf8', 'utf-8', 'ascii', 'base64', 'binary', 'hex', and 'ucs2' or 'ucs-2'.
-Appending Data to Files: If you want to append data to an existing file without overwriting its contents, you can use the fs.appendFile() method.
# Data Object as a second parameter
-String Data: You can provide a string as the data to be written to the file. For example:
fs.writeFile('example.txt', 'Hello, world!', (err) => {
    if (err) throw err;
    console.log('Data written to file');
});
-Buffer Data: You can provide a Buffer object containing binary data to be written to the file. For example:
const bufferData = Buffer.from('Hello, world!', 'utf8');
fs.writeFile('example.txt', bufferData, (err) => {
    if (err) throw err;
    console.log('Data written to file');
});
-Uint8Array Data: You can provide a Uint8Array containing binary data to be written to the file. For example:
const uint8ArrayData = new Uint8Array([72, 101, 108, 108, 111, 44, 32, 119, 111, 114, 108, 100, 33]);
fs.writeFile('example.txt', uint8ArrayData, (err) => {
    if (err) throw err;
    console.log('Data written to file');
});
-The data object as the second parameter of fs.writeFile() or fs.appendFile() represents the actual content that will be written to the file.
-Depending on the data type provided, Node.js will write the data accordingly, whether it's a string, binary data, or a file descriptor. 
-It's essential to choose the appropriate data format based on your application's requirements and the type of data you need to write to the file.
# Node Frameworks
-Node.js frameworks are collections of libraries and tools that provide a structured way to build web applications and APIs using Node.js. 
-These frameworks offer features and utilities to simplify common tasks such as routing, request handling, middleware management, and database integration. 
-They aim to streamline development processes and improve productivity by providing a robust foundation for building server-side applications.
-Express.js: Express.js is one of the most widely used Node.js frameworks. It's minimalist and flexible, allowing developers to build web applications and APIs quickly and efficiently. Express provides a simple, yet powerful set of features for routing, middleware, and HTTP request/response handling.
-Koa.js: Koa.js is a modern, lightweight framework developed by the creators of Express. It leverages ES6 features like async/await and generators to provide a more elegant and efficient way to write middleware. Koa aims to provide a more expressive and robust foundation for web applications.
-Sails.js is a modern, MVC (Model-View-Controller) framework for building data-driven web applications in Node.js. It's designed to make it easy to build custom, enterprise-grade Node.js applications. 
 # Socket.oi
Socket.io: Socket.io is a real-time web socket library for Node.js that enables bidirectional communication between web clients and servers. It provides a simple API for handling events and managing connections, making it ideal for building chat applications, multiplayer games, and real-time dashboards.
# React.Js
# What is React.js?
-React is a popular JavaScript library used for building user interfaces (UI) in web applications. It was developed by Facebook and released to the public in 2013. React is known for its efficiency, scalability, and component-based architecture, which makes it easier to build complex UIs by breaking them down into reusable and modular components.
-The core idea behind React is the concept of a virtual DOM (Document Object Model). The virtual DOM is a lightweight representation of the actual DOM, which is a tree-like structure that represents the HTML elements of a web page. React uses this virtual DOM to efficiently update and render components.
-When building a React application, you define components, which are reusable building blocks of the UI. Each component represents a part of the user interface and can have its own state and properties. State represents the data that can change over time, while properties (props) are immutable values passed to a component from its parent component.
-React uses a declarative syntax, which means you describe how your UI should look based on its current state, and React takes care of updating the actual DOM to reflect the desired state. When the state of a component changes, React efficiently updates only the necessary parts of the DOM, minimizing the number of actual manipulations and improving performance.
# Reactjs.org documentation site















 
 
 




 
