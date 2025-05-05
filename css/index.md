What is CSS?
CSS stands for Cascading Style Sheets.

It is a stylesheet language used to describe the presentation and layout of documents written in HTML or XML.

CSS controls how web elements look-such as colors, fonts, spacing, and positioning-across different devices and media.

Why Use CSS?
Separates content (HTML) from presentation (CSS), making websites easier to maintain and update.

Allows consistent styling across multiple web pages by linking to a single stylesheet file.

Makes web pages more visually appealing and responsive to different screen sizes.

How CSS Works
CSS uses rulesets to target HTML elements and apply styles.

A ruleset consists of a selector (which element to style) and a declaration block (what styles to apply).

Example:

css
p {
  color: red;
  font-size: 18px;
}
Here, p is the selector, and the declarations set the text color and size for all <p> elements.

CSS Syntax Basics
Selector: Targets the HTML element(s) to style.

Property: The aspect of the element to style (e.g., color, margin).

Value: The setting for that property (e.g., red, 10px).

Declaration: A property-value pair, separated by a colon and ending with a semicolon.

Ruleset: Selector plus curly braces containing one or more declarations.

The Box Model
Most HTML elements are treated as rectangular boxes.

Box model properties:

content: The actual text or image.

padding: Space around the content.

border: Line around the padding.

margin: Space outside the border.

How CSS is Applied
Inline: Directly in the HTML element (not recommended for maintainability).

Internal: Inside a <style> tag in the HTML <head>.

External: In a separate .css file, linked to the HTML (best practice).

Key Features
Controls layout, colors, fonts, spacing, backgrounds, and more.

Supports responsive design for different devices.

Enables animations and transitions.
