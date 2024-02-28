# week-3-HTML-CSS-INTRO
WHAT IS CSS?
Is a style sheet is like a css file that holds all style for your webpages.
To connect HTML and CSS you simply link them together(link rel="stylesheet" href="style.css")
HTML is all about recognizing commonly used element such as parahraph, headings, lists and links that defines the structure of a webpage.

CSS HAS TWO PARTS-the SELECTOR specifies a pattern in the html and if the pattern matches, the style within the DECLARATION block are applied to the corresponding html element.
It is possible to have multiple style applied to the same pattern, and that is where the cascading part of css comes into play.

CSS COMPONENT: 1.SELECTOR 2.PROPERTY 3.VALUE.
In declaration style consists of TWO part: A property and value.
WRITING A CLASS SELECTOR- A class is an attribute that can be added to any html element, providing additional details about that element.
In css we use a dot(.) before the class name to differentiate it from html element selectors.
If we want to style a specific part of a paragraph differently, we can use a span element with a class attribute.

DESCENDENT SELECTORS- html is organized like a family tree, where element have parent, children and descendents. The body tag is the parent, and the html element within it are the descendents.
A descendent selectors allows us to select lists items that are descendents of either an ordered or an unordered list. The relationship can be direct or indirect, similar to a family tree.
To apply the style using a descendant selector we can use the code "ol li"(without the body tag). "ol" and "li" signifies the descendant relationship. When working with css selector that involve multiple terms, it is important to remember that they are read from right to left, even although we write them from left to right.

IDENTIFY A COLOR SCHEME- The goal is to choose a color scheme or specific color for your website.
FORMATTING COLOR IN CSS- After selecting a color palette, the next step is to incorporate it into your code. It is important to note that your color palette may not include any named colors, and there are only around 130 of them available.
The most common way to represent colors online is through hex codes, also known as hex value or hex format. Hex is short for hexadecimal.
Hex has six digit long and consists of number zero to nine and letter A to F. Canva's color palettes also display hex value. Color names and hex value are the most commonly used methods for working with colors on the web.

UNDERSTANG IMAGES IN CSS- Images are frequently found on webpages. They can be added either html or css. 
There are various image formats: 1.GIF 2.PNG 3.JPEG
