---
title: Lesson 5 - HTML Tags 2
nav_order: 5
---

# HTML Tags 2

## Class Agenda

1. Div, Span and Section
2. Lists
3. Anchor (Hyperlinks)
4. Images
5. Base

## 1. Div, Span, and Section

-   The concept of block and inline elements was introduced in Lesson 3. The teacher should revise it with the students again and show examples.
-   Explain characteristics of a block and inline elements. <https://www.w3schools.com/html/html_blocks.asp>
-   Explain `<div>` as a block level non-semantic element.
-   When to use a div: when you can't find an appropriate semantic element.
-   Explain `<span>` as an inline level non-semantic element.
    -   Example: `<p><span>Some text</span></p>`
-   Explain `section>` as block level semantic element.

ETA: 15 mins

## 2. Lists

-   Unordered lists `<ul>`
-   Ordered lists `<ol>`
-   Nesting lists
-   Task: Create a list of items

```html
<p>Here are my Hobbies:</p>
<ul>
    <li>Dancing</li>
    <li>Singing</li>
</ul>
```

ETA: 15 mins

## 3. Anchor

-   What is a hyperlink? This was covered briefly in [Lesson 2 Glossary](../lesson2/#glossary--terminology`)
-   Anatomy of a link
    -   `<a>content to click</a>`
    -   href attribute
    -   target attribute
-   Explanation of linking to URLs and Paths (Absolute and Relative)
    -   `<a href="http://www.google.com">Visit Google</a>`
    -   `<a href="contacts.html">contacts page</a>`
    -   `<a href="projects/index.html">project homepage</a>`
    -   `<a href="../files/cv.pdf">My CV</a>`
    -   E-mail links: `<a href="mailto:me@gmail.com">Email me!</a>`
-   Task: Creating a navigation menu
    -   Create a list items to form a navigation
    -   Change the text to hyperlinks
    -   Create HTML pages for each navigation link

ETA: 35 mins

## 4. Images

-   The <img> element
-   src attribute
    -   `<img src="photo.jpg">`
    -   `<img src="photos/selfie.jpg">`
    -   `<img src="https://en.wikipedia.org/wiki/Germany#/media/File:Flag_of_Germany.svg">`
-   Warning: Be careful when linking to images on the web that are not yours. To avoid Copyright Violations.
-   alt attribute: `<img alt="A portrait of me" src="photo.jpg">`
-   Width and height attributes. (Warning: Aspect Ratio)

ETA: 20 mins

## 5. Base Element
- <base href="https://www.w3schools.com/">
- <base href=".">

ETA: 15 mins

# Exercise Description

Exercises should be done along while explaining the tags, by following the Tasks. After completing the Tasks, you should have content similar to `lesson5/Checkpoint5`

# Glossary & Terminology

-   `Ordered lists` - are lists in which the order of the items does matter. ([MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals))
-   `Unordered lists` - are used to mark up lists of items for which the order of the items doesn't matter. ([MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals))

---

# Homework

-   Create a Shopping list that looks like [this image]() // TODO: Add image
-   Add a list of your social media accounts to the footer
-   Read about other attributes used with the `<a>` tags

# Resources

-   [MDN HTML Text Fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)
-   [MDN Anchor Element Page](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a)
