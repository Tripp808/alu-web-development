# CSS Basics 

This readme provides an overview of the CSS styles used in the project.

## File Structure

The CSS styles are organized in the following files:

- `base.css`: This file contains the base styles that are shared across all HTML files in the project.
- `styles.css`: This file contains additional styles specific to each HTML file.

## Usage

To apply the CSS styles to the HTML files, ensure that the following lines are included within the `<head>` tag of each HTML file:

<link href="base.css" rel="stylesheet">
<link href="styles.css" rel="stylesheet">
```
The base.css file provides a set of foundational styles, while the styles.css file contains specific styles for each HTML file.

## **Customization**
You can customize the appearance of the website by modifying the CSS styles in the styles.css file. This includes changing colors, backgrounds, borders, font styles, and other visual properties.

Feel free to experiment and make adjustments as per your preferences to create a unique and personalized look for your website.

## Logo

To add a logo to the top-left of the page, you can utilize a Unicode character. In the HTML code, add the Unicode character within the first <li> tag of the <header> element, like this:

php
Copy code
<li class="logo">&#x2600;</li>
You can adjust the size of the logo by applying the appropriate CSS styles to the .logo class in the styles.css file.

## Note

Note
Please refrain from modifying the layout strategy implemented with CSS Flexbox, as it ensures the proper arrangement and responsiveness of the website. Focus on customizing the visual styles and appearance while keeping the existing layout intact.

Make sure to save the changes and refresh the webpage to see the updated CSS styles in action.

Enjoy customizing your website and creating a unique visual experience for your users!
