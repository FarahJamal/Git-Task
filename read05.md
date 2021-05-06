## Expressions & operators in Javascript.
### Operators
JavaScript has the following types of operators.
  - Assignment operators.(=,+=,*=,-=)
  -  Comparison operators.(<,>,==,!=)
  -  Arithmetic operators.(+,-,*,/)
  -  Bitwise operators.(&,|,^)
  -  Logical operators.($&&,||,!$)
  -  String operators.(+)
  -  Conditional (ternary) operator.(?:)
  -  Comma operator.(,) ---> The Comma operator evaluates each operand from left to right and returns the value of right most operand.
  -  Unary operators.().
    * As mentioned earlier, unary operators take only one operand in order to perform a specific operation. Some of the commonly used unary operators in JavaScript are:

      * typeof: Returns the type of the given operand
      * delete: Deletes an object, object’s attribute or an instance in an array
      * void: Specifies that an expression does not return anything
      * Increment Operators : ++, --
  -  Relational operators.( propNameOrNumber in objectName)
## Expressions.

Anything that evaluates to a value is called an expression.

# 2- JavaScript Loops
Loops are handy, if you want to run the same code over and over again, each time with a different value.

Often this is the case when working with arrays:
### Instead of writing:
```
text += cars[0] + "<br>";
text += cars[1] + "<br>";
text += cars[2] + "<br>";
text += cars[3] + "<br>";
text += cars[4] + "<br>";
text += cars[5] + "<br>";
```
### You can write:
```
var i;
for (i = 0; i < cars.length; i++) {
  text += cars[i] + "<br>";
}
```
## Different Kinds of Loops
JavaScript supports different kinds of loops:

* for - loops through a block of code a number of times.
* for/in - loops through the properties of an object.
* for/of - loops through the values of an iterable object.
* while - loops through a block of code while a specified condition is true.
* do/while - also loops through a block of code while a specified condition is true.
#### Example (for loop)
```
for (i = 0, len = cars.length, text = ""; i < len; i++) {
  text += cars[i] + "<br>";
}
```
#### While Loops.

