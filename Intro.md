### What is HTML?
HTML is the standard language used to create and design web pages. It structures the content on a web page, such as text, images, links, and other multimedia. HTML uses tags to define the structure and elements of a web page.
### Basic Structure of an HTML Document
An HTML document starts with a specific structure that ensures it is recognized by web browsers:
```
<!DOCTYPE html>
<html>
<head>
    <title>Page Title</title>
</head>
<body>
    <h1>Welcome to HTML</h1>
    <p>This is a paragraph.</p>
</body>
</html>
```
#### Breakdown of the Code:
```
<!DOCTYPE html>: Declares the document as HTML5.
<html>: The root element that wraps all the content on the page.
<head>: Contains metadata about the document, such as the title, styles, and scripts.
<title>: Sets the title of the page (shown on the browser tab).
<body>: Contains the main content of the page, visible to users.
```
### Common HTML Tags
#### 1. Headings
```
Use <h1> to <h6> tags for headings, where <h1> is the largest and <h6> is the smallest.
```
##### Example:
```
<h1>Main Heading</h1>
<h2>Subheading</h2>
```
#### 2. Paragraphs
```
Use <p> for paragraphs. With this, the text will always remain the same size.
```
##### Example:
```
<p>This is a paragraph.</p>
```
#### 3. Links
```
Use <a> to create hyperlinks.
```
##### Example:
```
<a href="https://www.example.com">Visit Example</a>
```
#### 4. Images
```
Use <img> to insert images. The src attribute specifies the image source, and alt provides alternative text.
```
##### Example:
```
<img src="image.jpg" alt="A descriptive text">
```
#### 5. Lists
```
Ordered lists use <ol> and <li>.
```
##### Example:
```
<ol>
    <li>First item</li>
    <li>Second item</li>
</ol>
```
#### Lists part 2.
```
Unordered lists use <ul> and <li>.
```
##### Example:
```
<ul>
    <li>Item one</li>
    <li>Item two</li>
</ul>
```
#### 6. Tables.
```
Use <table>, <tr>, <td>, and <th> for creating tables.
```
##### Examples:
```
<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
    </tr>
</table>
```
### HTML Attributes
Attributes provide additional information about an element and are always written inside the opening tag. For example:
```
<a href="https://www.example.com" target="_blank">Open in new tab</a>
href: Specifies the link's destination.
target="_blank": Opens the link in a new tab.
```
### Closing Tags
```
Most HTML elements have an opening tag (e.g., <p>) and a closing tag (e.g., </p>). However, some elements, like <img> and <br>, are self-closing.
```


