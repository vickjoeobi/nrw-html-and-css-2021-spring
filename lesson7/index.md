---
title: Lesson 7 - HTML Forms
nav_order: 7
---

# HTML Forms

## Class Agenda

1. What are HTML Forms?
2. Form Tags (Part 1)

## 1. What are HTML forms?

- Allow us to get information from users
- Look at examples of forms on other websites
  - Sign up / Log in forms
  - Search Box
  - Contact Form
  - Payment Form

ETA: 15 mins

## 2. Form Tags (Part 1)

- There are many tags needed to make a working form. We will cover a few.
- `<form>`

  - All forms start with a <form> element. It is a container element like `<section>` but for containing forms.
  - Two important attributes of `<form>`:
    - action - defines the location (URL) where the form's collected data should be sent when it is submitted.
    - method - defines which HTTP method to send the data with

- `<input>`

  - used to create elements that specifically accept data (input) from the user
  - There are different types of input elements
    - `<input type="text">`
    - `<input type="email">`
    - `<input type="password">`
    - `<input type="search">`
    - `<input type="submit">`
      - similar to `<button>`. Any difference?
      - <button>.
    - See other input types [here](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input#input_types)

- `<label>`

  - this represents a caption for an item
  - importance of adding a <label> for an <input> element
    - A user can click the label to focus/activate the associated input
    - A screen reader will read out the label when a user interacts with it's input
  - the `for` attribute

- `<textarea>`
  - represents a multi-line plain-text editing
  - Note: This is not an empty element. It requires a closing tag.

- Task: Show an image of a contact form, and let students identify tags to be used for creating it.

```
content discussed in meeting

- Tags:
  - Must have:
      - <form>
      - <fieldset>
      - <label>
      - <input>
          - text
          - email
          - submit
      - <textarea>
      - <button>
  - Others:
    - <select>
    - <option>
    - Other inputs <input>
        - file
```

# Exercise Description

The project should just have a simple form on a Contact Me Page

- Name
- Email
- Message
- Submit

# Glossary & Terminology

- `html tag` - An html tag is
- `hypertext` - Hypertext means this and that
- `...` - ...

# Homework

For next session please prepare this and that, etc...

# Resources

(please make sure to give links)

- [MDN's HTML Forms Page](https://developer.mozilla.org/en-US/docs/Learn/Forms)
- ...
- ...
