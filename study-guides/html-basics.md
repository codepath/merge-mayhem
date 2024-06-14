# HTML Basics


## Introducing the `div` element

The `div`, or content division element, is used to define sections or divisions of content on the webpage. When using these elements you may not see a difference from the user-view but it helps organize groups of elements within the html page.

**_But why is it necessary to organize your html elements?_**

There are many reasons why developers might use the `div` element in their code. Some of which may include:

- **Creating more readable code.** Using the `div` element makes it easier for code reviewers to see defined sections to help identify bugs, or isolate features to sections on the website.
- **For styling!** By creating defined sections, it allows developers to add custom styling to each section of their website. This is perhaps one of the most common reasons developers use `div` tags.

### Linking CSS Files

**Line 6**  `<link href="style.css" rel="stylesheet" type="text/css" />`  connects the CSS style sheet to our HTML file.

Let’s break down the syntax used to do this action. Learn more on the [MDN Web Docs about the `link` element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link).

- `<link>`: This element specifies relationships between the current document (the HTML file) and an external resource (the CSS file).
- `href`: This attribute specifies the file path, or location, of our external resource. In this particular example, the CSS file is named `style.css` but you can name your stylesheet anything. Take note that the file path is surrounded by double quotes, `""`.
- `rel`: `rel` stands for relationship. This lets the document know how the resource will interact with the current document

, in this case we are linking to a `stylesheet`. Learn more on the MDN Web Docs about link types.
- `type`: Similar to the `rel` attribute, the `type` attribute lets the document know the specific type of file that is being linked.

### Linking JavaScript Files

**Line 9**  `<script src="script.js"></script>` links the JavaScript file to our HTML file.

Let’s break down the syntax used to do this action.

- `<script>`: You may be wondering, why do we use the `script` element to connect JavaScript files instead of the `link` element that is used for CSS files. Unlike CSS styling, JavaScript dynamically changes elements in the HTML document. JavaScript may add, delete, or modify HTML elements. CSS styling can only change the appearance of an element, but cannot modify the structure of the HTML element.
- `src`: This attribute specifies the file path, or location, of our external resource. In this particular example, the JS file is named `script.js` but you can name your stylesheet anything. Take note that the file path is surrounded by double quotes, `“”`.

You may have noticed that the `<script>` element is placed inside of the `<body>` element. This is different from the `<link>` element for CSS files which is in the `<head>` element. This is because JavaScript files can often affect the HTML elements within the document. To ensure that the JavaScript file does not run before the HTML elements have been loaded on the page, developers tend to place the `<script>` element towards the bottom of the HTML file to avoid potential errors.

## HTML Boilerplate

**The HTML file is the most important file when building a basic website.** Some online IDEs like [Glitch](https://glitch.com/) or [Replit](https://replit.com/), you may notice that a basic website project comes pre-loaded with at least 3 files with the names `index.html`, `style.css`, and `script.js`. These are typical generic names an HTML, CSS, and JavaScript file, but you can name your files any name you want. It is always best practice to give your files a short descriptive name so that it is easier for others to view your code.

All websites **must have at least one HTML file**, but CSS style and JavaScript script files are **optional**. To learn more about file naming conventions and organization tips, check out [MDN web docs on dealing with files](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/Dealing_with_files).

*Note:* Web servers will often default to loading the `index.html` file if multiple HTML files are present, unless otherwise specified.

**Let’s take a look at a typical boilerplate, or standard template, for an HTML file.**

```html
<!DOCTYPE html>
<html>
 <head>
   <meta charset="utf-8">
   <meta name="viewport" content="width=device-width">
   <title>Title of Website</title>
   <link href="style.css" rel="stylesheet" type="text/css" />
 </head>
 <body>
   <script src="script.js"></script>
 </body>
</html>
```

In HTML, we denote an element by specifying the name of the element in opening brackets `<>` and closing brackets `</>`. Let’s take the time to highlight the structure of an HTML file and some important elements presented in the boilerplate above.

