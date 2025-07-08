# TASK 🚧

Create a HTML/CSS piece of news from any online news channel using the knowledge learned in class.
You must use a separated stylesheet file. Some elements that requires you to do your research and exploration at home:

1. Adding image using HTML `<img>` tag & using background-image CSS property. What's the difference?
2. Design using Google Font in your HTML / CSS.
3. Take time to make sure it's typographically beautiful. Get familiar with typography related CSS properties to do great styling.
4. Adding hyperlinks to link back to original sites.

# TUTORIAL ✏️

## Adding Image

### `<img>` tag

The `<img>` tag is used to embed an image in an HTML page.

**Link:** [https://www.w3schools.com/tags/tag_img.asp](https://www.w3schools.com/tags/tag_img.asp)

### Background Image

You can include image into HTML elements using `background image: url(abc.jpg);` in CSS as well. Try both, and see what's the difference in practical usage? (_Hint:_ Which one allows users to Right click > Save as? )

**Link:** [https://www.w3schools.com/cssref/pr_background-image.php](https://www.w3schools.com/cssref/pr_background-image.php)

## Custom Fonts

There are a few ways for you to include non-system fonts to your web page.

### Google Font

Google Font or font delivery is probably the easiest. You just need to pick and choose from font collection and follow instruction step-by-step.
![GoogleFont](https://cdn.glitch.global/784c396d-eaae-4d0d-a70a-a2f88fdc68df/google-font.png?v=1719660919796)

**Link:** [https://fonts.google.com/knowledge/using_type/using_web_fonts_from_a_font_delivery_service](https://fonts.google.com/knowledge/using_type/using_web_fonts_from_a_font_delivery_service)

### Custom Font

Manually adding webfonts (WOFF files) using CSS syntax.

**Link:** [https://fonts.google.com/knowledge/using_type/using_web_fonts](https://fonts.google.com/knowledge/using_type/using_web_fonts)

## Learning about Web Typography

Web typography builds on top of your knowledge about typography in visual design.
It takes practice to perfect. Here are some useful materials

**Link:**
[https://fonts.google.com/knowledge/using_type/the_foundations_of_web_typography](https://fonts.google.com/knowledge/using_type/the_foundations_of_web_typography)
[https://readymag.com/almanac/typography/](https://readymag.com/almanac/typography/)
[https://typographyprinciples.obys.agency/](https://typographyprinciples.obys.agency/)

## Adding Hyperlinks

### The `<a>` tag

Basically, hyperlinks are links to internal/external page. The `<a>` tag allow you to add hyperlinks. Unlike regular tags, it needs attributes to work as intended. Please check out:

**Link:** [https://www.w3schools.com/tags/tag_a.asp](https://www.w3schools.com/tags/tag_a.asp)

The most important one are `href` and `target`.
For example:
`<a href="www.rmit.edu.vn" target="_blank">RMIT University</a>`

### Internal, External Link

**Internal:**
Internal links are links between pages in your website. It should open the page in the SAME tab. For example:
`<a href="about.html">ABOUT</a>`

**External:**
External links are links to pages outside your website. It should open in a DIFFERENT tab. For example:
`<a href="www.rmit.edu.vn" target="_blank">RMIT University</a>`

**Mailto:**
Link to an email. For example: `<a href="mailto:someone@example.com">Send email</a>`

**Anchor:**
Link to move to a section inside the same page. For example: `<a href="#section2">Go to Section 2</a>`

### Styling Hyperlinks

Links can be customized at all of their states. Using what we call pseudo class. Don't worry, it looks complicated, but just copy & paste really.

**Link:** [https://www.w3schools.com/css/css_link.asp](https://www.w3schools.com/css/css_link.asp)
