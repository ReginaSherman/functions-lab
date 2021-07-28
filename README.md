![ga logo](https://camo.githubusercontent.com/6ce15b81c1f06d716d753a61f5db22375fa684da/68747470733a2f2f67612d646173682e73332e616d617a6f6e6177732e636f6d2f70726f64756374696f6e2f6173736574732f6c6f676f2d39663838616536633963333837313639306533333238306663663535376633332e706e67)

# Functions Lab!

<hr>
Title: Problem solving<br>
Created by: GA Instructional Staff<br>
Topics: Problem solving with functions<br>
<hr>

## Setup:

Pull up your handy dandy CodePen editor and go to town! 

## Problem solving

Solve the following problems.

Problem solving means taking things **one step at a time**, and often going **beyond what you already know**. Neither of these are easy.

Taking things one step at a time means stopping, taking a breath, evaluating your thoughts, testing what you have, and organizing your next step.

Often, you won't yet have the tools to solve a problem. This happens in the real world, and it means doing research. 

These two things are crucial in the mindset of a developer and they are why developers get paid the dollaroonies.

<br>
<hr>

## Go Time

### printGreeting

Write a function called `printGreeting` with a parameter `name` that returns a greeting with the argument **interpolated** into the greeting.

```javascript
console.log(printGreeting("Slimer"));
```

> `=> Hello there, Slimer!`

<hr>

### reverseWordOrder

Write a function `reverseWordOrder` that accepts a single argument, a string. The function should return a string with the order of the words reversed. Don't worry about punctuation.

```javascript
console.log(reverseWordOrder("Ishmael me Call"));
```

> `=> "Call me Ishmael"`


```js
console.log(reverseWordOrder("I use Lâncome on my comb"));
```

> `=> "comb my on Lâncome use I"`


<hr>

### calculate

Write a function called `calculate`.

This function should take three arguments: two numbers and a string.

Name the parameters `num1`, `num2`, and `operation`.

If if the function is called with the third argument as "add", it should return the sum of num1 and num2.

If if the function is called with the third argument as "sub", it should return return `num1` minus `num2`.

Do the same thing for multiplication "mult", division "div", and exponent "exp" (where `num2` is the exponent of `num1`).

```javascript
console.log(calculate(4, 3, "sub"));

=> 1
```

```javascript
console.log(calculate(4, 3, "exp"));

=> 64
```

<hr>

### printConsecutives
 
Write a function `printConsecutives` that can take an array of any length, and print groups of three numbers where three consecutive numbers increase by 1.

```javascript
printConsecutives([1, 2, 3, 9, 8, 0, 44, 45, 46, 2, 9]);
```
> => 1 2 3
> 
> => 44 45 46

```javascript
printConsecutives([0, 0, 0, -3, -2, -1, 0, 1, 2, 3]);
```

> -3 -2 -1
> 
> -2 -1 0
> 
> -1 0 1
> 
> 0 1 2
> 
> 1 2 3

<br>
<hr>

### letterReverse

Write a function `letterReverse` that accepts a single argument, a string. The function should maintain the order of words in the string but reverse the letters in each word. Don't worry about punctuation.

```javascript
console.log(letterReverse("Luke I am your father"));
```
> => "ekuL I ma ruoy rethaf"

```javascript
console.log(letterReverse("Aren't you a little short for a storm trooper"));
```

> => "t'nerA uoy a elttil trohs rof a mrots repoort"

<br>
<hr>
<hr>

## Hungry for more?

### Functions + loops: a special partnership 

Write a function that, when called ("call" = "invoke") creates a string that represents an 8×8 grid, using newline characters to separate lines. At each position of the grid there is either a space (a "white square") or a `#` character (representing a black square). Hence, the characters should form a chessboard.

Calling your function should print something like this:

```
 # # # #
# # # # 
 # # # #
# # # # 
 # # # #
# # # # 
 # # # #
# # # #
```

### 7. Modify it to make any size grid.

When you have a function that generates this pattern, modify it to take a parameter `size`.  Make the function work for any size, outputting a properly formatted grid of the given width and height.  If it helps you to have this set. The very first square should always be white.

Remember to give it a nice **semantic** name

> This problem was adapted from one in [Eloquent Javascript](http://eloquentjavascript.net/02_program_structure.html#p_1pkxSCSkVg) so hopefully you've already seen it because you've been reading Eloquent Javascript. If you haven't yet, read the first 3 chapters (this reads great on a phone, and if you take transit, this is a great thing to read on the train/bus on your way in).  Homework will be assigned soon. 

<hr>

### 8. Variable number of arguments

Modify `calculate` above so that it continues to work as specified in question 3, but also lets a user get the square root of a number by specifying only 2 parameters: the number they want the square root of as the first parameter, and "sqrt" as the second parameter.

Click "Details" below for a hint:

<details>
Hint: use `typeof` 
</details>

## Hungry for More?
Get started on the afternoon lab!
