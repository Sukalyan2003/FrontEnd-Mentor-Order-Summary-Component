# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![Screnshot](./screenshot.png)




## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

This was my first venture into Webdev and I made the following notes.
1. Index.html is the main file where we write our code. Everything else is referenced by this file.
2. We can use `!` in Vscode to generate Boilerplate code using Emmet (built into Vscode).
3. For CSS selectors we do as follows
   ```CSS
   Selector{
   property : Value;
   }
   ```
   Where `Selector` should be replaced by any tags we need. For eg:
   ```CSS
   h1{
	background-color: red;
	}
	```
	Will make every `h1` tag have red background colour.
	
4. What if We want to select only a few `h1` tags? Well then we cannot use the `h1` selector but we need to use Class Selector as follows
   ```CSS
   .redElement{
   background-color: red;
   }
   ```
   And in the HTML file we write the tag as:
   ```CSS
   <h1 class="redElement"> heading </h1>
   ```
   
5. We can Declare Global CSS Variables using
   ```CSS
   :root{
   --variable-name: value;
   }
   ```
6. We can use these variables to colour elements as:
   `background-color: var(--variable-name);`
7. There can only be ONE body in an HTML document.
8. Similar to the background colour, we can set image as:
   `background-image: url(path)`
8. Instead of writing the padding for each of the four sides, we can just write 
   `padding : top right bottom left` just like a clock's hands moves in that way.
   The same works for `margin:` as well.
9. To remove default values from everything we use:
   ```CSS
   * {
     margin: 0;
     padding: 0;
     }
   ```
   And so on for everything we need to remove the default values of.

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources
This [Video](https://www.youtube.com/watch?v=SR5GxoFhIAU) helped me learn it step by step.

