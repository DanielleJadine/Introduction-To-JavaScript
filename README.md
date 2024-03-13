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
 # Week 2
 Day1-5
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
 
 
 




 
