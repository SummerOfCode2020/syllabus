### JAVASCRIPT STATEMENTS

## IF, ELSE, AND SWITCH STATEMENT
* `if`: Use this to specify a block of code to be executed, if a specified condition is true.

* `else`: Use this to specify a block of code to be executed, if the same condition is false.

* `else if`: Use this to specify a new condition to test, if the first condition is false.

* `switch`: Use this to specify many alternative blocks of code to be executed.


* CODE EXAMPLES: 
- `if` Syntax: 
```
if (condition){
    // Block of code to be executed if the condition is true.
}
```

- `if` Code:
```
// This function adds 1 to any number sent through it
function increaseLevel(number) {
    if (number){
    /* Below is our code for our condition stating
    that our parameter `number` is equal to the
    parameter plus one.
    */
    number = number + 1
    
    }
    /* If the condition is true the code will run
    and `number` will be returned.
    */
    return number
}
/* When testing it `9` would pass and equal `10`.
While `a` will fail because its not a number and fails
to meet the condition.
*/
console.log(increaseLevel(9))
console.log(increaseLevel(a))
```

- `else` Syntax:
```
if (condition){
    // Block of code to be executed if the condition is true.
} else {
    // Block of code to be executed if the condition is false.
}
```

- `else` Code: 
```
function iHaveThePower(number) {
    if (number % 3) {
    /* Above our conditionn is checking to see if
    our `number` is even. The code below will multiply
    our `number` to the power of 3.
    */
        return Math.pow(number, 3) 
    } else {
    /* Our `else` is going to return that message if
    our `number` is odd.
    */
        return 'Not an even number'
    }
}
/* When we run the test the `3` will return the `else` message.
While the `2` will meet the condition and will return an `8`. */
console.log(iHaveThePower(3))
console.log(iHaveThePower(2))
```

- `else if` Syntax: 
```
if(condition1){
    // Block of code to be executed if `condition1` is TRUE.
} else if (condition2) {
    /* Block of code to be executed if `condition1` is FALSE but 
    `condition2` is TRUE */
} else {
    /* Block of code to be executed if `condition1` and `condition2` are
    both FALSE */
}
```

- `else if` Code: 
```
function greetings(time){
if (time < 10) {
/* Since we are sending through 19 
this first condition fails.
*/
    return "Good morning";
} else if (time < 20) {
/* Since we are sending through 19
this second condition will be true.
*/
    return "Good day";
} else {
/* Since the second condition was true 
This `else` did not execute but will if a 
`time` 20 or higher is sent through.
*/
    return "Good evening";
}
}
/* The `19` will meet the requirements for our
second condition.
*/
console.log(greetings(19))
```

- `switch` Syntax: 
```
switch(expression) {
    case x:
      // code block
    break;
    case y:
      // code block
    break;
    default:
      // code block
}
```

- `switch` Code: 
```
let a = 2 + 2;

switch (a) {
/* Here the switch starts to compare a from the 
first case variant that is 3. The match fails. */
case 3:
    alert( 'Too small' );
    break;
/* Then 4. That’s a match, so the execution starts 
from case 4 until the nearest break. */
case 4:
    alert( 'Exactly!' );
    break; /* This is the nearest break where our code stops */

case 5:
    alert( 'Too large' );
    break;

default:
    alert( "I don't know such values" );
}
```



## FOR, FOR EACH, AND WHILE LOOPS
* Loops - Loops are used if you want to run the same code over and over again usually checking for each item in an array.

* `for` - Used to loop through a block of code a number of times.

* `forEach` - This method calls a function once for each element in an array, in order.

* `while` - this method will loop through a block of code only while a specified condition is true.

* `do while` - This loop iterates at least once and reiterates as long as the condtion is true.

* Code Examples:
- `for` Syntax: 
```
for(/*statement 1; statement 2; statement 3 */){
    // Block of code to be executed.
}
```

- `for` Code: 
```
function sayHiToJim(listNames){
/* This `for` loop is checking every item inside 
out 'listNames' parameter */
    for(let i = 0; i < listNames.length; i++){
        if (listNames.includes('Jim')) {
        /* This `if` statement is saying if our `for`
        loop finds a 'Jim' send the message "Hi Jim"*/   
            return 'Hi Jim'
        } else {
        /* This `else` statement is saying if our `for`
        loop found anything other than 'Jim' its going to 
        send out a message saying "Ignoring 'name'"*/
            return listNames.forEach(element => {
                console.log('Ignoring' + element)
            });
        }
    }
}
/* This console.log will return "Hi Jim"*/
console.log(sayHiToJim(['Jane', 'Linda', 'Jim']))
/* While this one will return "Ignoring Jane" and "Ignoting Linda"*/
console.log(sayHiToJim(['Jane', 'Linda']))
```

