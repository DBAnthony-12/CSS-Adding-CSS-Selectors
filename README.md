# CSS-Adding-CSS-Selectors

Writing Your First Comment and Element Selector:
---------------------------------------------------------------------------
Comments are used in programming and markup languages to annotate parts of the code making it easier to understand the purpose of various sections and elements affecting the execution of the code.
HTML Comment: <!---->.
CSS Comment: /* */

Element selector:
----------------------------------------------------------------------------
Element selector is fundamental concept in CSS, allowing you to apply styles to TML elements directly. It helps target tags and applies the defined styles to all instances of those elements within the HTML document.
Anyone starting out in web development must grasp these fundamentals. The basis for applying CSS styles to HTML texts is element selectors, whereas comments aid in the maintenance and comprehension of code.

Definition: 
---------------------------------------------------------------------------
Using an element tag names as guideline, CSS element selectors allow you to target HTML elements. It gives web developers an indication to apply styles to every occurrence of specific elements on a web page.
Syntax: The element selector syntax in CSS is the tag name of the HTML element preceded by a period (.).
Usage: element selectors are frequently used in CSS rules to apply styles to different HTML elements.
In conclusion, CSS element selectors enable programmers to apply styles consistently throughout a webpage and target HTML elements based on their tag names. They are an essential component of CSS styling and are widely used in web.

Writing a class selector:
----------------------------------------------------------------------------
 Writing a class selector in CSS allows you to target HTML elements based on their assigned class attributes.
Definition: 
A class selector in CSS can be used to target individual HTML elements that have been given a certain class property. Classes provide various styles of a webpage without affecting other elements.
Syntax: a class selector syntax is the class name followed by a period(.).
Usage: Class selectors are useful tools that are frequently used in CSS rules to apply styles to sets of items that have similar functions or patterns of design. Compared to element selectors alone, they enable more focused styling.

To put it briefly, you can apply styles to groups of elements and target HTML elements based on their class property by constructing a class selector in CSS. In CSS, class selectors are an effective technique for arranging styles, encouraging reuse, and establishing a unified look and feel throughout a webpage or website.

Example:
--------------------------------------------------------------
<p class="example">This is a paragraph with the "example" class.</p>
.example {
font-size: 16px;
    color: #333;
}

Grouping selectors:
-----------------------------------------------------------------
Grouping selectors and descendant selectors are both important in CSS that allows developers to target and style specific elements efficiently.

Grouping selectors: 
----------------------------------------------------------------
•	grouping selectors in CSS allow you to apply the same style to multiple selectors at once
•	grouping selectors are useful for reducing redundancy in CSS code and applying consistent styles to multiple elements that share similar characteristics.

Example:
-------------------------------------------------------------
•	h1, h2, h3 {
•	    color: blue;
•	    font-family: Arial, sans-serif;
•	}

•	In this example, styles are applied to h1, h2, h3 by the font-family elements to the document.

Descendant Selectors.
---------------------------------------------------------------
Are known as selectors in CSS and allow you to target elements that are descendant of another element.
Are known as a useful tool for applying styles to specific elements within a level structure such as nested list or sections within a web page.

Example:
-----------------------------------------------------------------
•	.container p {
•	    font-size: 14px;
•	}

•	In this example, the font size of 14 pixels is applied to all <p> elements that are descendant of an element with the class “container”.

Grouping selectors and descendant selectors can be combined to apply styles to a specific group of elements within a document efficiently.
	
Example:
-------------------------------------------------------------------
•	.sidebar h2, .sidebar h3 {
•	    color: green;
•	}

•	In this example, color green has been applied to al headings (h2, h3) elements hat are descendant of an elements with the class “sidebar”.

To sum up, descendant selectors let you target individual items inside a hierarchical structure, whereas grouping selectors let you apply the same styles to numerous selectors at once. It takes both strategies to write maintainable and effective CSS code.
