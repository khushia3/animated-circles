# animated-circles
This HTML file creates a basic animation with four blurred circles positioned and animated using CSS.
The file starts with the DOCTYPE html declaration, specifying it's an HTML5 document.
An <html> element is defined with the language set to English (lang="en").
Inside the <html>, a <head> section contains:
Character encoding (<meta charset="UTF-8">) for proper display of various characters.
Viewport configuration (<meta name="viewport" content="width=device-width, initial-scale=1.0">) ensures the website adapts to different screen sizes.
A <title> element (currently "Document") to display the page title.
A link (<link rel="stylesheet" href="style.css">) to a CSS stylesheet (assuming it exists) for styling the HTML elements.
The <body> section contains the main content of the webpage:
Four empty <div> elements with unique IDs (hero1, hero2, hero3, hero4) serve as placeholders for the circles.
Following the <body> is a CSS style block (<style>...</style>) that defines the styles for various elements:
A universal selector (*) resets margins, padding, and font family for all elements.
html and body are set to 100% height and width to fill the viewport.
body has a 50px padding applied.
Each #heroN element (where N is 1 to 4) is styled with:
Specific height and width based on viewport width (vw).
Background color for each circle.
A 50% border-radius to create circles.
A blur filter to soften the edges.
Absolute positioning to allow overlapping circles.
An animation named "anime" applied.
The @keyframes anime block defines the animation behavior:
Over a duration of 3 seconds, the circles alternate between a 10% left/top and right/bottom translation.
Functionality:

When loaded in a web browser, this code displays four blurred circles of different sizes and colors. They are positioned absolute and animated with a smooth translation effect.
