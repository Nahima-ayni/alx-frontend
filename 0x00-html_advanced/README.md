---

# HTML5 Beginner Guide

## 1. Guidelines for HTML

- **Keep it simple and readable**: Write clean, readable code with proper indentation.
- **Use semantic tags**: Use HTML5 semantic tags to give meaning to your content.
- **Close your tags**: Always close your HTML tags to avoid errors.
- **Validate your HTML**: Use tools like the W3C Validator to check for errors.
- **Use lowercase for tags and attributes**: It's a good practice for consistency and readability.

## 2. Creating the Skeleton of an HTML5 Page

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document Title</title>
</head>
<body>
    <!-- Content goes here -->
</body>
</html>
```

## 3. Using Semantic HTML Tags to Structure a Web Page

Semantic tags provide meaning to the structure of your web page. Here are some common ones:

- `<header>`: Defines the header of a section or page.
- `<nav>`: Defines a navigation menu.
- `<main>`: Represents the main content of a document.
- `<section>`: Defines sections in a document.
- `<article>`: Represents an independent piece of content.
- `<aside>`: Defines content aside from the main content.
- `<footer>`: Defines the footer for a section or page.

## 4. Use Cases for `<div>` vs `<span>`

- `<div>`: A block-level element used to group larger chunks of content.
  ```html
  <div class="container">
      <p>Some content</p>
      <p>More content</p>
  </div>
  ```
- `<span>`: An inline element used to group small pieces of text within a line.
  ```html
  <p>This is a <span class="highlight">highlighted</span> text.</p>
  ```

## 5. Semantic Values of HTML5 Tags

- **`<header>`**: The introductory section of a document or section.
- **`<main>`**: The main content area of a document.
- **`<footer>`**: The footer of a document or section.
- **`<article>`**: A self-contained composition in a document.
- **`<nav>`**: A section containing navigation links.
- **`<section>`**: A thematic grouping of content.
- **`<aside>`**: Content aside from the main content, such as sidebars.

## 6. Using Headings and Hierarchical Order

Headings (from `<h1>` to `<h6>`) are used to define the structure of your document. They should be used in a hierarchical order:

```html
<h1>Main Title</h1>
<h2>Subsection Title</h2>
<h3>Sub-subsection Title</h3>
```

Following the hierarchical order helps with accessibility and SEO.

## 7. Making Lists in HTML

### Unordered List
```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
```

### Ordered List
```html
<ol>
    <li>First item</li>
    <li>Second item</li>
    <li>Third item</li>
</ol>
```

### Definition List
```html
<dl>
    <dt>Term</dt>
    <dd>Definition of the term</dd>
</dl>
```

## 8. Differences Between Media Types (SVG, GIF, PNG, JPG)

- **SVG (Scalable Vector Graphics)**: Resolution-independent and scalable without losing quality.
- **GIF (Graphics Interchange Format)**: Supports animations and transparency, limited to 256 colors.
- **PNG (Portable Network Graphics)**: Supports transparency, lossless compression, good for images with text or sharp lines.
- **JPG (Joint Photographic Experts Group)**: Best for photographs, lossy compression, no transparency support.

## 9. Structuring Data in a Table

```html
<table>
    <thead>
        <tr>
            <th>Header 1</th>
            <th>Header 2</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Data 1</td>
            <td>Data 2</td>
        </tr>
    </tbody>
</table>
```

## 10. Integrating a Video in a Webpage

```html
<video controls>
    <source src="movie.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
```

## 11. Integrating an Audio File in a Webpage

```html
<audio controls>
    <source src="audio.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
</audio>
```

## 12. Embedding External Content

### Using `<iframe>`

```html
<iframe src="https://example.com" width="600" height="400"></iframe>
```

### Using `<embed>`

```html
<embed src="https://example.com" width="600" height="400">
```

## 13. Correctly Structuring an HTML Page

Here’s a comprehensive example:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Webpage</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Webpage</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="home">
            <h2>Home</h2>
            <p>This is the home section.</p>
        </section>
        <section id="about">
            <h2>About</h2>
            <article>
                <h3>About Me</h3>
                <p>Some information about me.</p>
            </article>
        </section>
        <aside>
            <h2>Side Content</h2>
            <p>This is some side content.</p>
        </aside>
    </main>
    <footer>
        <p>&copy; 2024 My Webpage</p>
    </footer>
</body>
</html>
```

