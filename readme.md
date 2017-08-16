![github front end develeper interview questions and answers teaser](https://webman.pro/assets/img/main/webman-front-end-interview-questions-answers-github.jpg)

# Front End Interview Questions and Answers
This information is intended for the potential Front End Developer candidates.
The following list include a basic theoretical and code questions.

I hope, that my experience and experience of other developers will help you to get the best interview results.

## List of Content
1. [Common interview questions](#common-interview-questions)
1. [Common technical interview questions](#common-technical-interview-questions)
1. [HTML](#html-interview-questions)
1. [CSS](#css-interview-questions)
1. [Javascript](#javascript-interview-questions)
1. [Javascript Coding](#javascript-coding-questions)
1. [React interview questions](#react-interview-questions)
1. [Funny Questions](#funny-questions)
1. [Contributing](#contributing)

## Common interview questions
1. What was the most interesting solution did you implemented at the last project? 
1. What is the last book you read?
1. How big your team ever was?
1. Have you ever worked in [Agile, Scrum or Kanban](https://www.smartsheet.com/agile-vs-scrum-vs-waterfall-vs-kanban) environments?
1. What developers of Front End community do you know?
1. What is 'Gangs of four'?

## Common technical interview questions
1. What is [REST](http://www.restapitutorial.com/)? - [restcookbook](http://restcookbook.com/)
1. What is the difference between PUT and PATCH methods in REST? - [answer](https://stackoverflow.com/questions/21660791/what-is-the-main-difference-between-patch-and-put-request)
1. Tell about the differences between [websockets](https://developer.mozilla.org/en-US/docs/Web/API/WebSocket), long polling and [SSE](https://developer.mozilla.org/en-US/docs/Web/API/Server-sent_events/Using_server-sent_events). - [answer](https://stackoverflow.com/questions/11077857/what-are-long-polling-websockets-server-sent-events-sse-and-comet)
1. What is CORS? - [answer](https://www.maxcdn.com/one/visual-glossary/cors/), [answer](https://developer.mozilla.org/en-US/docs/Web/HTTP/Access_control_CORS)
1. What is the main things you can do to increase page speed loading? - [answer](https://www.crazyegg.com/blog/speed-up-your-website/)
1. Progressive enhancement vs graceful degradation. What is the difference? - [answer](https://www.w3.org/wiki/Graceful_degradation_versus_progressive_enhancement)
1. Do you use [Grunt](https://gruntjs.com/), [Gulp](https://gulpjs.com/), [Webpack](https://webpack.github.io/) or Browserify in your projects?
1. What do you know about "60fps"? What way to achieve this? - [answer](https://github.com/vasanthk/browser-rendering-optimization)
1. What is the difference between layout, painting and compositing? - [answer](https://developers.google.com/web/fundamentals/performance/rendering/?hl=en)

## HTML Interview Questions
1. Could you list main HTML5 tags? - [answer](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
1. What does mean optional closing tag? - [answer](https://www.w3.org/TR/REC-html40/index/elements.html) 
1. When and how to preload resources? - [answer](https://medium.com/reloading/preload-prefetch-and-priorities-in-chrome-776165961bbf)

## CSS Interview Questions
1. What is different between mobile first and desktop first - [answer](https://codemyviews.com/blog/mobilefirst )?
1. Which of [those](https://jsfiddle.net/thisman/9o8s2bdk/) selectors has the highest specificity. What color will be applied to the paragraph?
1. What pseudo-class `:root` refer to?
1. What preprocessor do you use ([Sass](http://sass-lang.com/), [Less](http://lesscss.org/))?

## Javascript Interview Questions
1. Who is the author of JavaScript Language? - [article](https://auth0.com/blog/a-brief-history-of-javascript/)
1. What is the JavaScript Event Loop? - [answer](http://altitudelabs.com/blog/what-is-the-javascript-event-loop/), [Philip Roberts answer](https://www.youtube.com/watch?v=8aGhZQkoFbQ&t=1244s)
1. What is the Event Delegation? - [answer](https://davidwalsh.name/event-delegate), [example](https://jsfiddle.net/thisman/h2eqfsx6/)
1. What is the difference between e.target and e.currentTarget? - [answer](https://developer.mozilla.org/en-US/docs/Web/API/Event/currentTarget), [example](https://jsfiddle.net/thisman/gkdeocd6/)
1. What patterns do you know and successfully use in JavaScript?
1. What is [`Window.postMessage()`](https://davidwalsh.name/window-postmessage) and where it can be used? - [answer](https://developer.mozilla.org/en-US/docs/Web/API/Window/postMessage)

## Javascript Coding Questions
* Write a `pipefy` function where a string received is returned, but with the `|` character between each character. Make it possible to execute function in this way: `'javascript'.pipefy()`. - [answer](https://jsfiddle.net/thisman/6ynaf3ot/)
* write a [currying function](https://medium.com/@adambene/currying-in-javascript-es6-540d2ad09400) that return sum of two numbers.
* Write a [factorial](https://www.mathsisfun.com/numbers/factorial.html) function without [side effect](https://stackoverflow.com/a/8129277/5513804). [answer](https://jsfiddle.net/thisman/8v0h5oLq/)
```js
// Code below must return true
alert(factorial(3) === 6 && factorial(0) === 1);
```
* Which line of the below code will be executed with an error. Why?
```js
10 .toString();
(10).toString();
10..toString();
```
* What is the order of alerts?
```js
setTimeout(function(){
    alert('gorilla');
    setTimeout(function(){
        alert('classical inheritance')
    }, 0);
    alert('drumroll');
}, 0);

alert('banana');
```
* What is the result after code execution: 1, 2 or 3?
```js
var x = 1;
var foo = {
  x:2,
  bar: function() {
    x = 3;
    return this.x;
  }
}
var run = foo.bar;

alert(run);
```

* What below code will return: true or false. What does each part of code return? 
```js
new String('a') instanceof String && 'b' instanceof String;
```

## React interview questions
1. What happens when you execute `setState()` in the `render()` method?
1. What is the difference between 'smart and dummy' components?
1. How to create higher order component?
1. Tell about React in the SEO context.
1. Why rendering of React Components in the custom `<div id="app">` is good practice than simple to the `<body>`?
1. What does mean "Isomorphic React Application"? - [answer](https://www.smashingmagazine.com/2015/04/react-to-the-future-with-isomorphic-apps/)

## Funny Questions
1. Do you like parties?
2. Do you know that we have a dress code? (asked as a joke)

## Contributing
Contributions, questions and comments, pull requests are all welcome.
**Note**: if you want to change a structure, please open an issue and we will discuss it, but if you have interesting questions or answers, please make pull request.

