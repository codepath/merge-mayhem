# CSS Basics
| Selector | Description | Syntax |
|----------|-------------|--------|
| [Universal Selector](https://developer.mozilla.org/en-US/docs/Web/CSS/Universal_selectors) | This selector uses the `*` symbol to apply styling rules to all elements on the website. | `* { property: value; }` |
| [Type Selector](https://developer.mozilla.org/en-US/docs/Web/CSS/Type_selectors) | This selector uses the name of an HTML element to apply styling rules to a specific type of elements | `element { property: value; }` |
| [Class Selector](https://developer.mozilla.org/en-US/docs/Web/CSS/Class_selectors) | This selector uses the `.` symbol followed by the class name (as identified by the attributes of some elements in the HTML document) to apply styling rules to all elements with the same class name. | `.className { property: value; }` |
| [Id Selector](https://developer.mozilla.org/en-US/docs/Web/CSS/ID_selectors) | This selector uses the `#` symbol followed by the id name to apply styling rules to a single element. | `#idName { property: value; }` |


**Line 6**  `<link href="style.css" rel="stylesheet" type="text/css" />`  connects the CSS style sheet to our HTML file.

Let’s break down the syntax used to do this action. Learn more on the [MDN Web Docs about the `link` element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link).

- `<link>`: This element specifies relationships between the current document (the HTML file) and an external resource (the CSS file).
- `href`: This attribute specifies the file path, or location, of our external resource. In this particular example, the CSS file is named `style.css` but you can name your stylesheet anything. Take note that the file path is surrounded by double quotes, `""`.
- `rel`: `rel` stands for relationship. This lets the document know how the resource will interact with the current document

, in this case we are linking to a `stylesheet`. Learn more on the MDN Web Docs about link types.
- `type`: Similar to the `rel` attribute, the `type` attribute lets the document know the specific type of file that is being linked.

