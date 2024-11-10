# Technical Writing Assignment

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/fullstack-curriculum/how-tos/working-with-assignments#how-to-work-on-assignments).

## Prompt 1

Do some research on semantic and non-semantic elements and share your findings. Your response should include:

- Examples of semantic and non-semantic tags
- The differences between semantic and non-semantic tags
- The benefits of using semantic tags (when possible)

```
Semantic tags are elements that clearly define the meaning or purpose of the content they enclose, while non-semantic tags are elements that only serve as containers for the content without indicating their specific role. An example of semantic tags are header, which represents the header of the page, and nav which defines the navigation link. An example of non-semantic tags are div which is a generic container with no specific meaning, and span which is a small inline container for styling purposes. The purpose for using semantic tags are so our code can be more clear and readable to our audience/viewers.
```

## Prompt 2

Do some research on accessibility. What are some ways to make your website more accessible? Explain why it is important for developers to create websites that meet accessibility standards.

```
Some ways to make a website more accessible is making a button tag, use semantic tags throughout your code, and also add alt tags in your img tags describing what the picture looks like. It is important for developers to create websites that are accessible because you want the user to be able to navigate and interact nicely with your site.
```

## Prompt 3

It is possible to add "inline" CSS styles to our html elements using the `style` attribute like so:

```html
<p style="color: red;">hello world</p>
```

While this is possible, it is a best practice to instead write styles in a separate CSS file. Provide at least one argument for why it _might_ be considered useful to write inline styles, and then provide a more compelling argument for writing styles in a separate CSS file.

```
It can be useful to write inline css since it doesn't require external files or links and plus it may be easier to style since you don't have to target the specific element in another file and you can just style the element in the line its written in. Even though inline css can work, it's best to write styles in a separate file because your code can be more messier with inline css, and also it can be more easier to style elements a separate file. For an example, if you want to style all h1 elements a particular way, all you have to do is target all of the h1 elements in a separate css file instead of having to style every h1 element the same way in one file.
```

## Prompt 4

Imagine you are teaching a brand new programmer a brief lesson about the `class` and `id` attributes in HTML as well as how to use them to style elements using CSS. Your lesson should have the following components:

- An explanation of the concept of "classes" and "ids" with an analogy.
- An example of the usage using an HTML code block and a CSS code block.
- An explanation of the syntax using the terms: **attribute**, **selector**

```
ID's are used to target a specific element on a page, such as a navigation bar or header, while classes are used to style multiple elements that share characteristics or behaviors.
```

```html
<!--HTML example -->
<h1 id="title">LalaBye</h1>
<style>
  #title {
    color: blue;
  }
</style>
```

```css
/* CSS Example */
h1 {
  font-family: "Times New Roman";
  text-align: center;
}
```

```
In HTML, the class and id are attributes we add to elements to identify them. For an example <h1 id="title>LalaBye</h1> uses a attribute to give the element an id.
In CSS, selectors are used to select each element you want to style, there are two types of selectors which are "Class selectors", and "ID selectors".

Class selectors are used to to select elements with a specific class. We use a period(.) followed by the class name to select it. So if we wanted to select all elements with the class "back-up", we would put (.back-up).

ID selectors are used to select elements with a specific id. We would use a hash (#) followed by the id name to select the id. For an example, we would use #background-info to select all the elements with the id "background-info".
```

## Prompt 5

The Document Object Model (DOM) API provides functions for manipulating HTML documents. It is possible to build an entire website using only JavaScript and the DOM API, however is that the best practice?

When building a website, how can I decide which content I should write using HTML/CSS and which content I should create using the JavaScript and the DOM API?

```
Using only DOM and javaScript is not the best practice, the best practice is using javaScript and HTML/CSS. The reason for this is so your site could run faster, it can be more accessible to viewers, and the performance can be overall better.

You can use HTML/CSS for elements that don't change and for styling purposes in your website, while you can use JavaScript and DOM API for content that changes based on the users actions and for writing functions for your website.
```
