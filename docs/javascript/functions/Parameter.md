---
sidebar_position: 1
---

# Parameter

Special variable used in a function to refer to data when you call the function.

## Ways to utilize parameters

### Function with variable as parameter

```javascript
function greet(name) { //name is parameter
    console.log("Hello, " + name + "!");
}

greet("John");
```

### Function with default values as parameters

```javascript
// Defining the function with default values
function sum(num1 = 6, num2 = 1) {
  return num1 + num2;
}

// Calling the function
console.log(sum(8));
// Output 9

```

### Function with another function as parameter
```javascript
function processData(data, callback) {
    console.log("Processing data:", data);
    callback(data);
}

processData("Some data", (data) => {
    console.log("Callback received:", data);
});
```
Parameters can be any value: string, number, boolean, array, object, function, or even null or undefined.

