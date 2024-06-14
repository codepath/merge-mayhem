# HTML Basics

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
