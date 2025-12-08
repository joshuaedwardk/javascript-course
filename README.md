Ended at Booleans: https://youtu.be/EerdGm-ehJQ?t=8645MadaZ23NHiC-CWYQpuXyWVZ


# ENDED [https://youtu.be/EerdGm-ehJQ?t=11409] Section 6

# Order of Operation End List
1. (...)
2. * /
3. + -
4. [Comparison Operators](#ComparisonOperators)


# Episode 4
 Variable Re-Assignment Shortcuts
    += 2 | variable = variable + 2
    -= 2 | variable = variable - 2
    *= 2 | variable = variable * 2
    /= 2 | variable = variable / 2
    ++   | variable = variable + 1
    --   | variable = variable - 1


# Episode 5
//Syntax rulesVariable name restrictions
// 1. can't use special work: let (can use let1, let2)
// 2. can't start with a number
// 3. can't use special characters except ($ _) 

//Syntax rules for Re-assigning a value to a verable
// 1. Do not use "Let" when re-assigning (let variable1 = 5; would cause a error)

/* camelCase = standard for JS */

# Episode 6
## project website [https://supersimple.dev/projects/booleans/] & [https://supersimple.dev/projects/rock-paper-scissors/]

## variables
const - cannot change always default
let - can change 2nd choice
var - outdate


### Syntax rules for Boolean do not surround with ' '


## type of

console.log(typeof ) returns data type to us
1. string
2. number
3. boolean
4. bigint
5. symbol
6. null
7. undefined

typeof "John"         // Returns string
typeof ("John"+"Doe") // Returns string
typeof 3.14           // Returns number
typeof 33             // Returns number
typeof (33 + 66)      // Returns number
typeof true           // Returns boolean
typeof false          // Returns boolean
typeof 1234n          // Returns bigint
typeof Symbol()       // Returns symbol
typeof x              // Returns undefined

## <a name="ComparisonOperators">Comparison Operators</a>
* > Greater than
* < Less than
* >= greater than or equal to
* <= less than or equal to
* === equal to
* !== not equal to

#### Math.random
console.log(Math.floor(Math.random() * 10 / 3)) [https://josephcardillo.medium.com/using-math-random-in-javascript-c49eff920b11]

### Logical Operators
Let us combinme boolean values

#### OR Operator ||

// Logical And Opperator   
console.log(true && false);
console.log(0.2 >= 0 && 0.2 < 1 / 3);

/* OR Operator || Checks if at least 1 side is true */
console.log(true || false);

/* Not Operator ! It flips the operator */
console.log(!true);

## Scope - limits where variable exists
### Any variable we create {....}
### Will only exist inside the {....}
Scopes help us avoid naming conflicts

Doesnt work:
  const randomNumber = Math.random();
    if (randomNumber >= 0 && randomNumber < 1 / 3) {
        const computerMove =  'Rock';
    } else if (randomNumber >= 1 / 3 && randomNumber < 2 / 3) {
        const computerMove = 'paper';
    } else if (randomNumber >= 2 / 3 && randomNumber < 1) {
        const computerMove = 'scissors';
    }

    console.log(computerMove);
    ">

    /*const age = 30;

    if (age >= 16) {
        console.log('I AM OLD');
        console.log('GREAT');
    }
    else if (age >= 14) {
        console.log('TRY HARDER');
    }
    else {
        console.log('I AM A CHILD');
    }*/

## Truthy & Falsey
This wont show it behaves as a false. 
if (0) {
    console.log('truthy');
}

## Falsy values:
* false
* 0
* ''
* NaN
* undefined
* null

Any value not on the falsy list is a truthy.

## Chapter 7 Done - will add notes later

## Chapter 8 Objects [Youtube Link](https://youtu.be/EerdGm-ehJQ?t=15682)

