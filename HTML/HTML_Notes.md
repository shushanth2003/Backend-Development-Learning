# HTML Notes
## Tag
In HTML, a tag is used for creating an element.
The name of an HTML element is the name that appears at the beginning of the element's start tag and at the end of the element's end tag (if the element has an end tag). For example, the p in the p start tag and /p end tag is the name of the HTML paragraph element. Note that an element name in an end tag is preceded by a slash character: /p and that for void elements, the end tag is neither required nor allowed.
```
<div></div> //this is called as Tag
```
---
## Attribute
* An attribute extends an HTML or XML element, changing its behavior or providing metadata.

* An attribute always has the form name="value" (the attribute's identifier followed by its associated value). You may see attributes without an equals sign or a value. That is a shorthand for providing the empty string in HTML. However, this is not valid in XML: XML requires all attributes to have an explicit value.

* A number of HTML attributes are boolean attributes. These attributes' values are only controlled by the presence or absence of the attribute. See boolean attributes for more information.

---
## Case Insensitivity
HTML isn't picky about capitalization. You can write tags and attributes using uppercase, lowercase, or a mix of both. For example, <html>, <HTML>, and <Html> all work the same way. While browsers understand all these variations, it's generally considered good practice to stick to lowercase for better readability and consistency in your code.
---
## Entity
Entity is a term from the Standard Generalized Markup Language (SGML), which refers to a reference to information that can be defined once and used throughout a document.

The term "HTML Entity" is used as a synonym for a character reference — a pattern of characters that can represent another character in the HTML. For example, &lt; is used to represent the less-than symbol (<) in HTML content.
---
## HTML Comments
Comments in HTML are notes that you can add to your code to explain what's going on, make reminders, or temporarily disable parts of your code. These comments are not displayed in the browser, so they're only visible when someone views the source code. To create a comment in HTML, you enclose your text within <!-- and -->. Anything between these tags will be ignored by the browser.
---
## Whitespaces
Whitespaces in HTML refer to the spaces, tabs, and line breaks that are used to format the code. Browsers typically collapse multiple consecutive whitespaces into a single space when rendering the content. While using whitespaces can improve the readability of your HTML code, they generally don't affect how the page is displayed to the user.
---
# Basic Tags
## !DOCTYPE Declaration
The <!DOCTYPE> declaration is an instruction to the web browser about the HTML version used to write the page. It's placed at the very top of an HTML document, before the <html> tag, and ensures that the browser renders the page in "standards mode," following the correct specifications for that HTML version. Technically, It is not an HTML tag itself.
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>First Page</title>
</head>
<body>
    <h1>Welcome to 2027 Arc!!!!</h1>
</body>
</html>
```
---
## HTML Element
The <html> element is the root element of an HTML page. It tells the browser that this is an HTML document. All other HTML elements (except for the <!DOCTYPE> declaration) must be descendants of the <html> element.
---
## Body Tag
The <body> tag in HTML defines the main content of an HTML document. It contains all the visible elements of a webpage, such as text, images, links, tables, lists, and more. Think of it as the container for everything you actually see and interact with on a website.
---
## head Tag
The <head> element in HTML acts as a container for metadata (data about data) about the HTML document. This metadata isn't displayed on the page itself, but it provides information like the document's title, character set, linked stylesheets, scripts, and other important configurations that help browsers and search engines understand and process the HTML document correctly.
---
## Meta tag
Meta tags in HTML provide metadata about an HTML document, which is information about the webpage that is not directly visible to the user but is crucial for browsers, search engines, and other web services. These tags are placed within the <head> section of an HTML document. 
### Reasons for using Meta Tags:
* **Search Engine Optimization (SEO)**: Meta tags provide information to search engines about the content of a page, influencing how the page is indexed and displayed in search results.
* **Browser Rendering and Functionality**: They guide browsers on how to render the page, handle character sets, and manage responsiveness across different devices.
* **Social Media Sharing**: Meta tags (like Open Graph tags) control how a webpage's content appears when shared on social media platforms.
* **Accessibility and Usability**: They can contribute to a better user experience by ensuring correct display and providing relevant information to assistive technologies.
---
# Textual Tags
## Headings
Headings are used to define the titles and subtitles within a document. HTML provides six levels of headings, from h1 (the most important and largest) to h6 (the least important and smallest). They help structure content and improve readability by creating a clear hierarchy.
---
## Title Tag
The <title> tag in HTML defines the title of the HTML document. This title is displayed in the browser's title bar or tab, and it's also used for bookmarking pages and in search engine results. It's placed within the <head> section of the HTML document.
---
## p Tag
The p tag in HTML defines a paragraph. Browsers automatically add a single blank line before and after each paragraph, creating a clear separation between blocks of text. It's a block-level element, meaning it occupies the full width available to it and starts on a new line.
---
## br Tag
The break tag in HTML creates a line break within a text block. It's used to start a new line without creating a new paragraph, effectively forcing the text that follows to appear on the next line. It is an empty element, meaning it has no closing tag.
---
## b / strong
The b and strong tags in HTML are used to make text appear bold. While both achieve a similar visual effect, the b tag is primarily for stylistic purposes, indicating text that should be visually distinguished without necessarily conveying importance. On the other hand, the strong tag signifies that the enclosed text has strong importance, seriousness, or urgency.
---
## pre
The pre tag in HTML represents preformatted text. Text inside a pre element is displayed in a fixed-width font, and it preserves both spaces and line breaks. This is useful for displaying code snippets, ASCII art, or any other text where formatting is important.
---
## Links
Links, also known as hyperlinks, are elements that connect one web resource to another. They allow users to navigate between different pages on the same website or to external websites. Links are created using the <a> (anchor) tag, and they can point to various types of resources, including HTML pages, images, documents, and more
---
# Grouping Text
div and span are HTML elements used to group other elements together. The div element is a block-level element, meaning it creates a distinct block on the page and typically starts on a new line. It's often used for larger structural groupings. The span element, on the other hand, is an inline element, meaning it flows within the surrounding text and doesn't create a new line. It's useful for styling or manipulating specific portions of text without disrupting the overall layout.

## div tag
The div element is a generic container for flow content, which in simpler terms means it's a way to group together other HTML elements. It doesn't inherently represent anything specific on its own, but it's commonly used to structure and style sections of a webpage. It has no effect on the content or layout until styled in some way using CSS (e.g., styling is directly applied to it, or some kind of layout model like Flexbox is applied to its parent element).
---
## span tag
The span element is an inline container used to mark up a part of a text, or a part of a document. It is used to group elements for styling purposes or because they share attributes such as lang or dir. It doesn't inherently represent anything on its own, but becomes useful when combined with CSS or JavaScript to target specific sections of text.
---
# Standard Attributes
## id Attribute
The id attribute in HTML provides a unique identifier for an element within a document. This identifier allows you to target and manipulate that specific element using CSS styles, JavaScript code, or even link directly to it using fragment identifiers in URLs (e.g., #section1). Each id value should be unique within the entire HTML document to ensure proper functionality.
---
## Class Attribute
The class attribute in HTML is used to specify one or more class names for an HTML element. These class names can then be used by CSS and JavaScript to style and manipulate specific elements or groups of elements that share the same class. Essentially, it's a way to categorize and target elements for styling and scripting purposes.
---
# Table Tag
## HTML Table Tag
The HTML table tag is used to create tables on web pages. It organizes data into rows and columns, similar to a spreadsheet. Within the table tag, you'll find tags like <tr> for table rows, th for table headers, and td for table data cells, which define the structure and content of the table.
---