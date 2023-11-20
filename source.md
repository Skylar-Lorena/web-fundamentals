# HTML Introduction

## Attributes

HTML attributes are additional details that can be added to HTML elements to provide more information about the element. Attributes are specified in name-value pairs within the opening tag of an element.

```html
<elementName attributeName="attributeValue">Content</elementName>
Example:

html

<img src="image.jpg" alt="Image description">
```

### Element Syntax

The basic syntax for an HTML element is:
html

<tagName>Content</tagName>
Where tagName is the name of the element and Content is the content that will be displayed within the element.

Example:

html

<p>This is a paragraph.</p>

### Semantics Syntax

Semantic syntax is used to give HTML elements a specific meaning. This helps search engines and other machines understand the content of a web page. Semantic elements include headings, paragraphs, lists, and more.

Example:

html

<h1>This is a heading</h1>

<p>This is a paragraph.</p>

<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>

### Void Syntax

Void elements are self-closing elements that do not contain any content. These elements are typically used to embed media or other content into a web page. Void elements include <img>, <hr>, and <br>.

Example:

html

<img src="image.jpg" alt="Image description">


### Anatomy of an HTML Document
The basic structure of an HTML document is as follows:

html

<!DOCTYPE html>
<html>
<head>
  <title>Page Title</title>
</head>
<body>
  <!-- Content goes here -->
</body>
</html>

### Block vs. Inline Elements

Block elements start on a new line and take up the full width of their container. Inline elements flow within the text and do not take up the full width of their container.

Common block elements include:

<p> (paragraph)
<h1>, <h2>, <h3>, etc. (headings)
<ul>, <ol> (lists)
<div> (division)
Common inline elements include:

<a> (anchor)
<strong>, <em> (emphasis)
<sub>, <sup> (subscript/superscript)

### Tables
Tables are used to organize data in a tabular format. Tables consist of rows and cells.

Basic table syntax:

html

<table>
  <tr>
    <th>Column 1 Heading</th>
    <th>Column 2 Heading</th>
  </tr>
  <tr>
    <td>Data 1</td>
    <td>Data 2</td>
  </tr>
</table>

### Forms Basics
Forms are used to collect user input. Forms consist of input fields, buttons, and other controls.

Basic form syntax:

html

<form>
  <label for="firstName">First Name:</label>
  <input type="text" id="firstName" name="firstName">
  
  <br>
  
  <label for="lastName">Last Name:</label>
  <input type="text" id="lastName" name="lastName">
  
  <br>
  
  <button type="submit">Submit</button>
</form>
