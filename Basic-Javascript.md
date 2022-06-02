# Javascript
## Comment
``` Javascript
// In-line comment

/*
multi-line
comment
*/
```

## Data types and variable
- Undefined, null, boolean, string, symbol, number, and object
``` Javascript
// Can be used through out the whole program
var name = "Abby";
// Can only used in the scope that it is declared
let myName = "Abby";
// Varable that never change
const pi = 3.14;
```

## Operators
``` Javascript
// Addition
var a = 1 + 2;
// Subtraction
var a = 5 - 1;
// Multiplication
var a = 3 * 3;
// Division
var a = 10 / 2
// Incrementing
var a = a++;
a += 1;
// Decrementing
var a = a--;
a -= 1;
// Remainder
var remainder = 11 % 3;
// Escape quotaion mark
var str = "this is quotation mark \"";
// Put string in single quotation mark (or back tick) to escape double quotation
var str = 'this is quotation mark "';
// New line, tab
\n \t
// String concatenation
var str = "first" + "second";
```

## Array
``` Javascript
var array = ["number", 1];
// Nested array
var nestedArray = [["hello", "world"], ["number", 2]];
// Get element in an array and modify
var data = array[1] + 1;
// Append an element
array.push(3);
// Add to the beginning of an array
array.unshift("Hello");
// Remove last element
var lastElement = array.pop();
// Remove first element
var firstElement = array.shift();
```

## Function
``` Javascript
function printToConsole() {
    console.log("Hello world");
}
function sum(a,b) {
    return a + b;
}
```

## Comparing operators
``` Javascript
// Equal: Convert type so 3 == '3' return true
a == b
// Strict equal: Doesn't convert type so 3 === '3' return false
a === b
// Inequality
a != b
// Strict inequality
a !== b
// Greater than or less than
a > b
a < b
// And Or
a && b
a || b
```