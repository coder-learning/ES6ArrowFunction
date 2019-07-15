# ES6 Arrow Function CheatSheet

The below explains the the key corner syntax which will be handely when you write your own Arrow function in javascript.

A simple javascript function to say Hi can be writen as below.

```
var sayHi = function(name){ return 'Hi ' + name };
```

To rewrite the above function using arrow function, it can be done as below

```
var sayHi = (name) => { return 'Hi ' + name };
```


# Key Syntax

## Rule 1 - Single parameter, no Parentheses is required

If there is only one parameter, then the parameter does not have to be enclosed in a parentheses. So the sayHi arrow function can be 
rewitten as below.

```
var sayHi = name => { return 'Hi ' + name };
```

## Rule 2 - No parameter, Parentheses is required

If are no parameter, then a parentheses is required. Let have an arrowfunction to return the value of Pi, then an arrow function can be rewitten as below.

```
var pi = () => { return 3.14 };
```

## Rule 3 - Implicit Return

### Rule 3.1 - Implicit Return - Stright forward String
If the function have single line with a return, then the return statment does not have to be enclosed in {}.  So the sayHi arrow function can be rewitten as below.

```
var sayHi = name => 'Hi ' + name;
```

### Rule 3.1 - Implicit Return - as Object
If the function have single line with a return as object, then the return statment does not have to be enclosed in {}.  So the sayHi arrow function can be rewitten as below.

```
var sayHi = name => ({Name: 'Hi ' + name});
```
