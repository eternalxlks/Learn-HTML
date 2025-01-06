### What is HTML?
HTML is the standard language used to create and design web pages. It structures the content on a web page, such as text, images, links, and other multimedia. HTML uses tags to define the structure and elements of a web page.
### Basic Structure of an HTML Document
An HTML document starts with a specific structure that ensures it is recognized by web browsers:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="A comprehensive example of a web page including all possible meta tags.">
    <meta name="keywords" content="HTML, meta tags, SEO, web development">
    <meta name="author" content="Your Name">
    <meta name="robots" content="index, follow">
    <meta name="googlebot" content="index, follow">
    <meta name="canonical" href="https://example.com">
    <meta property="og:title" content="Example Web Page with Meta Tags">
    <meta property="og:description" content="A detailed HTML document structure including all necessary meta tags.">
    <meta property="og:image" content="https://example.com/image.jpg">
    <meta property="og:url" content="https://example.com">
    <meta property="og:type" content="website">
    <meta property="og:locale" content="en_US">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Example Web Page with Meta Tags">
    <meta name="twitter:description" content="A detailed HTML document structure including all necessary meta tags.">
    <meta name="twitter:image" content="https://example.com/image.jpg">
    <meta name="twitter:site" content="@yourtwitterhandle">
    <meta name="theme-color" content="#ffffff">
    <meta name="mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
    <meta name="apple-mobile-web-app-title" content="Meta Tags Example">
    <meta name="google-site-verification" content="your-google-site-verification-code">
    <meta name="yandex-verification" content="your-yandex-verification-code">
    <meta name="msvalidate.01" content="your-bing-verification-code">
    <meta http-equiv="refresh" content="30">
    <meta name="generator" content="Visual Studio Code">
    <meta name="rating" content="general">
    <link rel="icon" href="favicon.ico" type="image/x-icon">
    <link rel="apple-touch-icon" href="apple-touch-icon.png">
    <title>My Website</title>
</head>
<body>
    <h1>Welcome to my Website</h1>
    <p>Bye for now!</p>
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
```html
<h1>Main Heading</h1>
<h2>Subheading</h2>
```
##### Preview:
<!-- Made these a bit smaller as to not interfere because underlines are added for <h2> and <h1> -->
### Main Heading
#### Subheading

#### 2. Paragraphs
```
Use <p> for paragraphs. With this, the text will always remain the same size.
```
##### Example:
```html
<p>This is a paragraph.</p>
```
##### Preview:
This is a paragraph.
#### 3. Links
```
Use <a> to create hyperlinks.
```
##### Example:
```html
<a 
    href="https://example.com" 
    target="_blank" 
    rel="noopener noreferrer" 
    hreflang="en" 
    type="text/html" 
    referrerpolicy="no-referrer" 
    role="link" 
    aria-label="Accessible description of the link" 
>
    Click here
</a>
```
##### Preview:
[Visit Example](https://www.example.com)
#### 4. Images
```
Use <img> to insert images. The src attribute specifies the image source, and alt provides alternative text.
```
##### Example:
```html
<img 
    src="example.jpg" 
    alt="Description of the image" 
    width="600" 
    height="400" 
    crossorigin="anonymous" 
    decoding="async" 
    importance="high" 
    loading="lazy" 
    referrerpolicy="no-referrer" 
    style="border: 2px solid black; border-radius: 5px;" 
    draggable="false" 
    title="Hover text for the image" 
    role="img" 
    aria-label="Accessible description of the image" 
/>

```
##### Preview
<!-- Game idea spoiler? -->
![A descriptive text](https://github.com/user-attachments/assets/fad34984-ae58-40e4-bcaa-16abf9744030)

#### 5. Lists
```
Ordered lists use <ol> and <li>.
```
##### Example:
```html
<ol>
    <li>First item</li>
    <li>Second item</li>
</ol>
```
##### Preview:
1. First item
2. Second item
#### Lists part 2.
```
Unordered lists use <ul> and <li>.
```
##### Example:
```html
<ul>
    <li>Item one</li>
    <li>Item two</li>
</ul>
```
##### Preview:
- Item one
- Item two
#### 6. Tables.
```
Use <table>, <tr>, <td>, and <th> for creating tables.
```
##### Examples:
```html
<table>
    <tr role="row">
        <th
            scope="col" 
            abbr="H1" 
            style="text-align: left;" 
            role="columnheader" 
            aria-label="Header 1" 
        >Header 1</th>
        <th
            scope="col" 
            abbr="H2" 
            style="text-align: left;" 
            role="columnheader" 
            aria-label="Header 2"
        >Header 2</th>
    </tr>
    <tr role="row">
        <td
            headers="Header 1" 
            style="text-align: left;" 
            role="cell" 
            aria-label="Data 1" 
        >Data 1</td>
        <td
            headers="Header 1" 
            style="text-align: left;" 
            role="cell" 
            aria-label="Data 1"
        >Data 2</td>
    </tr>
</table>
```
##### Preview:

| Header 1 | Header 2 |
|----------|----------|
| Data 1   | Data 2   |

### HTML Attributes
Attributes provide additional information about an element and are always written inside the opening tag. For example:

##### Example:
```
<a href="https://www.example.com" target="_blank">Open in new tab</a>
href: Specifies the link's destination.
target="_blank": Opens the link in a new tab.
```
##### Preview:
<a href="https://www.example.com" target="_blank">Open in new tab</a>

### Closing Tags

Most HTML elements have an opening tag (e.g., `<p>`) and a closing tag (e.g., `</p>`). However, some elements, like `<img>` and `<br>`, are self-closing. Self-closing tags have two forms:

```html
<img 
    src="example.jpg" 
    alt="Description of the image" 
    width="600" 
    height="400" 
    crossorigin="anonymous" 
    decoding="async" 
    importance="high" 
    ismap 
    loading="lazy" 
    referrerpolicy="no-referrer" 
    sizes="(max-width: 600px) 100vw, 600px" 
    srcset="example-480w.jpg 480w, example-800w.jpg 800w" 
    usemap="#imagemap" 
    style="border: 2px solid black; border-radius: 5px;" 
    draggable="false" 
    title="Hover text for the image" 
    role="img" 
    aria-label="Accessible description of the image" 
>

<img 
    src="example.jpg" 
    alt="Description of the image" 
    width="600" 
    height="400" 
    crossorigin="anonymous" 
    decoding="async" 
    importance="high" 
    ismap 
    loading="lazy" 
    referrerpolicy="no-referrer" 
    sizes="(max-width: 600px) 100vw, 600px" 
    srcset="example-480w.jpg 480w, example-800w.jpg 800w" 
    usemap="#imagemap" 
    style="border: 2px solid black; border-radius: 5px;" 
    draggable="false" 
    title="Hover text for the image" 
    role="img" 
    aria-label="Accessible description of the image" 
/>
```

The second form is the only form you can use in XHTML documents, which is a type of stricter HTML.

