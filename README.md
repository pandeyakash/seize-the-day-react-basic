# React vs. Traditional JavaScript DOM Manipulation

## Introduction

This project demonstrates the basic usage of React to create and render a simple paragraph element with the text "Seize the day" into a web page. The purpose is to illustrate the differences between traditional DOM manipulation using JavaScript and React's approach to handling the DOM.

## Traditional JavaScript DOM Manipulation

In traditional JavaScript, manipulating the DOM involves directly interacting with the DOM API to create, update, and remove elements. Here’s a basic example:

```javascript
// Traditional JavaScript to create a paragraph and append it to a div with id 'root'
const root = document.getElementById("root");
const paragraph = document.createElement("p");
paragraph.textContent = "Seize the day";
root.appendChild(paragraph);
```