- `forEach` Syntax: 
```
arr.forEach(callback(currentValue [, index [, array]])[, thisArg])
```

- `forEach` Code: 
```
const letterGrade = ["H", "G", "F", "E", "D", "C", "B", "A"]

function showLetterGrades(letters) {
    //We only want A, B, C, D and F to appear.
    if (letters == "E" || letters == "H" || letters == "G") {
        /* this `if` statement says if the `letters` parameter
        has an "E", "H" or "G" return nothing */ 
        return ""
    } else {
        console.log(letters)
    }
}
/* `letterGrade` is the array we want our function to loop through.*/
letterGrade.forEach(showLetterGrades)
/* We wrote our `showLetterGrades` function and what its supposed to 
do above and now we are sending that code through our array using the 
`forEach()` and our output is [A, B, C, D, F] as expected.*/
```

- `while` Syntax:
```
while (condition) {
   /* Block of code to be executed */
}
```

- `while` Code: 
```
let number = 1

/* Now our `while` condition that needs to be true
says that our number variable has to be less than 8 */
    while (number < 8){
    /* If the condition is true then our 
    statement is saying to add 1 to `number` changing
    the value of it. */
        number++

    /* Our statement will stop adding 1 once it reaches
    8 because each time we add 1 we are changing the value
    of `number` and our condition says we can only add if `number` is
    less than 8. */
    }
console.log(number)
```

- `do while` Syntax:
```
do {statement}
while (condition);
```

- `do while` Code: 
```
/* Here we made variable equaled to 20*/
let amount = 20
    do {
    /* Our `do` statement will add 1 
    onto our `amount` varriable even though
    it does not meet our condition because
    20 is NOT less than 19. */
        amount++
    }
    while (amount < 19)
    /* After our `do` statement the current value of our 
    amount variable is 21 and since our condition 
    requires amount to be less than 19 our condition is
    false and WILL NOT add 1 to 'amount' anymore.*/

    /* If you were to set `amount` to equal any number lower
    than 19 it would run the same as the previous `while`
    example. */
console.log(amount)
```



## MAP, REDUCE AND FILTER
* `map` - This method creates a new array with the results of calling a function for every array element.

* `reduce` - Will execute a provided function for each value of the array (from left-to-right).

* `filter` - Used to create an array filled with all array elements that pass a test.

* Code Examples: 
- `map` Syntax: 
```
array.map(function(currentValue, index, arr), thisValue)
```

- `map` Code:
```
/* This function removes the first letter
of a string within an array. */
function reverseErase(array){
    /* Our `.map` is going to cycle through everything
    in the array and create a new array containing 
    our changes. */
    return array.map(x => x.substring (1))
    /* the `.substring` method removes the first letter
    in a string.*/
}
/* Sending through this array will give us
`[ 'pple', 'innamon', 'corn', 'read' ]` */ 
console.log(reverseErase(['Apple', 'Cinnamon', 'Acorn', 'Bread']))
```

- `reduce` Syntax: 
```
array.reduce(function(total, currentValue, currentIndex, arr), initialValue)
```

- `reduce` Code: 
```
/* This function subtracts all numbers within an array */
function priceTotal(numbersInArray){
    /* We've created a varriable called `results`
    and set it to equal our `reduce` function. */
    let result = numbersInArray.reduce(function (array,total){
        /* Now we do the `reduce` our `numbersInArray` parameter
        and our return statement will subtract every number in our array 
        from eachother */
        return array - total
    })
    /* Here we return our `result` variable. */
        return result 
} 
/* Sending through the array will give us 30 as expected. */
console.log(priceTotal([100,50,20]))
```

- `filter` Syntax:
```
array.filter(function(currentValue, index, arr), thisValue)
```

- `filter` Code:
```
let burger = ['Top bun', 'Lettuce', 'Tomato', 'Onion', 'Cheese', 'Bottom bun']
/* This function is supposed to remove `Tomato` from our `burger` array. */
function holdTheTomatoes(ingredients){
    /* Here we set our `filter` fuction to this new variable
    `changedBurger` */
    let changedBurger = ingredients.filter((requestedIngredients) => {
        /* Now we filer through our `ingridients` parameter.
        now within our filter function we have this `requestedIngredients`
        parameter. */
        return requestedIngredients !== 'Tomato'
        /* Above we returned our `requestedIngredients` parameter and used the `!==` 
        to specify we don't want 'Tomato' to be sent back.*/
    })
    /* Below we send back our burger that now has no tomatos thanks to our `filter`.*/
    return changedBurger
}
/* And using the `console.log` out burger now looks like this
`[ 'Top bun', 'Lettuce', 'Onion', 'Cheese', 'Bottom bun' ]` */
console.log(holdTheTomatoes(burger))
```