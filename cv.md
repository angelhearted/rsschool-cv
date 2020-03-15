# CV


Name: **Nikita Skrebets**

Email: my-email@some-email-service.ru

Telegram: some-telegram-account


## Summary

For the last 10 years I have been working as a QA Engineer and now I would like to get a job of a frontend developer, as it fascinates me and gives a lot of possibilities to grow.

Have been working with JS (ES6) for 3 years in previous company while creating automation testing framework.

What is important for me is dive into atmosphere where I can learn swiftly, be responsible for ambitious goals and ask sometimes for a helping hand.

## Skills

JavaScript (ES6), Vue.js (beginner), ESLint, npm (beginner); HTML, CSS; SQL (basics)

## Code examples

A 5-kyu kata [solution](https://www.codewars.com/kata/550f22f4d758534c1100025a)

```javascript
function dirReduc(arr) {
  const areOpposite = (a, b) => a === 'NORTH' && b === 'SOUTH'
    || a === 'SOUTH' && b === 'NORTH'
    || a === 'WEST' && b === 'EAST'
    || a === 'EAST' && b === 'WEST';

  for (let i = 1; i < arr.length; i++) {
    if (areOpposite(arr[i - 1], arr[i])) {
      arr.splice(i - 1, 2);
      i = i > 1 ? i - 2 : i - 1;
    }
  }
  
  return arr;
}
```

## Experience

10 years as QA Engineer.

* Created JS test framework from scratch, which had ~15 000 lines of code in the end
* Automation tests development in JS, Java, C# (regular duties included at least 50% time of manual testing)
* Solving puzzles in codewars, codingame.com

## Education

Specialist degree in Specialized computer systems (2009)

A Udemy course on Vue.js from Maximilian Schwarzmüller (in progress)

RS School course of JavaScript

ICAgile cetrification (2011)

## English

Though I don't have any cetrification, can talk almost fluelently.

Worked 4+ years as outsourcer for British and American companies with tight communication, using both voice and text.
