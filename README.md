# Regular Expressions All In One

> MDN

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions

> Regular Expression 

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Cheatsheet


## Regular Expressions & Cheatsheet


https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Cheatsheet#Character_classes

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Character_Classes

## \w & \W

> 基本的拉丁字母，包括下划线

```js
\w === [A-Za-z0-9_]

\W === [^A-Za-z0-9_]
```

![](https://img2020.cnblogs.com/blog/740516/202008/740516-20200825111151210-735508996.png)


## \d & \D

> 阿拉伯数字

```js
\d === [0-9]

\D === [^0-9]
```

![](https://img2020.cnblogs.com/blog/740516/202008/740516-20200825111405036-1061956750.png)


## \s & \S

> 匹配单个空格字符，包括空格，制表符，换页符，换行符和其他Unicode空格。

```js
\s === [ \f\n\r\t\v\u00a0\u1680\u2000-\u200a\u2028\u2029\u202f\u205f\u3000\ufeff]

\S === [^A-Za-z0-9_]
```

![](https://img2020.cnblogs.com/blog/740516/202008/740516-20200825111546426-1438500083.png)

![](https://img2020.cnblogs.com/blog/740516/202008/740516-20200825111938606-1257744291.png)


## \b & \B

> 边界字符检测

```js
// 前，后
\b 

// 前，后
\B 

```

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Cheatsheet#Assertions

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Assertions

![](https://img2020.cnblogs.com/blog/740516/202008/740516-20200825112853169-48695023.png)


## Group

> 分组

```js

```

## Range

> 范围

```js

```

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Cheatsheet#Groups_and_ranges

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Groups_and_Ranges


## Quantifiers

> 量词

```js

```

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Cheatsheet#Quantifiers

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Quantifiers


## refs

https://regexper.com/


***

<div>
  <a href="https://info.flagcounter.com/QIXi">
    <img src="https://s11.flagcounter.com/count2/QIXi/bg_000000/txt_00FF00/border_FF00FF/columns_3/maxflags_12/viewers_0/labels_1/pageviews_1/flags_0/percent_1/" alt="Flag Counter" border="0">
  </a>
</div>


***

<blockquote style="display: flex; flex-flow: column; align-items: center; justify-content: center; text-align: center; border: none;">
  <h3><strong><span style="font-size: 16pt; color: #00ff00;">&copyxgqfrms 2012-<span data-uid="copyright-aside">2020</span></strong></span</h3>
  <p><span style="font-size: 18pt; color: #00ff00;"><strong>www.cnblogs.com 发布文章使用：只允许注册用户才可以访问！</strong></span></p>
</blockquote>

***
