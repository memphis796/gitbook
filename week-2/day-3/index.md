# Wednesday March 9

## Daily JS * 2

### Function Arguments

When looking at variables or arguments inside of functions, if they are created in the function itself just rename it `functionName_variableName` so that it is clear that these variables are DIFFERENT than variables that exist outside of that function.

```js
var x = 2;

var y = function(foo) {
  return foo;
};

function z(z_foo) {
  return z_foo + x;
}

/* Fat arrow same as
var a = function(x = 9, y = 10) {
  return x * y;
};
 */
var a = (x = 9, y = 10, z = 2) => {
  return x * y;
};

var b = (cb, value) => {
  return cb(value);
};


console.log(y(12)); // 12
console.log(y('hello')); // "hello"
console.log(foo); // undefined
console.log(y(x)); // 2
console.log(z('Five')); // "Five2"
console.log(a(15, 2)); // 30
console.log(x); // 2
console.log(a()); // 90
console.log(a(41)); // 410
console.log(b(y, x)); // 2
```

## Interruptions

* None

## Standups

* What is going well?
* What is not going well (what are you struggling with)?
* What's something you'd like to share not about code?
* What's something you've learned

### Common Wins

* Faster Typing
* HTML
* Some Flexbox
* Take **Meaningful** Breaks
* Think "Out to In"
* Slowly Making Sense
* More Comfort in Code
  - Seems like 2 days ago is starting to click

### Common Struggles

* "Aha" moments kick you in the butt
* Sleep & Energy
* **Starting Projects**
* Backlog
* Time Management
* Positioning
  - Box Sizing
  - Position
  - Float
  - Flex
* Slowly Making Sense

## Topics

* Focus and Time Management
  - [Tab Wrangler](https://chrome.google.com/webstore/detail/tab-wrangler/egnjhciaieeiiohknchakcodbpgjnchh?hl=en)
  - [Paradox of Choice](https://www.ted.com/talks/barry_schwartz_on_the_paradox_of_choice?language=en)
  - [Music Playlists](../../resources/playlists.html)
* [Tips for Starting](../../resources/getting-started.html)
* When to Commit?
* [Selector Specificity](specificity.html)
* [BEM](bem.html)
* Refactoring - Scott Pilgrim ଘ(੭*ˊᵕˋ)੭* ̀ˋ ɪɴᴛᴇʀɴᴇᴛs
* [Layout Planning & Components](components.html)
* [Semantic Markup](semantic-markup.html)

## Inspiration

### [Initial Site](http://pricing-example.surge.sh)

### Mockups

* Desktop

![Desktop](https://github.com/theironyard-frontend-nashville/assignments/blob/cohort2/week02/wed/breakpoint4.png?raw=true)

* Phone

![Phone](https://github.com/theironyard-frontend-nashville/assignments/blob/cohort2/week02/wed/breakpoint1.png?raw=true)


## Exercise & Lesson Code

https://github.com/TIY-TN-FEE-2016-spring/02-03-pricing-table

## Lab

## Homework

https://github.com/TIY-TN-FEE-2016-spring/assignments/tree/master/07-pricing-page
