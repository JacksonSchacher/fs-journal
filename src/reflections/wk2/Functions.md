# JavaScript Functions

## Writing Functions and Differences
---
Function Declaration: function name(parameters) {
    //statements
} *definition is hoisted, allowed to use before it's defined*
Function Expressions: let name = function(parameters) {
    //statements
} *not hoisted, cannot be used before they're defined*
Arrow Function Expression: let name = (parameters) => {
    //statements
} *don't create their own 'this' value*

---

## Parameters vs. Arguments
---
Parameters are used when defining a function (names created in the function definition)

Arguments are the values the function receives from each parameter when invoked. 

---

## Higher Order Functions
---
Higher-Order Function is when a function accepts another function as a parameter or returns a function.

Array.map() Array.find()

---