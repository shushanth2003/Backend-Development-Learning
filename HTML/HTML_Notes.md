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
# p Tag
The p tag in HTML defines a paragraph. Browsers automatically add a single blank line before and after each paragraph, creating a clear separation between blocks of text. It's a block-level element, meaning it occupies the full width available to it and starts on a new line.