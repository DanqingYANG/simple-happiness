# Live demo

Changes are automatically rendered as you type.

* Implements [GitHub Flavored Markdown](https://github.github.com/gfm/)
* Renders actual, "native" React DOM elements
* Allows you to escape or skip HTML (try toggling the checkboxes above)
* If you escape or skip the HTML, no `dangerouslySetInnerHTML` is used! Yay!

## 

## HTML block?



<blockquote>
  This blockquote will change based on the HTML settings above.
</blockquote>



## How about some code?



```js
var React = require('react');
var Markdown = require('react-markdown');

React.render(
  <Markdown source="# Your markdown here" />,
  document.getElementById('content')
);
```



## Tables?



Use [`remark-gfm`](https://github.com/remarkjs/react-markdown#use) to support tables, strikethrough, tasklists, and literal URLs.
These features **do not work by default**.

| Feature | Support      |
| :-----: | ------------ |
| tables  | `remark-gfm` |

~~strikethrough~~

- [ ] task list



* a
  * b
    * c