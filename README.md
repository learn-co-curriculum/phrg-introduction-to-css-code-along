# Introduction

It's time to see some CSS code in action. [Codepen][] is a great tool to easily test HTML and CSS code and it's what we will use for our example.

This [Pen][] (saved [Codepen][] document) contains an HTML document with the following structure:

- a [`<body>`][] element (root of the html content. In [Codepen][] the body html element is implied. We will not see a body tag but it's implicitly present and it wraps all the HTML content)
- an [`<article>`][] tag to define our content as self-contained unit (e.g. blog post, newspaper article)
- an [`<h1>`][h tags] tag to wrap the [`<article>`]'s header text
- [`<p>`][] tags to wrap the [`<article>`]'s unstructured text
- [`<ul>`][] tags to represent un-ordered lists
- [`<li>`][] tags to wrap each list item

The [Pen][] also includes commented out CSS Code to (`/* this is a CSS comment */`):
- Set the background of the [`<body>`] element (whole document) to '#00b3e6' (light blue)
- Sets the [`<article>`] element width to 700px
- Centers the [`<article>`] element
- Sets the font family of the [`<article>`] element to 'Helvetica Neue'. Alternative fonts are provided in the event 'Helvetica Neue' is not available on your computer
- Set the background of the [`<article>`] element to 'white'
- Add 30px of white space to perimeter of the [`<article>`]
- Set the `font-size` to `22px` for the element with `id` `main-header`
- Set the `font-style` to `italic` for elements containing the class `perspective-questions`

# Code Along Instructions

View this [Pen][] in your browser. You should see a page similar to this:

![][Pen hompage]

We will modify the CSS code to transform the page from:

![][Unstyled page]

to:

![][Styled page]

All the CSS code you need to successfully modify the page is already included but commented out. All you need to do is un-comment all `CSS declarations` (`property-name`:`value`) one by one. See the screenshot below:

![][Uncomment instructions]   


[Codepen]: https://codepen.io/
[Pen]: https://codepen.io/curiositypaths/pen/WddzQM?editors=1100
[Pen homepage]: https://curriculum-content.s3.amazonaws.com/web-development/codepen.jpeg
[Unstyled page]: https://curriculum-content.s3.amazonaws.com/web-development/unstyled-codepen.jpeg
[Styled page]: https://curriculum-content.s3.amazonaws.com/web-development/styled-codepen.jpeg
[Uncomment instructions]: https://curriculum-content.s3.amazonaws.com/web-development/css-code-codepen.jpg
[`<body>`]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/body
[`<article>`]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/article
[h tags]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements
[`<p>`]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p
[`<ul>`]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul
[`<li>`]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/li
