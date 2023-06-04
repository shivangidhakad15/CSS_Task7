# CSS_Task7
README for Hoverable Side Navigation in HTML with CSS
------------------------------------------------------

This README provides instructions on how to create a hoverable side navigation in HTML using CSS. Follow these steps to set up and customize your hoverable side navigation:

1. HTML Structure:
   - Begin by opening the HTML file where you want to create the hoverable side navigation.
   - Inside the `<body>` element, create a `<div>` or `<nav>` element to represent the side navigation.
   - Within the navigation element, add `<a>` elements to create the navigation links.
   - Use appropriate IDs or classes for the navigation element and links to apply CSS styling later.

2. CSS Styling:
   - Open your CSS file or create a new one.
   - Select the navigation element using its ID or class and apply desired styling. For example:
     ```css
     #sidenav {
       width: 200px;
       background-color: #f2f2f2;
       padding: 20px;
     }
     ```
   - Style the navigation links within the side navigation using their IDs or classes. For example:
     ```css
     .nav-link {
       display: block;
       padding: 10px;
       text-decoration: none;
       color: #333;
     }
     ```
   - Customize the styles further by adding properties like font size, font color, hover effects, or other desired attributes.

3. Apply CSS to HTML:
   - In your HTML file, link the CSS file by adding the following line of code within the `<head>` section:
     ```html
     <link rel="stylesheet" href="path/to/your/css-file.css">
     ```
   - Replace `"path/to/your/css-file.css"` with the actual path to your CSS file.

4. Save and Preview:
   - Save both your HTML and CSS files.
   - Open the HTML file in a web browser to see the hoverable side navigation with the applied CSS styles.

Congratulations! You have successfully created and styled a hoverable side navigation in HTML using CSS. When the user hovers over the navigation, it should expand or display additional information. Feel free to customize the navigation further by adding additional links, adjusting the styles, or incorporating any desired features to suit your project's requirements.
