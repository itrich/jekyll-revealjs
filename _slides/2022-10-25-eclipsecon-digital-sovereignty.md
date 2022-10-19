---
layout: reveal
title: Digital sovereignty
---

## Welcome

Welcome to the jekyll-reveal.js example presentation.

---

## Slide 2

This is the second slide. And it's just another file inside the _posts-directory.

It is identified as slide 2, because it has a "2" after the mandatory date-part (0000-01-01) in its
filename. (It's called 0000-01-02-slides.md)

---

This is a third slide, although we're still in 0000-01-02-slides.md.

---

## Fragments

It's also possible to do fragments.

- Start the line with ‘+’ instead of ‘-’ for your fragment item like this:  
  `+ This is a fragment`
+ This is a fragment
+ Your fragment may contain the ‘+’ character
    + You can also indent fragments

<fragment/>You can use &lt;fragment/&gt; to step other content.

---

## Vertical Slides

Or

--

Even

--

Vertical

--

Slides

---

# Backgrounds

<background>green</background>

Or use different backgrounds.

&lt;background&gt;green&lt;/background&gt;

---

# Image Backgrounds

<backgroundimage>https://farm4.staticflickr.com/3743/11167478016_1714b57b28_b.jpg</backgroundimage>
<backgroundimageopacity>0.25</backgroundimageopacity>

You can also set image backgrounds.

&lt;backgroundimage&gt;
&#123;&#123; '/images/image.jpg' | relative_url &#125;&#125;/
&lt;/backgroundimage&gt;
&lt;backgroundimageopacity&gt;0.25&lt;/backgroundimageopacity&gt;

<small><a href="https://www.flickr.com/photos/31518985@N04/11167478016">"Light through autumn leaves, Alice Holt Forest, Surrey, UK"</a> by <a href="https://www.flickr.com/photos/31518985@N04">ambabheg</a> is licensed under <a href="https://creativecommons.org/licenses/by/2.0"> CC BY 2.0 </a></small>

---

# SVG Diagrams

<background>white</background>

You can use [mermaid-js](https://mermaid-js.github.io/mermaid/) to create SVG diagrams.

(enable the feature by setting `mermaid_diagrams` to `true` in `_config.yml`)

<!-- .element: style="font-size: 50%;" -->

<mermaid>
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
    D-->E
</mermaid>
<!-- .element: style="height: 250px;" -->

<!-- .element: style="font-size: 50%;" -->You can tweak the height of the diagram by following the closing tag with an [element attribute](https://revealjs.com/markdown/#element-attributes):  
`<!-- .element: style="height: 400px;" -->`
