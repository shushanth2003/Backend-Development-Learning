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