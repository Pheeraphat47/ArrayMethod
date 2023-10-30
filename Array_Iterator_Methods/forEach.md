# forEach()
* The .forEach() method calls a function for each element in an array.
## Usage
array.forEach(function(currentValue, index, array) {
  // Your code here
});
​
## Example
### Example 1: Printing elements of an array
```
let array = [1, 2, 3, 4, 5];
array.forEach(function(element) {
  console.log(element);
});
```
​
### Example 2: Modifying array elements using forEach
```
let words = ['apple', 'banana', 'cherry'];
words.forEach(function(word, index, arr) {
  arr[index] = word.toUpperCase();
});
console.log(words);
```