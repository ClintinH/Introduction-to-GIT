# HTML helpful Information 

## HTML Common Tag list
\<html>>/html>
\<!DOCTYPE html>
\<title> this is heading<\title>
\<Body>this is the body>/body>
\<div>>/div>
\<span>>/span>
\<a href="https://www.ggogle.com">google</a>.
\<table>>/table>
\<thead>>/thead>
\<tr>>td>Value1>/td>>td>Value2>/td>>/tr>
\<script>
\<!-- javascript code -->
\</script>
\<img src=https://bitarray.io/images.logo.png alt="bitarray logo">
\<strong> this is strong text>/strong>

[Reference](https://www.bitarray.io/20-html-tags-you-need-to-know/)

### HTML: HyperText Markup Language
HTML (HyperText Markup Language) is the most basic building block of the Web. It defines the meaning and structure of web content. Other technologies besides HTML are generally used to describe a web page's appearance/presentation (CSS) or functionality/behavior (JavaScript).

"Hypertext" refers to links that connect web pages to one another, either within a single website or between websites. Links are a fundamental aspect of the Web. By uploading content to the Internet and linking it to pages created by other people, you become an active participant in the World Wide Web.

HTML uses "markup" to annotate text, images, and other content for display in a Web browser. HTML markup includes special "elements"[Reference](https://developer.mozilla.org/en-US/docs/Web/HTML)

### What Does HTML5 Mean?
Hypertext Markup Language revision 5 (HTML5) is markup language for the structure and presentation of World Wide Web contents. HTML5 supports the traditional HTML and XHTML-style syntax and other new features in its markup, New APIs, XHTML and error handling.
HTML5 is an effort is to bring order to web development chaos by organizing common practices, embracing implementations from various browsers. It is massive, with over 100 specifications as part of the HTML5 specs. Understanding this, you can simplify by thinking of HTML5 this way. HTML5 is simply just an umbrella term for the next generation of web apps an how functionality will be expanded with better markup (HTML), better style (CSS), and better interactivity (JavaScript). [Reference](https://www.techopedia.com/definition/1891/html5)

### HTML
- It didn’t support audio and video without the use of flash player support.
- It uses cookies to store temporary data.
- Does not allow JavaScript to run in browser.
- Vector graphics is possible in HTML with the help of various technologies such as VML, Silver-light, Flash, etc.
- It does not allow drag and drop effects.
- Not possible to draw shapes like circle, rectangle, triangle etc.
- It works with all old browsers.
Older version of HTML are less mobile-friendly.
- Doctype declaration is too long and complicated.
- Elements like nav, header were not present.
- Character encoding is long and complicated.
- It is almost impossible to get true GeoLocation of user with the help of browser.
- It can not handle inaccurate syntax.
Attributes like charset, async and ping are absent in HTML.

### HTML5
- It supports audio and video controls with the use of \<audio> and \<video> tags.
- It uses SQL databases and application cache to store offline data.
- Allows JavaScript to run in background. This is possible due to JS Web worker API in HTML5.
Vector graphics is additionally an integral a part of HTML5 like SVG and canvas.
- It allows drag and drop effects.
HTML5 allows to draw shapes like circle, rectangle, triangle etc.
- It supported by all new browser like Firefox, Mozilla, Chrome, Safari, etc
- HTML5 language is more mobile-friendly.
- Doctype declaration is quite simple and easy.
- New element for web structure like nav, header, footer etc.
- Character encoding is simple and easy.
- One can track the GeoLocation of a user easily by using JS GeoLocation API.
- It is capable of handling inaccurate syntax.
Attributes of charset, async and ping are a part of HTML 5.
[Reference](https://www.geeksforgeeks.org/difference-between-html-and-html5/)

### HTML Tag Properties
The html tag properties can be difined by adding atributes =.

### Atributes: 
HTML attributes provide additional information about HTML elements.
HTML Attributes
    All HTML elements can have attributes
    Attributes provide additional information about elements
    Attributes are always specified in the start tag
    Attributes usually come in name/value pairs like: name="value"
[Reference](https://www.w3schools.com/html/html_attributes.asp)

### Tags
An HTML tag is a piece of markup language used to indicate the beginning and end of an HTML element in an HTML document.
As part of an HTML element, HTML tags help web browsers convert HTML documents into web pages. For example, the \<p> tag is used to organize text content into paragraph elements and the \<img> tag is used to embed image elements.
Many tags, though not all, use an opening tag and closing tag to wrap around the content that they are used to modify. Closing tags are denoted with a backslash like this: </tag_name>. HTML tags are not visible in the browser.
The following diagram illustrates how tags are commonly used in HTML elements:
[Reference](https://www.digitalocean.com/community/tutorials/what-is-an-html-tag)

### The DocType Tag
\<!DOCTYPE html>
The HTML document type declaration, also known as DOCTYPE, is the first line of code required in every HTML or XHTML document. The DOCTYPE declaration is an instruction to the web browser about what version of HTML the page is written in. This ensures that the web page is parsed the same way by different web browsers.
[Reference](https://www.freecodecamp.org/news/what-is-the-doctype-declaration-in-html/#:~:text=The%20HTML%20document%20type%20declaration,way%20by%20different%20web%20browsers)

### The Header Tag
The \<header> HTML element represents introductory content, typically a group of introductory or navigational aids. It may contain some heading elements but also a logo, a search form, an author name, and other elements.
Usage: The >header> element is not sectioning content and therefore does not introduce a new section in the outline. That said, a \<header> element is intended to usually contain the surrounding section's heading (an h1–h6 element), but this is not required.
[Reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/header)

### The Body Tag 
The \<body> tag in HTML is used to define the main content present inside an HTML page. It is always enclosed within >html>tag. The \<body> tag is the last child of \<html> tag. A body tag contains starting as well as an ending tag. [Reference](https://www.geeksforgeeks.org/html-body-tag/#:~:text=The%20tag%20in%20HTML,present%20inside%20an%20HTML%20page.&text=Attributes%3A%20There%20are%20many%20attributes,to%20set%20the%20background%20image)

### Padding
An element's padding area is the space between its content and its border. Padding creates extra space within an element.
This property is a shorthand for the following CSS properties:
padding-bottom
padding-left
padding-right
padding-top
[Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/padding)

### Margin
The margin property defines the space around an HTML element. It is possible to use negative values to overlap content.
The values of the margin property are not inherited by the child elements. Remember that the adjacent vertical margins (top and bottom margins) will collapse into each other so that the distance between the blocks is not the sum of the margins, but only the greater of the two margins or the same size as one margin if both are equal.
We have the following properties to set an element margin.
⦁	The margin specifies a shorthand property for setting the margin properties in one declaration.
⦁	The margin-bottom specifies the bottom margin of an element.
⦁	The margin-top specifies the top margin of an element.
⦁	The margin-left specifies the left margin of an element.
⦁	The margin-right specifies the right margin of an element.
[Reference](https://www.tutorialspoint.com/css/css_margins.htm#:~:text=The%20margin%20property%20defines%20the,negative%20values%20to%20overlap%20content.&text=The%20margin%2Dbottom%20specifies%20the,left%20margin%20of%20an%20element)