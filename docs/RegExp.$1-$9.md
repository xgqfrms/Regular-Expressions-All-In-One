# RegExp.$1-$9

> regex var

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/n

The legacy RegExp $1, $2, $3, $4, $5, $6, $7, $8, $9 properties are static and read-only properties of regular expressions that contain parenthesized substring matches.

旧的 RegExp $1, $2, $3, $4, $5, $6, $7, $8, $9 属性是包含括号内的子字符串匹配项的正则表达式的静态和只读属性。


```js
var reg = /(\w+)\s(\w+)/;
var str = 'John Smith';

str.replace(reg, '$2, $1');
// "Smith, John"

RegExp.$1;
// "John"
RegExp.$2;
// "Smith"

```

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Groups_and_Ranges


> [] range

> () group, $1-$9

```js
const log = console.log;

const aliceExcerpt = 'The Caterpillar and Alice looked at each other';
const regexpWithoutE = /\b[a-df-z]+\b/ig;

log(aliceExcerpt.match(regexpWithoutE));
// ["and", "at"]

const imageDescription = 'This image has a resolution of 1440×900 pixels.';
const regexpSize = /([0-9]+)×([0-9]+)/;

const match = imageDescription.match(regexpSize);
log(`match =`, match);
// ["1440×900", "1440", "900"]

log(`Width: ${match[1]} / Height: ${match[2]}.`);
// "Width: 1440 / Height: 900."

```
