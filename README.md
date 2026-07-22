# 📘 HTML & CSS Interview Questions and Answers

This repository contains the most frequently asked **HTML & CSS interview questions** with simple and easy-to-understand answers.

---

# 📑 HTML Interview Questions

## 1. What is HTML?

**Answer:**

HTML (HyperText Markup Language) is the standard markup language used to create the structure of web pages. It defines elements such as headings, paragraphs, links, images, forms, and tables.

---

## 2. What is HTML5?

**Answer:**

HTML5 is the latest version of HTML. It introduced semantic tags (`<header>`, `<footer>`), multimedia support (`<audio>`, `<video>`), Canvas, SVG, localStorage, and many new form input types.

---

## 3. What is the difference between HTML and HTML5?

| HTML | HTML5 |
|------|-------|
| Older version | Latest version |
| No audio/video support | Supports audio & video |
| No semantic tags | Semantic tags available |
| Limited form controls | New input types |

---

## 4. What are HTML tags?

**Answer:**

HTML tags are predefined keywords enclosed within angle brackets (`<>`) that define the structure and content of a webpage.

Example:

```html
<h1>Hello World</h1>
```

---

## 5. What is an HTML element?

**Answer:**

An HTML element consists of a start tag, content, and an end tag.

Example:

```html
<p>This is a paragraph.</p>
```

---

## 6. What is the difference between tags and elements?

**Answer:**

| Tag | Element |
|-----|---------|
| `<p>` | `<p>Hello</p>` |
| Only markup | Complete structure |

---

## 7. What are HTML attributes?

**Answer:**

Attributes provide additional information about HTML elements.

Example:

```html
<img src="image.jpg" alt="Nature">
```

Here `src` and `alt` are attributes.

---

## 8. What is the purpose of `<!DOCTYPE html>`?

**Answer:**

It tells the browser that the document is written in HTML5 and ensures standards mode rendering.

---

## 9. What is the difference between id and class?

| id | class |
|----|-------|
| Unique | Can be reused |
| Uses # selector | Uses . selector |
| One per page | Multiple elements |

---

## 10. What are semantic tags?

**Answer:**

Semantic tags describe the meaning of the content instead of its appearance.

Examples:

- `<header>`
- `<nav>`
- `<main>`
- `<section>`
- `<article>`
- `<footer>`

---

## 11. What are non-semantic tags?

**Answer:**

These tags do not describe their content.

Examples:

```html
<div>
<span>
```

---

## 12. What is the difference between div and span?

| div | span |
|------|------|
| Block element | Inline element |
| Used for layouts | Used for inline styling |

---

## 13. What are block elements?

**Answer:**

Block elements always start on a new line and occupy the full available width.

Examples:

```html
<div>
<p>
<h1>
<section>
```

---

## 14. What are inline elements?

**Answer:**

Inline elements occupy only the required width and do not start on a new line.

Examples:

```html
<span>
<a>
<strong>
<img>
```

---

## 15. What are HTML entities?

**Answer:**

HTML entities display reserved characters.

Examples:

```html
&lt;
&gt;
&amp;
&nbsp;
&copy;
```

---

## 16. What is iframe?

**Answer:**

An iframe embeds another webpage inside the current webpage.

Example:

```html
<iframe src="https://example.com"></iframe>
```

---

## 17. What is localStorage?

**Answer:**

localStorage stores data permanently in the browser until it is manually removed.

Methods:

```javascript
localStorage.setItem()
localStorage.getItem()
localStorage.removeItem()
```

---

## 18. What is sessionStorage?

**Answer:**

sessionStorage stores data only until the browser tab is closed.

---

## 19. Difference between localStorage and sessionStorage?

| localStorage | sessionStorage |
|--------------|----------------|
| Permanent | Temporary |
| Shared across tabs | Tab-specific |
| Larger storage | Smaller storage |

---

## 20. Why are semantic tags important?

**Answer:**

- Improve SEO
- Better accessibility
- Easier maintenance
- Cleaner code

---

# 🎨 CSS Interview Questions

## 1. What is CSS?

**Answer:**

CSS (Cascading Style Sheets) is used to style HTML elements. It controls colors, layouts, spacing, fonts, and responsiveness.

---

## 2. What are the types of CSS?

**Answer:**

- Inline CSS
- Internal CSS
- External CSS

---

## 3. Which CSS type is recommended?

**Answer:**

External CSS because it improves maintainability, reusability, and page performance.

---

## 4. What are CSS selectors?

**Answer:**

Selectors target HTML elements for styling.

Examples:

- Element
- Class
- ID
- Universal
- Attribute
- Grouping

---

## 5. What is the CSS Box Model?

**Answer:**

The Box Model consists of:

- Content
- Padding
- Border
- Margin

---

## 6. Difference between Margin and Padding?

| Margin | Padding |
|---------|----------|
| Outside border | Inside border |
| Transparent | Background color applies |

---

## 7. What is box-sizing?

**Answer:**

It defines how an element's width and height are calculated.

Values:

```css
content-box
border-box
```

---

## 8. Difference between block, inline, and inline-block?

| Block | Inline | Inline-block |
|--------|--------|--------------|
| New line | Same line | Same line |
| Width works | Width ignored | Width works |
| Height works | Height ignored | Height works |

---

## 9. What is display:flex?

**Answer:**

It creates a Flexbox container for one-dimensional layouts.

```css
display:flex;
```

---

## 10. What is justify-content?

**Answer:**

It aligns flex items along the main axis.

Common values:

- flex-start
- center
- flex-end
- space-between
- space-around
- space-evenly

---

## 11. What is align-items?

**Answer:**

It aligns flex items along the cross axis.

---

## 12. What is CSS Grid?

**Answer:**

CSS Grid is a two-dimensional layout system used to arrange content in rows and columns.

```css
display:grid;
```

---

## 13. Difference between Flexbox and Grid?

| Flexbox | Grid |
|----------|------|
| One-dimensional | Two-dimensional |
| Best for components | Best for page layouts |

---

## 14. What is position?

**Answer:**

The `position` property specifies how an element is positioned.

Values:

- static
- relative
- absolute
- fixed
- sticky

---

## 15. Difference between relative and absolute?

| Relative | Absolute |
|----------|----------|
| Keeps original space | Removes original space |
| Relative to itself | Relative to nearest positioned ancestor |

---

## 16. What is z-index?

**Answer:**

It controls the stacking order of overlapping elements. Higher values appear on top.

---

## 17. What is overflow?

**Answer:**

It controls what happens when content exceeds an element's size.

Values:

- visible
- hidden
- scroll
- auto

---

## 18. What is transform?

**Answer:**

The `transform` property changes an element's position, size, rotation, or shape.

Functions:

- translate()
- rotate()
- scale()
- skew()

---

## 19. What is transition?

**Answer:**

It creates smooth animations between property changes.

Example:

```css
transition: all 0.3s ease;
```

---

## 20. What are pseudo-classes and pseudo-elements?

**Answer:**

### Pseudo-classes

Target an element in a specific state.

Examples:

- `:hover`
- `:focus`
- `:active`
- `:visited`

### Pseudo-elements

Style a specific part of an element.

Examples:

- `::before`
- `::after`
- `::first-letter`
- `::first-line`

---

# ⭐ Topics Covered

- HTML Basics
- HTML5
- Semantic HTML
- Forms
- Tables
- CSS Basics
- Box Model
- Flexbox
- Grid
- Position
- Transform
- Transition
- Pseudo Classes
- Pseudo Elements
- Interview Questions

---

⭐ **If you found this repository helpful, don't forget to Star it!**
