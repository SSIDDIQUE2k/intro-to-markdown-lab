# intro-to-markdown-lab
# YOU-DO SECTION
Writing a Function in JavaScript

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

1. Basic syntax

``const functionName = (params) => {
  // code to be executed``
}

+ **const**: const should be used whenever a function expression is assigned to a variable.
The function name: The name you choose for the function.
+ **Parameters**: Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
+ **The arrow syntax**: Indicates that this will be a function.
+ **The body**: The statements that make up the function itself. Surrounded by curly braces.

``Example: const greet = (name) => {
  console.log("Hello, " + name + "!");``
}

>Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ). 

2. Calling a function

To execute the function, you _call_ or _invoke_ it by using its name followed by parentheses.

Example:

``greet('Alice'); // Outputs: Hello, Alice!``

3. _Return values_

Functions can process data input and output a value using the return keyword.

4. __Example__: 

``const addNums = (numA, numB) => {``
  ``return numA + numB``
}

``const total = addNums(2, 4);``

``console.log(total) // Expected value: 6``

For more information on functions and how they are used in JS, check out the MDN docs. 
[MDN docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)



------------------------------------------------------       LAB Work Lecture         ----------------------------------------------------------------

Part 1: 1. Header

# h1
## h2
### h3
#### h4
##### h5
###### h6

 2 : Bolidng/Italics/Italics and Bolds

This text is **bold**. This text is also __bold__.

This text is in *italics*. This text is also in _italics_.


This text is ***bold and italicized***. This text is also ___bold and italicized___.

You Do: Part 1 complete

3: Creating lists
Bulleted lists: unordered lists

* Item 1
* Item 2
  * Subitem 2.1
  * Subitem 2.2
    * Subitem 2.2.1

Numbered lists: ordered lists
    
1. First item
2. Second item
   1. Subitem 2.1
   2. Subitem 2.2


You Do #2 : Part 1 complete


4. Code snippets

inline code

Use the `console.log()` function to print values to the console.

miltiline code


```javascript
const printItem = (item) => {
  console.log(item);
}
```
const printItem = (item) => {
  console.log(item);
}
You Do number 3 done

5. Adding links

Inline-style links
You can create an inline link by wrapping the link text in brackets [My URL]

[Google](https://www.google.com)

6. Blockquotes
> This is a blockquote.

Blockquotes are handy for highlighting important asides in text, often representing citations, referenced content, or emphasizing statements in your Markdown documents.

To create a blockquote, start the line with the > character followed by a space.

> First level of blockquote.
>> Nested blockquote.
>>> Another nested blockquote.



You Do 4 done


7. Adding images


Using images can elevate your documentation, tutorials, and project write-ups. Embedding images is straightforward in Markdown (and the best way to include screenshots in a project).


![some alt text](www.url_to_an_image.com/image)



You Do 5 

![Door Dashz](https://images.unsplash.com/photo-1717457779626-24fafc629c67?q=80&w=2970&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDF8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

