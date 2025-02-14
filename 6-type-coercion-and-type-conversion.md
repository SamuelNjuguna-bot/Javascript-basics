# Type Conversion and Coercion


1. ## coercion ##


In this type, java script implicitly converts one form data type to another while using the ternary operator ``` + ``` or comparison operator ` ==`


Below are some of the examples
```
console.log("5" + 3);         // "53" - Number is coerced into a string
console.log("5" - 3);         // 2 - String is coerced into a number
console.log("5" * "2");       // 10 - Both strings converted to numbers
console.log(5 == "5");        // true - Loose equality allows coercion
 ```
 2.  ## Conversion ##

 In this kind of conversion the programmer has to use some keywords to change one form of datatype to another, such as as the table below shows.


 | Keyword        | Use                                    | Example                      |
|---------------|----------------------------------------|------------------------------|
| `String()`    | Converts a value to a string         | `String(123) → "123"`        |
| `.toString()` | Converts a value to a string         | `(42).toString() → "42"`     |
| `Number()`    | Converts a value to a number         | `Number("123") → 123`        |
| `parseInt()`  | Converts a string to an integer      | `parseInt("100px") → 100`    |
| `parseFloat()`| Converts a string to a float         | `parseFloat("10.5") → 10.5`  |
| `Boolean()`   | Converts a value to a boolean        | `Boolean(1) → true`          |
| `Boolean()`   | Converts a falsy value to `false`    | `Boolean("") → false`        |
