# Vue.JS-CodeHighlighter
A simple code highlight render component based on highlight.js

##Credits
JS - [highlight.js](https://highlightjs.org/) (dependency)

CSS - Atom One Dark by Daniel Gamage 

##Usage
Props: 
* code - *String* - The code you wish to highlight
* language - *String* - which language to highlight, **javascript** by default
* wrap - *Boolean* - whether break lines in code or not, **false** by default

Example:

```<Highlight code="console.log(`Hello, my name is Dana and I like ${favouritePet}!`)" />```

```<Highlight language="html" code="<p>Such a <strong>sunny weather</strong> today!</p>" />```
