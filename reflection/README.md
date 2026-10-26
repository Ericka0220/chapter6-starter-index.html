# Chapter 6 Reflection

### 1. How do padding, border, and margin differ? Explain with an example from your own page.

Padding is the space inside an element between the content and the border. A border goes around the element, while margin creates space outside the border between other elements. On my page, I used padding to add space inside sections and margin to separate them.

### 2. What is the practical difference between `width`, `min-width`, and `max-width`?

The `width` property sets the preferred width of an element. The `min-width` property prevents an element from becoming too narrow, while `max-width` prevents it from becoming too wide. These properties help make a webpage look better on different screen sizes.

### 3. Why might you choose an RGBA background color instead of using `opacity` on the whole element?

RGBA allows me to make just the background color transparent without affecting the content inside the element. Using `opacity` on the whole element also makes text, images, and other content transparent. RGBA is useful when I want a see-through background while keeping the text easy to read.

### 4. What did you observe when testing `background-size: cover` versus `contain`?

When I tested `background-size: cover`, the background image filled the entire area, but some parts of the image could be cropped. With `contain`, the entire image remained visible, but empty spaces could appear around it. I would use `cover` when I want a full background and `contain` when showing the complete image is more important.

### 5. What CSS adjustment made the biggest improvement in your design? Why?

Adding padding and adjusting margins made one of the biggest improvements to my design. These changes gave the content more space and made the page look cleaner and easier to read. I learned that small CSS adjustments can make a big difference in the overall appearance of a webpage.