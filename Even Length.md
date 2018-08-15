Write a function called "isEvenLength".

Given a word, "isEvenLength" returns whether the length of the word is even.

Example: var output = isEvenLength('wow');
console.log(output); // --> false

SOLUTION:
```javascript
function isEvenLength(word) {
  if (word.length % 2 === 0){
    return true;
  }else {
    return false;
  }
}

//To check for an even numbered word, we use the remainder operator to ensure that the remainder is equivalent to 0
