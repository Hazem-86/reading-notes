# Function Invocation

## The code inside the function will execute when "something" invokes (calls) the function:
When an event occurs (when a user clicks a button)
When it is invoked (called) from JavaScript code
Automatically (self invoked)
You will learn a lot more about function invocation later in this tutorial.
# --------------
# Function Return

## When JavaScript reaches a return statement, the function will stop executing.
## If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.
## Functions often compute a return value. The return value is "returned" back to the "caller":

# Example:
## *Calculate the product of two numbers, and return the result:
var x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a * b;            // Function returns the product of a and b
}
