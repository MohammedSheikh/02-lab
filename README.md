# Basic CSS Exercise

The index.html file contains the module handbook, with the code (generated by the Markdown file) indented and modified ready for you to style up.

Go through the following steps, reloading your file (`ctrl/cmd-R`) in the browser after each change.

1. create a new folder "css" and create a file "styles.css" inside it
1. link to the stylesheet in the HTML `head` section using the syntax `<link rel="stylesheet" href="css/styles.css">`
1. make sure your styles are being read into the HTML file by adding the following at the top of "styles.css": `body{ background: red; }`
1. reload in the browser. If the background is red it has worked, so comment out the above code between CSS comments `/*` and `*/`
1. Set a `font-family` style for the `body` tag that will cascade throughout the entire document. See the [CSS Font Stack](https://www.cssfontstack.com/) for examples
1. Set a `max-width` value for the `main` tag to ensure the [line lengths (see this article)](https://www.usability.gov/get-involved/blog/2006/08/line-length-and-onscreen-reading.html) don't get too wide to be readable. Try `800px`
1. set a different font-family style for all the headings (`h1, h2, h3, h4, h5, h6`). The CSS selector for **multiple targets** is comma-separated e.g. `h1, h2 { property: value; }`
1. Style the `ul` element inside the `nav` section. To target an element that is *nested inside* another element, the selector is a space-separated list e.g. `nav ul` or for the li tags themselves `nav li` (you can skip an element)
1. Style the table elements. Adding `width: 100%` will ensure they stretch to match the body width
1. adjust the padding where necessary (e.g. in table cells)
1. change the default blue/purple link (`a` tag) colours using the pseudo-classes `a:link` and `a:hover` as identifiers
1. create a standard horizontal menu from the `nav` using `text-align: center;` and for `nav ul` `list-style-type: none;` to remove the bullet points, and for `nav li` use `display: inline-block;`
1. inside the `nav`, restyle the `a` tags (`nav a`) using `display: block;` to enable background-colours and hover styles to display more effectively. You can also change the `background-color` using the `:hover` state
1. add `text-decoration: none;` to the `nav a` style block, and a `background-color` value

## Optional experiment

Create a floating menu from the `nav` element by using `position: fixed; left: 10px; top: 20em; width 20%` and for the `main` tag use `margin-left: 25%; max-width: 800px;`
