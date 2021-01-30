<div align="center">
  <a href="https://webman.pro">
    <img src="https://raw.githubusercontent.com/wwwebman/wwwebman/master/wwwebman.svg" width="50px" alt="webman.pro">
  </a>
  <br />
  <h1> Front End Interview Questions and Answers</h1>
  <a href="CONTRIBUTING.md">
    <img src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat" alt="Contributions">
  </a>
  <a href="https://github.com/wwwebman/gulp-webpack-starter/blob/master/CONTRIBUTING.md">
    <img src="https://img.shields.io/github/contributors/wwwebman/front-end-interview-questions.svg" alt="Contributors">
  </a>
  <a href="https://github.com/wwwebman/gulp-webpack-starter/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/mashape/apistatus.svg" alt="License">
  </a>
</div>
<br />

The goal is to give a candidate the possibility to test his/her knowledge before a real-world interview.
My experience and the experiences of other developers will help you get better interview results.

**Rock your interview! :rocket:**
___


## List of Content

1. [Common interview questions](#common-interview-questions)
1. [Common technical interview questions](#common-technical-interview-questions)
1. [HTML Interview Questions](#html-interview-questions)
1. [CSS Interview Questions](#css-interview-questions)
1. [Javascript Interview Questions](#javascript-interview-questions) ([junior](#js-junior), [middle](#js-middle), [senior](#js-senior))
1. [Javascript Coding Questions](#javascript-coding-questions)
1. [React interview questions](#react-interview-questions)
1. [Typescript interview questions](#typescript-interview-questions)
1. [Security](#security)
1. [Testing Questions](#testing-questions)
1. :tada: [Recruiting tasks](#recruiting-tasks)
1. [GIT](#git)
1. [Funny Questions](#funny-questions)
1. [Contribution](#contribution)

## Common interview questions

1. What was the most interesting solution you implemented during your last project?
1. What the latest programming book you've read.
1. How big is/was your team?
1. Have you ever worked in [Agile, Scrum or Kanban](https://www.smartsheet.com/agile-vs-scrum-vs-waterfall-vs-kanban) environments?
1. Which developers do you know in the Front End community?
1. Are you a team player?
1. What makes you a good developer?
1. What next skill do you want to improve?
1. What values can you bring to a new team?
1. What is the difference between imperative and declarative programming in JS? - [@blog](https://www.redotheweb.com/2015/09/18/declarative-imperative-js.html)

## Common technical interview questions

1. What is REST? - [@docs](https://restcookbook.com/)
1. What is the difference between PUT and PATCH methods in REST? - [@stackoverflow](https://stackoverflow.com/questions/21660791/what-is-the-main-difference-between-patch-and-put-request)
1. Talk about the differences between [websockets](https://developer.mozilla.org/en-US/docs/Web/API/WebSocket), long polling and [SSE](https://developer.mozilla.org/en-US/docs/Web/API/Server-sent_events/Using_server-sent_events). - [@stackoverflow](https://stackoverflow.com/questions/11077857/what-are-long-polling-websockets-server-sent-events-sse-and-comet)
1. What is CORS? - [@blog](https://www.maxcdn.com/one/visual-glossary/cors/), [@docs](https://developer.mozilla.org/en-US/docs/Web/HTTP/Access_control_CORS)
1. List the main things you can do to increase page speed loading? - [@blog](https://www.@blog/blog/speed-up-your-website/)
1. Progressive enhancement vs graceful degradation. What is the difference? - [@docs](https://www.w3.org/wiki/Graceful_degradation_versus_progressive_enhancement)
1. Do you use [Grunt](https://gruntjs.com/), [Gulp](https://gulpjs.com/), [Webpack](https://webpack.js.org/) or [Browserify](https://browserify.org/) in your projects?
1. What tools do you know or already use to improve your code?
1. What do you know about "60fps"? How can you achieve it? - [@github](https://github.com/vasanthk/browser-rendering-optimization)
1. What is the difference between layout, painting and compositing? - [@docs](https://developers.google.com/web/fundamentals/performance/rendering/?hl=en)
1. What is Web Components? - [@docs](https://developer.mozilla.org/en-US/docs/Web/Web_Components)
1. What is the difference between sessionStorage, localStorage and cookies? [@stackoverflow](https://stackoverflow.com/a/19869560/5513804)

## HTML Interview Questions

1. Could you list major HTML5 tags? - [@docs](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
1. What does an 'optional' closing tag mean? - [@docs](https://www.w3.org/TR/REC-html40/index/elements.html)
1. When and how to preload resources? - [@blog](https://medium.com/reloading/preload-prefetch-and-priorities-in-chrome-776165961bbf)
1. What is the difference between id and class? - [@blog](https://css-tricks.com/the-difference-between-id-and-class/)

## CSS Interview Questions

1. What is the difference between 'mobile first' and 'desktop first' - [@blog](https://codemyviews.com/blog/mobilefirst)?
1. Which of [these](https://jsfiddle.net/thisman/9o8s2bdk/) selectors has the highest specificity. What color will be applied to the paragraph?
1. What does the pseudo-class `:root` refer to?
1. What preprocessor do you use? ([Sass](https://sass-lang.com/) or [Less](https://lesscss.org/))

## Javascript Interview Questions

#### JS Junior

1. Who is the author of JavaScript Language?
1. What is the best book for learning JavaScript and why? - [@github](https://github.com/wwwebman/js-books-backpack)
1. What is the type of NaN? How to check if a value is NaN?
1. What the reason that `window.window === window` return true? - [@docs](https://developer.mozilla.org/pl/docs/Web/API/Window/window)
1. What is the outcome of the JavaScript calculation? `1/0 = ?`
1. What is hoisting? [@docs](https://developer.mozilla.org/en-US/docs/Glossary/Hoisting)
1. What is the difference between bubbling and capturing? - [@stackoverflow](https://stackoverflow.com/a/4616720/5513804)

#### JS Middle

1. What does `this` refer to? - [@blog](https://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/)
1. What is the JavaScript Event Loop? - [@blog](https://altitudelabs.com/blog/what-is-the-javascript-event-loop/), [@youtube](https://www.youtube.com/watch?v=8aGhZQkoFbQ&t=1244s)
1. What is the Event Delegation? - [@blog](https://davidwalsh.name/event-delegate), [@code](https://jsfiddle.net/thisman/h2eqfsx6/)
1. What is the difference between e.target and e.currentTarget? - [@docs](https://developer.mozilla.org/en-US/docs/Web/API/Event/currentTarget), [@code](https://jsfiddle.net/thisman/gkdeocd6/)
1. What is [`Window.postMessage()`](https://davidwalsh.name/window-postmessage) and where it can be used? - [@docs](https://developer.mozilla.org/en-US/docs/Web/API/Window/postMessage)
1. Is there any difference between Promises and callbacks? Which is better? - [@blog](http://callbackhell.com/),
1. What is recursion? When is the use of recursion useful in Javascript? - [@blog](https://medium.com/@dis_is_patrick/practical-uses-for-recursive-javascript-b8f142552f8b)
1. What do you hear about DRY, KISS, YAGNI? - [@blog](https://thefullstack.xyz/dry-yagni-kiss-tdd-soc-bdfu)
1. What do you know about optional chaining operators? What benefits does it bring? [@docs](https://www.typescriptlang.org/docs/handbook/release-notes/typescript-3-7.html#optional-chaining)

#### JS Senior

1. What patterns do you know and successfully use in JavaScript?
1. What is the problem throttling and debouncing are resolved? What is the core difference between them? - [@blog](https://medium.com/@_jh3y/throttling-and-debouncing-in-javascript-b01cad5c8edf)
1. What is SOLID? [@wiki](<https://en.wikipedia.org/wiki/SOLID_(object-oriented_design)>)
1. What is the difference between inheritance and composition? What do you prefer? Why? [@blog](https://hackernoon.com/javascript-functional-composition-for-every-day-use-22421ef65a10), [@blog](https://medium.com/front-end-hacking/classless-javascript-composition-over-inheritance-6b27c35893b1)

## Javascript Coding Questions

<details>
<summary>Write a `pipefy` function where a string received is returned, but with the "|" character between each character:</summary>

```js
pipefy();
```

[@code](https://jsfiddle.net/thisman/6ynaf3ot/)

</details>
<details>
<summary>Write a currying function that returns a sum of two numbers:</summary>

```js
sum(1)(2);
```

[currying function](https://medium.com/@adambene/currying-in-javascript-es6-540d2ad09400),

</details>
<details>
<summary>Write a factorialfunction without side effect:</summary>
	
```js
// Code below must return `true`.
alert(factorial(3) === 6 && factorial(0) === 1);
```

[factorial](https://www.mathsisfun.com/numbers/factorial.html),
[side effect](https://stackoverflow.com/a/8129277/5513804),
[@code](https://jsfiddle.net/thisman/8v0h5oLq/)

</details>

<details>
<summary>Which line of the below code will be executed with an error? Why?</summary>
	
```js
10 .toString();
(10).toString();
10..toString();
```
</details>
<details>
<summary>What is the order of alerts?</summary>

```js
setTimeout(function () {
  alert('gorilla');
  setTimeout(function () {
    alert('classical inheritance');
  }, 0);
  alert('drumroll');
}, 0);

alert('banana');
```

</details>
<details>
<summary>What is the result after code execution: 1, 2 or 3?</summary>

```js
var x = 1;
var foo = {
  x: 2,
  bar: function () {
    x = 3;
    return this.x;
  },
};
var run = foo.bar;

alert(run());
```

</details>
<details>
<summary>What below code will return: `true` or `false`. What does each part of code return?</summary>
	
```js
new String('a') instanceof String && 'b' instanceof String;
```
</details>
<details>
<summary>What the result of the following functions call? Is it the same?</summary>

```js
const a = function (obj, val) {
  obj.val = {
    a: 1,
    b: 2,
  };

  return obj;
};



const b = function (obj, val) {
  return (obj.val = {
    a: 1,
    b: 2,
  });
};

a({}, 'val');
b({}, 'val');
```

</details>
<details>
<summary>What would be the output of this code below?</summary>

```js
(function () {
  console.log(a, b);
  var a = 1;
  const b = 2;
})();
```

</details>
<details>
<summary>Which one of the function expression below would be the best choice for the `prototype-constructor` pattern (a, b, c)? Why?</summary>

```js
function Man(name) {
  this.name = name;
}
// a
Man.prototype.getName = function () {
  return this.name;
};
// b
Man.prototype.getName = function getName() {
  return this.name;
};
// c
Man.prototype.getName = () => {
  return this.name;
};
```

</details>
<summary>Implement normalizeCase() function that converts "HELLO worLD" to "Hello world".</summary>

```js
function normalizeCase(str) {
  // The magic happens here.
}
```

</details>

## React interview questions

### General

1. What is the difference between 'smart and dummy' components?
1. How to create higher order component?
1. What is the difference between hoc, Renders Props and hooks patterns?
1. Why it is a good practice to render React Components in `<div id="app"></div>` over `<body>`?
1. What does mean "Isomorphic React Application"? - [@blog](https://www.smashingmagazine.com/2015/04/react-to-the-future-with-isomorphic-apps/)
1. What happens when you execute `setState()` in the `render()` method?
1. What is difference between useState() and useRef()?
1. How do lifecycle methods correspond to hooks?
1. Is it okay to call hooks inside loops or conditions?
1. How do you handle errors in React?

### Redux

1. What is the difference between Mobx & Redux? - [@blog](https://www.robinwieruch.de/redux-mobx-confusion/)
1. What do you think about ajax request in reducer?
1. What architecture do you use to structure actions and reducers?
1. What is the difference between reducers and actions?
1. What is an action creator?
1. Is Redux still relevant in 2020? Can React context replace Redux?
1. What is middleware? Can you describe the use case where it can be used?
1. Have you used reselect? 


## Typescript interview questions

1. Talk about the differences between public, private, and protected class access modifiers? [@docs](https://www.typescriptlang.org/docs/handbook/classes.html#public-private-and-protected-modifiers)
1. What typescript features do you use/know?
1. What is a generic type? [@docs](https://www.typescriptlang.org/docs/handbook/generics.html)
1. What Typescript utility types do you use/know (Omit, Partial)? [@docs](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)

## Security

1. What are the most common types of web attacks? - [@blog](https://blog.sucuri.net/2014/11/most-common-attacks-affecting-todays-websites.html)

## Testing Questions

1. Explain the difference between unit tests and integration tests? - [@stackoverflow](https://stackoverflow.com/a/5357837/5513804)
1. Tell about TDD. What advantages or disadvantages of this concept you know? [@docs](https://en.wikipedia.org/wiki/Test-driven_development)
1. Which frameworks/platforms do you use for test you code?
1. List unit testing best practices principles. [@slides](https://www.slideshare.net/homespothq/unit-testing-concepts-and-best-practices)

## Recruiting tasks

1. [React user search](tasks/react-user-search)

## GIT

1. What is the main difference between `merge` and `rebase`? - [@blog](https://www.atlassian.com/git/tutorials/merging-vs-rebasing)

## Funny Questions

1. Do you like parties?
1. Do you know that we have a dress code?
1. Where do you see yourself in 5 years?

## Contribution

It would be cool to find your Front End interview question on our list. 
Check out the contributing [guide](CONTRIBUTING.md) to get started.

## License

MIT License, Copyright © 2017-present, [Dmytro Chumak](https://webman.pro).
See [LICENSE](./LICENSE) for more information.
