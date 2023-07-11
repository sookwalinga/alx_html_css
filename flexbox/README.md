## Flexbox

**What is Flexbox?**
Flexbox, short for Flexible Box, is a CSS layout module that provides a more efficient way to lay out, align, and distribute space among items in a container[1]. It allows for easy resizing and repositioning of a flexible container and its items one-dimensionally[2]. Flexbox is designed for smaller-scale layouts and components of an application, while CSS Grid Layout is intended for larger-scale layouts[1].
**How to convert float positioning to a flex display**
To convert float positioning to a flex display, you can follow these steps:

1. Set the display property of the parent container to display: flex [3].
2. Remove the float property from the child elements[3].
3. Use flex properties such as flex-direction, justify-content, and align-items to achieve the desired layout and alignment[1].
   **How to horizontally and vertically align elements using Flexbox**
   To horizontally and vertically align elements using Flexbox, you can use the following properties on the parent container:
   • justify-content: center to horizontally align the items in the center of the container[1].
   • align-items: center to vertically align the items in the center of the container[1].
   **The difference between the main and cross axes**
   In Flexbox, there are two axes: the main axis and the cross axis[5].
   • The main axis is the primary axis along which flex items are laid out. It can be either horizontal (row) or vertical (column) depending on the flex-direction property[5].
   • The cross axis is perpendicular to the main axis. It is the axis that is orthogonal to the main axis[5].
   **Properties that work on flex elements vs flex container**
   There are different properties that can be applied to flex elements (flex items) and the flex container[1].
   • Properties that can be applied to flex elements include flex-grow, flex-shrink, and flex-basis, which control how the flex items grow, shrink, and establish their initial size[1].
   • Properties that can be applied to the flex container include flex-direction, justify-content, and align-items, which control the layout and alignment of the flex items within the container[1].
   **Shorthands for flex**
   There are shorthand properties available for working with flex in CSS[1].
   • flex is a shorthand property that combines flex-grow, flex-shrink, and flex-basis into a single declaration[1].
   • align-self is a shorthand property that allows you to override the align-items property for individual flex items[1].
   **How to create a new page with flex in mind**
   To create a new page with flex in mind, you can follow these steps:
4. Set the display property of the main container to display: flex [1].
5. Determine the desired layout and alignment of the elements on the page.
6. Use flex properties such as flex-direction, justify-content, and align-items to achieve the desired layout and alignment[1].
7. Apply flex properties to individual elements as needed to control their sizing and positioning within the flex container[1].
