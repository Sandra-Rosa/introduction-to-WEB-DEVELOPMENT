# introduction-to-HTML
## What is HTML?
- HTML stands for Hyper Text Markup Language
- HTML is the standard markup language for creating Web pages
- HTML describes the structure of a Web page
- HTML consists of a series of elements
- HTML elements tell the browser how to display the content
- HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.
## What is an HTML Element?
An HTML element is defined by a start tag, some content, and an end tag:

<tagname>Content goes here...</tagname>
The HTML element is everything from the start tag to the end tag:
## Web Browsers
The purpose of a web browser (Chrome, Edge, Firefox, Safari) is to read HTML documents and display them correctly.

# HTML Basic Examples
## HTML Documents
All HTML documents must start with a document type declaration: <!DOCTYPE html>.

The HTML document itself begins with <html> and ends with </html>.

The visible part of the HTML document is between <body> and </body>.

## The <!DOCTYPE> Declaration
The <!DOCTYPE> declaration represents the document type, and helps browsers to display web pages correctly.

It must only appear once, at the top of the page (before any HTML tags).

The <!DOCTYPE> declaration is not case sensitive.

  
## HTML Links
HTML links are defined with the <a> tag
  The link's destination is specified in the href attribute. 

Attributes are used to provide additional information about HTML elements.
## HTML Images
HTML images are defined with the <img> tag.

The source file (src), alternative text (alt), width, and height are provided as attributes
## How to View HTML Source?
Have you ever seen a Web page and wondered "Hey! How did they do that?"

## View HTML Source Code:
Right-click in an HTML page and select "View Page Source" (in Chrome) or "View Source" (in Edge), or similar in other browsers. This will open a window containing the HTML source code of the page.

## Inspect an HTML Element:
Right-click on an element (or a blank area), and choose "Inspect" or "Inspect Element" to see what elements are made up of (you will see both the HTML and the CSS). You can also edit the HTML or CSS on-the-fly in the Elements or Styles panel that opens
  
  # HTML Elements
  
  he HTML element is everything from the start tag to the end tag:

<tagname>Content goes here...</tagname>
  
  Nested HTML Elements
HTML elements can be nested (this means that elements can contain other elements).

All HTML documents consist of nested HTML elements.
  ## Never Skip the End Tag
Some HTML elements will display correctly, even if you forget the end tag
  ## Empty HTML Elements
HTML elements with no content are called empty elements.

The <br> tag defines a line break, and is an empty element without a closing tag
  ## HTML is Not Case Sensitive
HTML tags are not case sensitive: <P> means the same as <p>.

The HTML standard does not require lowercase tags, but W3C recommends lowercase in HTML, and demands lowercase for stricter document types like XHTML.
