---
sidebar_position: 1
---

# Argument

An argument is a value you pass into a function when you call it, so the function can use it.

### String Example

```javascript
function greet(name) { //name is parameter
    console.log("Hello, " + name + "!");
}

greet("John"); //argument is John
```
An argument can be any value: string, number, boolean, array, object, function, or even null or undefined.

### Number Example
```javascript
function double(num) {
    console.log(num * 2);
}

double(5); // Outputs: 10
```
### How should I use it?

Use it when you call the function to actually provide the data.

### What makes an argument different from a parameter?
- Parameter = empty box

- Argument = items you put in the box