# Type 'string[]' is not assignable to type 'string'
This repo contains a simple TypeScript program that demonstrates a common type error: assigning an array of strings to a variable of type string. The error message is: `Type 'string[]' is not assignable to type 'string'.`

## Bug
The `greeter` function expects a string argument, but the `user` variable is an array of strings. When the code attempts to call `greeter(user)`, TypeScript throws a type error because the argument types don't match.

## Solution
The solution involves either modifying the `greeter` function to accept an array of strings or modifying the `user` variable to be a single string.  The example shows how to iterate over the array and call the `greeter` function for each name.