# Javascript-beginner-advanced-expert-exercise-solutions
## Beginners
### Exercise-1:
#### Swap the values of 2 variables
```js
// takes two variables
let varOne = "Variable One";
let varTwo = 2;
//before swap
console.log("------------Before Swap ----------------");
console.log('Variable one =>', varOne);
console.log('Variable Two =>', varTwo);
//let's take a third variable for swap
let varSwap = varOne;
varOne = varTwo;
varTwo = varSwap;

// print the values
//after swap
console.log("------------After Swap ----------------");
console.log('Variable one =>', varOne);
console.log('Variable Two =>', varTwo);
```
### Exercise-2:
#### Write a function which returns the maximum of two number
```js 
//Write a function which returns the maximum of two number
function twoMaxNumber(num1,num2){
    // if(num1 < num2){
    //     return num2;
    // }else{
    //     return num1;
    // }
    return num1 > num2 ? num1 : num2;
}

console.log(twoMaxNumber(200,25));
```

