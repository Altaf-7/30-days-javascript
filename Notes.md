# Notes
## "use strict"
"use strict" enables strict mode in JavaScript, which catches common coding mistakes and prevents unsafe behavior like accidental global variables, Disallows Duplicate Parameters,Makes `this` Safer, Prevents Some Reserved Keywords.


## let vs var
let is morden-way of defining variables, var is older way of defining variables.

## Data Types
There are 8 basic data types in JavaScript.
### Seven primitive data types:
- number for numbers of any kind: integer or floating-point, integers are limited by ±(2^53-1).
- bigint for integer numbers of arbitrary length.
- string for strings. A string may have zero or more characters, there’s no separate single-character type.
- boolean for true/false.
- null for unknown values – a standalone type that has a single value null.
- undefined for unassigned values – a standalone type that has a single value undefined.
- symbol for unique identifiers.

### one non-primitive data type:
- object for more complex data structures.

The typeof operator allows us to see which type is stored in a variable.

### typeof
Usually used as typeof x, but typeof(x) is also possible.
Returns a string with the name of the type, like "string".
For null returns "object" – this is an error in the language, it’s not actually an object.