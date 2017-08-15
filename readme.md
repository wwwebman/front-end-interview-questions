# Front-End Interview Questions
This information is intended for the potential Front End Developer candidates.
The following list include a basic theoretical and code questions. 

## List of Content
1. [Common interview questions](#common-interview-questions)
1. [Common technical interview questions](#common-technical-interview-questions)
1. [HTML](#html-interview-questions)
1. [CSS](#css-interview-questions)
1. [Javascript](#javascript-interview-questions)
1. [Javascript Coding](#javascript-coding-questions)

## Common interview questions
1. What was the most interesting solution did you implemented at last project? 
1. What the last book you read?
1. How big your team was?
1. Have you ever worked in [Agile, Scrum or Kanban](https://www.smartsheet.com/agile-vs-scrum-vs-waterfall-vs-kanban)) environments? Talk more about..

## Common technical interview questions
1. What is [REST](http://www.restapitutorial.com/)? - [more](http://restcookbook.com/)
1. What is the difference between PUT and PATCH methods in REST? - [answer](https://stackoverflow.com/questions/21660791/what-is-the-main-difference-between-patch-and-put-request)
1. What is CORS? - [answer](https://www.maxcdn.com/one/visual-glossary/cors/), [answer](https://developer.mozilla.org/en-US/docs/Web/HTTP/Access_control_CORS)
1. What the main things you can do to increase page speed loading? - [answer](https://www.crazyegg.com/blog/speed-up-your-website/)
1. Progressive enhancement vs graceful degradation. What is the difference?

## HTML Interview Questions

## CSS Interview Questions
1. What different between mobile first and mobile last?
1. Which of [those](https://jsfiddle.net/thisman/9o8s2bdk/) selectors has the highest specificity. What color will be applied to the paragraph?

## Javascript Interview Questions
1. What is the JavaScript Event Loop? - [answer](http://altitudelabs.com/blog/what-is-the-javascript-event-loop/), [Philip Roberts answer](https://www.youtube.com/watch?v=8aGhZQkoFbQ&t=1244s)
1. What is the Event Delegation? - [answer](https://davidwalsh.name/event-delegate), [example](https://jsfiddle.net/thisman/h2eqfsx6/)
1. What is the difference between e.target and e.currentTarget? - [answer](https://developer.mozilla.org/en-US/docs/Web/API/Event/currentTarget), [example](https://jsfiddle.net/thisman/gkdeocd6/)

## Javascript Coding Questions
* Write a `pipefy` function where a string received is returned, but with the `|` character between each character. Make it possible to execute function in this way: `'javascript'.pipefy()`. - [answer](https://jsfiddle.net/thisman/6ynaf3ot/)
* Which line of the below code will be executed with an error. Why?
```js
10 .toString();
(10).toString();
10.toString();
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
* Write a [factorial](https://www.mathsisfun.com/numbers/factorial.html) function without [side effect](https://stackoverflow.com/a/8129277/5513804). `alert(factorial(3) === 6 && factorial(0) === 1)` must return true. - [answer](https://jsfiddle.net/thisman/8v0h5oLq/)