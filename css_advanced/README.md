# CSS ADVANCED

## What is CSS?

CSS (Cascading Style Sheets) is a style sheet language used to describe the presentation and styling of HTML or XML documents. It allows you to define how elements should appear on a webpage, including their layout, colors, fonts, and other visual aspects.

## How to add style to an element?

To add style to an HTML element, you can use CSS by either inline styling, internal styling, or external styling.

Inline styling: Apply styles directly to an HTML element using the style attribute, like <div style="color: blue;">.
Internal styling: Define styles within the <style> tags in the <head> section of an HTML document.
External styling: Link an external CSS file to your HTML document using the <link> tag, like <link rel="stylesheet" href="styles.css">.

## What is a class?

In CSS, a class is a reusable identifier that allows you to apply styles to multiple elements. By assigning a class name to one or more HTML elements, you can target and style them collectively using CSS. Class names are preceded by a dot (.), like .my-class.

## What is a selector?

A selector is a CSS pattern used to select and target specific HTML elements for styling. It defines the elements to which a set of CSS rules should apply. Selectors can be based on element names, class names, IDs, attributes, or hierarchical relationships between elements. For example, the selector h1 targets all <h1> elements, while .my-class targets all elements with the class name "my-class".

## How to compute CSS Specificity Value?

CSS specificity determines which CSS rule should be applied to an element when conflicting rules exist. It is computed based on the type of selectors used in the CSS rules. Specificity is usually represented as a four-part value, where each part has a different weight:

Inline styles have the highest specificity.
IDs have a higher specificity than classes or element selectors.
Classes and attribute selectors have a higher specificity than element selectors.
The universal selector (\*) has the lowest specificity.

## What are Box properties in CSS?

Box properties in CSS refer to the properties that define the dimensions and spacing of an element's content box, including its width, height, padding, border, and margin. Some commonly used box properties include width, height, padding, border, and margin. These properties allow you to control the size, positioning, and spacing of elements on a webpage.

## How does the browser load a webpage?

When a browser loads a webpage, it follows a series of steps:

Parsing: The browser reads the HTML markup of the webpage and constructs the Document Object Model (DOM) tree, representing the structure of the page.
CSS styling: The browser applies the styles defined in the CSS to the appropriate elements in the DOM, creating the Render Tree.
Layout: The browser calculates the position and size of each element on the page, known as layout or reflow.
Painting: The browser renders the final appearance of the webpage based on the layout, applying colors, images, borders, and other visual aspects.
Display: The rendered webpage is displayed on the user's screen.
These steps happen quickly and continuously to provide the user with an interactive and visually appealing browsing experience.
