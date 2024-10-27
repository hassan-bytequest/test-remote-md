# HTML Basics Tutorial 2

## Table of Contents
1. [Introduction to HTML](#introduction-to-html)
2. [HTML Document Structure](#html-document-structure)
3. [Basic HTML Tags](#basic-html-tags)
4. [Creating Lists](#creating-lists)
5. [Adding Links](#adding-links)
6. [Working with Images](#working-with-images)
7. [HTML Forms](#html-forms)

---

### 1. Introduction to HTML

HTML stands for **HyperText Markup Language** and is the standard language for creating web pages. It describes the structure of a webpage and is made up of elements (tags) that define the content and layout.

### 2. HTML Document Structure

Every HTML document should start with the `<!DOCTYPE html>` declaration to define the document type. Here’s the structure of a basic HTML document:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Title</title>
</head>
<body>
    <h1>Hello, World!</h1>
    <p>This is a basic HTML document.</p>
</body>
</html>
```

- `<!DOCTYPE html>`: Defines the document type as HTML5.
- `<html>`: The root element of an HTML document.
- `<head>`: Contains meta-information about the document, such as the title.
- `<body>`: Contains the content of the webpage.

### 3. Basic HTML Tags

- **Headings**: HTML provides six levels of headings, from `<h1>` (largest) to `<h6>` (smallest).

  ```html
  <h1>Main Heading</h1>
  <h2>Subheading</h2>
    ```

- **Paragraphs**: Use the `<p>` tag to define a paragraph.

  ```html
  <p>This is a paragraph of text.</p>
    ```

- **Bold and Italic**: Use `<strong>` or `<b>` for bold text and `<em>` or `<i>` for italicized text.

  ```html
  <strong>Bold text</strong> and <em>italic text</em>.
    ```

### 4. Creating Lists

HTML supports ordered (numbered) and unordered (bullet-point) lists.

- **Unordered List**:

  ```html
  <ul>
      <li>Item 1</li>
      <li>Item 2</li>
      <li>Item 3</li>
  </ul>
    ```

- **Ordered List**:

  ```html
  <ol>
      <li>First item</li>
      <li>Second item</li>
      <li>Third item</li>
  </ol>
    ```

### 5. Adding Links

Links are created using the `<a>` tag. The `href` attribute defines the URL.

```html
<a href="https://www.example.com">Visit Example</a>
```

- `target="_blank"` can be used to open the link in a new tab:

  ```html
  <a href="https://www.example.com" target="_blank">Open in a new tab</a>
    ```

### 6. Working with Images

To add an image, use the `<img>` tag with `src` (source) and `alt` (description) attributes.

```html
<img src="image.jpg" alt="Description of image">
```

- `width` and `height` attributes can be used to set the image size.

  ```html
  <img src="image.jpg" alt="Description" width="300" height="200">
    ```

### 7. HTML Forms

Forms allow user input and are created with the `<form>` tag.

```html
<form action="/submit" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name">

    <label for="email">Email:</label>
    <input type="email" id="email" name="email">

    <button type="submit">Submit</button>
</form>
```

- **Form Attributes**:
- `action`: The URL to send form data.
- `method`: Specifies HTTP method (`get` or `post`).

---

This is a basic guide to HTML to help you get started. Happy coding!


