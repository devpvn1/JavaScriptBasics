# JavaScriptBasics
Javascript has 3 components
1) ECMA Script
2) DOM - Document Object model
3) BOM - Browser Object model

# HTML 5
&lth;!Doctype HTML;&grt;
otherwise HTML4 or XHTML with Transitional,strict and frameset modes

If doctype is not mentioned, it will go for inconsistent quirkmode rendering

# Difference between async and defer in script Tag?
async - included in HTML5; asychronously load script tag sources without any order in which script tag is defined
defer - included in HTML4; asychronously load script tag sources in the order in which script tag is defined

# How to check whether a variable is undefined?
var message;
if(message == undefined){  // true
   //do stuff
}

# The value undefined is a derivative of null
if(null == undefined) //true

# ECMA5 Object Properties
1) Data Properties
      a) Configurable
      b) Enumerable
      c) Writable
      d) Value
eg: 
var person = {};
Object.defineProperty(person, name,{
  writable : false,
  value : "Ram"
});

