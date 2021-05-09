# Functions.
## What is the function?
##### - A JavaScript function is a block of code designed to perform a particular task.

##### - A JavaScript function is executed when "something" invokes it (calls it).


###### A function is a block of organized, reusable code that is used to perform a single, related action. Functions provide better modularity for your application and a high degree of code reusing. 

## JavaScript Function Syntax.

```
function name(parameter1, parameter2, parameter3) {
  // code to be executed
}
```
* Function parameters are listed inside the parentheses () in the function definition.

* Function arguments are the values received by the function when it is invoked.

* Inside the function, the arguments (the parameters) behave as local variables.

## Function Invocation
  The code inside the function will execute when "something" invokes (calls) the function:

 1- When an event occurs (when a user clicks a button).

 2- When it is invoked (called) from JavaScript code.
 
 3- Automatically (self invoked).


 ## Function Return
- When JavaScript reaches a return statement, the function will stop executing.

- If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.

- Functions often compute a return value. The return value is "returned" back to the "caller":



## Why Functions?
You can reuse code: Define the code once, and use it many times.

You can use the same code many times with different arguments, to produce different results.

* ### you can use function as a variable.
 #### Example:-
 ```
var x = toCelsius(77);
var text = "The temperature is " + x + " Celsius";
 ```

### you can nested functions.