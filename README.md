# web-components-example
web components with HTML imports, template and shadow dom

## Idea
I wanted to show how to create components without any frameworks. Bringing us back to plain html, js and css and still be able to reuse components where ever.

## Solution

### shadow DOM
[MDN web docs](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_shadow_DOM)

Allows us to create our own HTML elements.

### template
[MDN web docs](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/template)

template tag is used to keep our class clean. Not inlining all the HMTL code in a string or using document.createElement for every tag.

### HTML Imports
[MDN web docs](https://developer.mozilla.org/en-US/docs/Web/Web_Components/HTML_Imports)

This is used to keep the component in it's own separate file. Not having to polute our index file with a template tag. Note: HTML Imports will for the moment not be implemented in Firefox and might be removed in Chrome.

## Run
`npm i -g watch-http-server`

`watch-http-server`

Open `localhost:8080` in Chrome

## Demo
[GitHub Pages](https://gautemo.github.io/web-components-example/) in Chrome