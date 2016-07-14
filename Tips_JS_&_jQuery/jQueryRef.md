# jQuery tips, tricks and general use cases

We are going to use some examples based on simple DOM manipulation to illustrate some properties and important features of jQuery, so that when we need to use a specific functionality, we can use this file as an aggregated reference for everything jQuery.

jQuery allows you to have _interactive_ and _dynamic_ webpages via **DOM manipulation**. We shall see on later examples how we can have this interactivity. An HTML document is structured according to the Document Object Model, or DOM. It's by interacting with the DOM that jQuery is able to access and modify HTML.

The DOM consists of every element on the page, laid out in a hierarchical way that reflects the way the HTML document is ordered. Remember how we could think of the HTML document as a tree? You can think of the DOM the same way. Just as with an HTML document, elements in the DOM can have parents, children, and siblings.

## How jQuery works

jQuery uses a special syntax to denote that some elements are going to be manipulated and that jQuery is going to be used. It is also important to denote that jQuery **is** a cross-platform JavaScript library designed to simplify the client-side scripting of HTML, which means that, jQuery **is** javascript with some added properties, and its code file needs to be linked to the HTML in the same way a "normal" js file does.

```javascript
$(document).ready(function() {
    //Perform some actions
});
```
