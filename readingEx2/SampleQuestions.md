# Basic Web Techniques

## Reading Assignment 2: WWW and HTML

### Html

1. Name the components of html elements properly

Tag Name: The name of the element, surrounded by angle brackets (< and >).
Attributes: Additional information about the element, specified as name-value pairs.
Content: The text or other elements contained within the element.
Closing Tag: The tag that marks the end of the element, typically identical to the opening tag but with a forward slash (/) before the tag name

2. Identify void elements and how they are denoted 

Void elements are HTML elements that do not have a closing tag. 
They are denoted by a single tag with a forward slash (/) at the end, like this: <br/>, <img src="image.jpg" />, etc.

3. Identify attributes
 Attributes are additional information about an element, specified as name-value pairs. For example: <a href="https://www.example.com">Link</a>, where href is the attribute name and "https://www.example.com" is the attribute value.

4. Write down the correct ``DOCTYPE`` declaration for html 5  
The correct DOCTYPE declaration for HTML 5 is <!DOCTYPE html>.

5. Write down syntactically correct statements for the following elements
   - Article (``<article>``)
   - Body (``<body>``)
   - line break (``<br/>``)
   - Headings (``<h1>``, ...)
   - Section with meta-information (``<head>``)
   - Top level element (``<html>``)
   - Image named ``Team.jpg`` (``<img src="Team.jpg">``)
   - Paragraph (``<p>``)
   - Section (``<section>``)
   - Label appearing in the title bar (``<title>``)
   - Link to other pages (``<a>``)
   - Comment
   - Head with title and meta elements

   Article: <article>article</article>
Body: <body> body of the HTML document</body>
Line Break: <br/>
Headings: <h1>This is a heading</h1>, <h2>This is a subheading</h2>, etc.
Section: <head><title>Page Title</title></head>
Top level element: <html><head>...</head><body>...</body></html>
Image named "Team.jpg": <img src="Team.jpg" alt="Team photo">
Paragraph: <p>This is a paragraph of text</p>
Section: <section>This is a section of the document</section>
Label appearing in the title bar: <title>Page Title</title>
Link to other pages: <a href="https://www.example.com">Link to example.com</a>
Comment: <!-- This is a comment -->
Head with title and meta elements: <head><title>Page Title</title><meta charset="UTF-8"></head>

## Css

1. Name the components of a css rule properly
part of the rule that specifies which elements to apply the styles to.
The individual styles that are applied to the selected elements.
The values assigned to each property. 

2. Use combinators properly: direct child, descendant, adjacent sibling, sibling
Direct Child: > (e.g., div > p selects all p elements that are direct children of div elements)
Descendant:   (e.g., div p selects all p elements that are descendants of div elements)
Adjacent Sibling: + (e.g., h2 + p selects all p elements that are adjacent siblings of h2 elements)
Sibling: ~ (e.g., h2 ~ p selects all p elements that are siblings of h2 elements)

3. Specify colors by color names and in hexadecimal notation
Color Names: color: red;, color: blue;, etc.
Hexadecimal Notation: color: #FF0000;, color: #0000FF;, etc.

4. Declarations for color, background color
Color: color: #FF0000;
Background Color: background-color: #FFFFFF;    

5. Pseudo classes for the ``<a>`` element  
:link: a:link { color: blue; }
:visited: a:visited { color: purple; }
:hover: a:hover { color: red; }
:active: a:active { color: green; }  

6. Declaration for background image
background-image: url('image.jpg');


7. Declaration for text alignment (left, right, center, justify)
Left: text-align: left;
Right: text-align: right;
Center: text-align: center;
Justify: text-align: justify; 

8. Declaration for text decoration (overline, underline, line-through)
Overline: text-decoration: overline;
Underline: text-decoration: underline;
Line-through: text-decoration: line-through;  

9. Declaration for text transformation (uppercase, lowercase, capitalize)
Uppercase: text-transform: uppercase;
Lowercase: text-transform: lowercase;
Capitalize: text-transform: capitalize;  

10. Identify the difference between serif and sans-serif fonts
Serif fonts have small lines or flourishes at the ends of the strokes that make up the letters. Examples of serif fonts include Times New Roman, Garamond, and Georgia.  

11. Declarations for font families
Serif font family: font-family: serif;
Sans-serif font family: font-family: sans-serif;
Specific font family: font-family: Arial, Helvetica, sans-serif;  

12. Declarations for font style normal and italic
Normal font style: font-style: normal;
Italic font style: font-style: italic;  

13. Declarations for font sizes
Absolute font size: font-size: 16px;
Relative font size: font-size: 1.2em;  

14. Declarations for font weights
Normal font weight: font-weight: normal;
Bold font weight: font-weight: bold;
Specific font weight: font-weight: 700;  

