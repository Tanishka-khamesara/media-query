# media-query
hosted link-> https://tanishka-khamesara.github.io/media-query/coffee.html

![Screenshot (118)](https://github.com/Tanishka-khamesara/media-query/assets/127411985/8f7ea9b1-5454-444e-8bcc-7c37513dc13a)
![Screenshot (119)](https://github.com/Tanishka-khamesara/media-query/assets/127411985/4cd6fa2b-764f-4c4c-9004-d00e64f21b8b)
![Screenshot (120)](https://github.com/Tanishka-khamesara/media-query/assets/127411985/81aea329-e6bd-4034-9e4f-8d6edaed971f)
![Screenshot (121)](https://github.com/Tanishka-khamesara/media-query/assets/127411985/f805e491-39bc-484e-9c56-5691a9bfd90a)
![Screenshot (122)](https://github.com/Tanishka-khamesara/media-query/assets/127411985/75809960-315e-4623-b1a0-6134fd00d7de)
<body>: The <body> element contains the main content of the web page, including text, images, and buttons.

<img>: This <img> tag inserts an image into the web page. It has attributes such as src (the image source URL), alt (alternative text for the image, useful for accessibility), and class (assigns the "image" class to the image, which can be used for styling with CSS).

<main class="main">: This <main> element defines the main content section of the web page and assigns the "main" class to it. This class can be used for styling or scripting purposes.

<h1>: This is a top-level heading (the largest heading) with the text "Certified Coffee Courses."

<p>: These <p> elements represent paragraphs of text. The Lorem Ipsum text is used as placeholder text.

<span>: This <span> element is nested within a paragraph and is used to enclose the text "Freepik," which might be a credit or attribution for the image.

<button>: This <button> element creates a button with the text "LEARN MORE." It can be used for interactive purposes on the web page, such as triggering an action when clicked.

Overall, this HTML document provides the structure and content for a web page with a title, an image, a heading, paragraphs of text, and a "Learn More" button. The appearance and layout of the page can be further customized and styled using CSS, which is linked to this HTML file via the "style.css" stylesheet.

Here's an explanation of the CSS code:

The * selector applies the following styles to all elements on the page. It sets the margin to 0, uses the border-box box-sizing model, and specifies the font family as Roboto and sans-serif as a fallback.

Styles for the overall page (body):

It sets the height of the body to 100vh (viewport height) and limits the width to a maximum of 90% of 1200px, centering the content both horizontally and vertically using CSS Grid and the place-content and align-items properties.
It applies a linear gradient background.
Defines a grid layout with two areas: 'image' and 'main'.
Sets a 1rem gap between elements within the grid.
Styles for the image (.image):

It specifies that elements with the class "image" should occupy the "image" grid area.
It sets the image's width to 25vw (viewport width) for desktop screens and 50vw for tablets.
Styles for the main content (.main):

It specifies that elements with the class "main" should occupy the "main" grid area.
Styles the heading (h1) with a specific font size, margin, and width.
Styles for specific elements like paragraphs (p), spans (span), and buttons (button) are defined.

There are two media queries for different screen sizes:

Tablet Screen (601px to 900px): Adjusts the background gradient, image width, and heading size.
Mobile Screen (0px to 600px): Reconfigures the grid layout, adjusts the background gradient, and modifies the image height, heading size, and paragraph font size for smaller screens.
These media queries ensure that the page's layout and styles adapt to various screen sizes, making the design responsive and user-friendly.
