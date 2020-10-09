# Regular_Expressions

> [^\w], [\W], [^A-Za-z]

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Character_Classes

> group

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Groups_and_Ranges


```js
  const str = city.replace(/[^A-Za-z]/ig, ``).toLowerCase();
  // const str = city.replace(/[\W]/ig, ``);
  // const str = city.replace(/[^\w]/ig, ``);

```