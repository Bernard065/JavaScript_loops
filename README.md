# JavaScript_loops

JavaScript provides several types of loops that allow you to repeatedly execute a block of code. The most commonly used loops in JavaScript are:

## For Loop:
The for loop is used to execute a block of code a specific number of times. It has three parts: initialization, condition, and update.
```javascript
for (initialization; condition; update) {
  // Code to be executed in each iteration
}
```


## while Loop
Reapeatedly executes a block of coe as long as a specified condtion is true.

```javascript
while (condition) {
  // Code to be executed in each iteration
}
```

## do...while Loop
Similar to while loop but the code is executed at least once before the condition is checked

```javascript
do {
  // Code to be executed in each iteration
} while (condition);

```

## for...of Loop
 The for...of loop is used to iterate over the values of iterable objects like arrays, strings, maps, sets, etc.

```javascript
 for (let element of iterable) {
  // Code to be executed for each element
}
```

## for...in Loop

This loop is used to iterate over the enumerable properties of an object. It's not recommended for iterating over arrays, but it's useful for iterating over object properties.


NB: Choose the appropriate type of loop based on your use case. Use for loops when you know the exact number of iterations, while and do...while loops for situations where the number of iterations is uncertain, and for...of or for...in loops for iterating over collections or object properties.