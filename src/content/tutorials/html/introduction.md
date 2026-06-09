---

title: "HTML Introduction"
category: "HTML"
order: 1
description: "Learn what HTML is and how HTML is used to create web pages."
---------------------------------------------------------------------------

# HTML Introduction

HTML is the first step to learn web development.

HTML is used to create the structure of a web page.

A website is made with different technologies:

* HTML creates the structure
* CSS adds design and style
* JavaScript adds actions and interactivity

In this lesson, you will learn the basic meaning of HTML.

---

## What is HTML?

HTML means **HyperText Markup Language**.

HTML is not a programming language.

HTML is a markup language.

It is used to create content on a web page, such as:

* Headings
* Paragraphs
* Images
* Links
* Lists
* Tables
* Forms
* Buttons

---

## Simple Example

```html
<h1>Hello World</h1>
<p>This is my first web page.</p>
```

Output:

# Hello World

This is my first web page.

---

## Why do we use HTML?

We use HTML to tell the browser what to show on the screen.

For example:

```html
<h1>About Me</h1>
<p>My name is Kunal. I am learning HTML.</p>
```

The browser reads the HTML code and displays the content as a web page.

---

## What is a Tag?

A tag is a special HTML word written inside angle brackets.

Example:

```html
<h1>
```

Most HTML tags have an opening tag and a closing tag.

Example:

```html
<h1>Hello</h1>
```

Here:

* `<h1>` is the opening tag
* `Hello` is the content
* `</h1>` is the closing tag

---

## Basic HTML Page Structure

Every HTML page has a basic structure.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Page</title>
  </head>

  <body>
    <h1>Hello World</h1>
    <p>This is my first HTML page.</p>
  </body>
</html>
```

---

## Explanation

### `<!DOCTYPE html>`

This tells the browser that the file is an HTML document.

### `<html>`

This is the main root of the HTML page.

### `<head>`

This part contains page information.

It is not directly shown on the page.

### `<title>`

This shows the page title in the browser tab.

### `<body>`

This part contains the visible content of the webpage.

Everything inside the body is shown on the screen.

---

## HTML File Extension

HTML files are saved with `.html`.

Example:

```text
index.html
about.html
contact.html
```

The homepage of a website is usually named:

```text
index.html
```

---

## Create Your First HTML File

Step 1: Open VS Code.

Step 2: Create a new file.

Step 3: Save the file as:

```text
index.html
```

Step 4: Write this code:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Website</title>
  </head>

  <body>
    <h1>Hello World</h1>
    <p>I am learning HTML.</p>
  </body>
</html>
```

Step 5: Open the file in your browser.

---

## Important Points

* HTML is used to create web pages.
* HTML uses tags.
* HTML files end with `.html`.
* HTML content is shown in the browser.
* HTML works with CSS and JavaScript.

---

## Practice Task

Create a new HTML file and add:

* One heading
* One paragraph
* Your name
* Your learning goal

Example:

```html
<h1>My First Web Page</h1>
<p>My name is Kunal.</p>
<p>I want to learn web development.</p>
```

---

## Mini Quiz

### 1. What does HTML mean?

HTML means HyperText Markup Language.

### 2. Is HTML a programming language?

No. HTML is a markup language.

### 3. Which tag is used for the biggest heading?

```html
<h1>
```

### 4. Which file extension is used for HTML files?

```text
.html
```

### 5. Which part shows visible content on the webpage?

```html
<body>
```

---

## Summary

HTML is used to create the structure of a website.

It is the base of every web page.

Before learning CSS and JavaScript, you should first understand HTML clearly.
