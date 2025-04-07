---
sidebar_position: 1
---

# Common Issues

### Return Keyword

A common mistake is to forget the return keyword, in which case the function will return undefined

```javascript
function sum(number1, number2) {
    console.log(number1 + number2); 
}
sum(1,2); //returns undefined
```

### Invoking functions:
The code inside a function is not executed when the function name is just written, only when it is invoked using () . Invoking is different in DOM than in the script.

#### Template engines generate HTML and are there for parts of the DOM

### Example in Vue.js
```vue
<template>
  <div>
    <h1>Hello, world!</h1>
    <p>This is a simple webpage.</p>
    <button @click="myFn">Click me</button>
  </div>
</template>

<script>
  export default {
    methods: {
      myFn() {
        console.log('test');
      }
    }
  }
</script>
```
### Example of template engines
- Vue
- Nuxt
- Laravel
- JS Frameworks