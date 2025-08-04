# Semantic HTML and CSS

<details open>
  <summary>Menu – Jump to Section</summary>

- [What is Semantic Meaning in HTML?](#what-is-semantic-meaning-in-html)

- [Why Use Semantic HTML?](#why-use-semantic-html)

- [Example (non-semantic)](#example-non-semantic)

- [Example (semantic)](#example-semantic)

- [Common Semantic HTML Elements](#common-semantic-html-elements)

  - [`<header>`](#header)
  - [`<nav>`](#nav)
  - [`<main>`](#main)
  - [`<section>`](#section)
  - [`<article>`](#article)
  - [`<aside>`](#aside)
  - [`<footer>`](#footer)
  - [`<h1>` to `<h6>`](#h1-to-h6)
  - [`<p>`](#p)
  - [`<ul>`, `<ol>`, `<li>`](#ul-ol-li)
  - [`<img>`](#img)
  - [`<a>`](#a)
  - [`<div>` and `<span>`](#div-and-span)

- [Summary - Semantic HTML](#summary---semantic-html)

- [CSS]()

  - [Cascading Style Sheets](#cascading-style-sheets)
  - [CSS Rules](#css-rules)
  - [Box Model](#box-model)
  - [Selectors](#selectors)
  - [Specificity](#specificity)

  </details>

## What is Semantic Meaning in HTML?

**Semantic HTML** means using HTML elements according to their **intended purpose and meaning**, rather than just for visual layout.

Instead of using generic containers like `<div>` or `<span>` for everything, you use meaningful tags like `<header>`, `<nav>`, `<article>`, and `<footer>` to describe the **role** of each section of the content.

## Why Use Semantic HTML?

- **Clarity for developers** – Code is easier to read and understand
- **Accessibility** – Screen readers and assistive tech can navigate the page more accurately
- **SEO (Search Engine Optimization)** – Search engines can better understand your content
- **Maintainability** – Well-structured markup is easier to scale and modify
- **Standards-based development** – Follows modern web best practices

  [Back to top](#semantic-html-and-css)

## Example (non-semantic)

```html
<div class="top">
  <div class="menu">Some content</div>
</div>
```

[Back to top](#semantic-html-and-css)

## Example (semantic)

```html
<header class="top">
  <nav class="menu">Links to other pages</nav>
</header>
```

# Comments in HTML

```html
<!-- This is a comment in HTML -->
```

[Back to top](#semantic-html-and-css)

# Common Semantic HTML Elements

This is a guide to the most common **semantic HTML elements**, their meaning, when to use them, and examples.

## `<header>`

**Semantic meaning:** Introductory content for a page or section. Often includes a title, logo, or navigatrion.

**When to use it:** At the beginning of a webpage or section/article.

**Example:**

```html
<header>
  <h1>My Blog</h1>
  <nav>
    <a>Home</a>
    <a>Contact</a>
    <a>About</a>
  </nav>
</header>
```

[Back to top](#semantic-html-and-css)

## `<nav>`

**Semantic meaning:** A navigation meny with links to other parts of the site or page.

**When to use it:** For main site navigation or in-page navigation.

**Example:**

```html
<nav>
  <a href="/">Home</a>
  <a href="/contact">Contact</a>
  <a href="/about">About</a>
</nav>
```

[Back to top](#semantic-html-and-css)

## `<main>`

**Semantic meaning:** The main content of the page _( html page )_. Should only appear once per page.

**When to use it:** Wrap the unique content of the current page.

**Example:**

```html
<main>
  <h1>Our services</h1>
  <p>We offer web development and design</p>
</main>
```

[Back to top](#semantic-html-and-css)

## `<section>`

**Semantic meaning:** A thematic grouping of content, typically with a heading.

**When to use it:** To divide your content into logical blocks.

**Example:**

```html
<main>
  <h1>The anti social company!</h1>

  <section>
    <h2>About us</h2>
    <p>Something awesome about us</p>
  </section>

  <section>
    <h2>Contact</h2>
    <p>Contact us via the telephone! We hate social media!</p>
  </section>
</main>
```

[Back to top](#semantic-html-and-css)

## `<article>`

**Semantic meaning:** A self-contained piece of content that can stant alone.

**When to use it:** For blog posts, news articles, product descriptions etc.

**Example:**

```html
<section class="posts">
  <article class="post">This is article #1</article>

  <article class="post">This is article #2</article>
</section>
```

[Back to top](#semantic-html-and-css)

## `<aside>`

**Semantic meaning:** Content related to the main content, but not part of it.

**When to use it:** For sidebars, tips, related links, swipe-in-content etc.

**Example:**

```html
<aside>
  <h3>Wuick Tip</h3>
  <p>Use semantic element to imporve accessibilty</p>
</aside>
```

[Back to top](#semantic-html-and-css)

## `<footer>`

**Semantic meaning:** Footer of a page or section. Usually includes copyright information, links or contact info.

**When to use it:** At the bottom of a page or articles or similar.

**Example:**

```html
<footer>
  <p>&copy; 2025 My Website</p>
</footer>
```

[Back to top](#semantic-html-and-css)

## `<h1>` to `<h6>`

**Semantic meaning:** Headings to structure content hierarchically.

**When to use them:** Use `<h1>` for the main title, then `<h2>` for subsections and so on. Only use one `<h1>` per page.

**Example:**

```html
<h1>Main title</h1>
<h2>Subsection</h2>
<h3>Detail</h3>
```

[Back to top](#semantic-html-and-css)

## `<p>`

**Semantic meaning:** A paragraph of text

**When to use it:** To seperate blocks of text.
**Example:**

```html
<p>This is a paragraph explaining something important.</p>
```

[Back to top](#semantic-html-and-css)

## `<ul>`, `<ol>`, `<li>`

**Semantic meaning:** Lists (unordered and ordered).

**When to use them:** For groups of related items.

**Example:**

```html
<ul>
  <li>Milk</li>
  <li>Eggs</li>
  <li>Bread</li>
</ul>
```

[Back to top](#semantic-html-and-css)

## `<img>`

**Semantic meaning:** An image.

**When to use it:** To display a relevant image, always with alt text for accessibility.

**Example:**

```html
<img src="pikachu.png" alt="Image of Pikachu" />
```

[Back to top](#semantic-html-and-css)

## `<a>`

**Semantic meaning:** A hyperlink.

**When to use it:** To link to another page or part of the same page.

**Example:**

```html
<a href="https://example.com">Visit our site</a>
```

[Back to top](#semantic-html-and-css)

## `<div>` and `<span>`

**Semantic meaning:** None – these are generic containers.

**When to use them:** When no semantic element fits, or for styling/layout purposes.

**Example:**

```html
<div class="card">
  <span class="highlight">Important</span>
</div>
```

[Back to top](#semantic-html-and-css)

## Summary - Semantic HTML

Using semantic HTML makes your code cleaner, more accessible, and easier to maintain.  
Try to always choose the element that best reflects the **meaning** of your content.

Here is a link to all the elements that exist: [HTML Element Reference - w3Schools](https://www.w3schools.com/tags/default.asp)

[Back to top](#semantic-html-and-css)

## Cascading Style Sheets

**CSS (Cascading Style Sheets)** is used to describe the look and formatting of HTML elements. The “cascading” part means that styles are applied in order of importance based on specificity and order of appearance.

### Key concepts:

- CSS is separate from structure (HTML)
- You can apply styles inline, in a `<style>` tag, or via an external `.css` file
- Later rules or more specific selectors override earlier ones

**Example:**

```css
p {
  color: darkblue;
}
```

```html
<p>This text will be dark blue.</p>
```

[Back to top](#semantic-html-and-css)

## CSS Rules

A **CSS rule** defines how an HTML element should be styled. Each rule is made up of a **selector** and a **declaration block**.

### Syntax:

```

```

![CSS Rule Diagram](https://assets.digitalocean.com/articles/how-to-build-a-website-with-css/css-diagram.png)

Here is a link to all existing CSS properties: [CSS Reference](https://www.w3schools.com/CSSref/index.php)

[Back to top](#semantic-html-and-css)

## Box Model

Every HTML element is treated as a rectangular box made up of:

1. **Content** – the actual text or element
2. **Padding** – space between content and border
3. **Border** – wraps around the padding (and content)
4. **Margin** – space between the element and others

![CSS Box Model](https://tse4.mm.bing.net/th/id/OIP.A5RSZrRcN7JACdsswC1VBgHaFE?pid=Api)

### Visual order:

```

[margin]
[border]
[padding]
[content]

```

**Example:**

```html
<div id="some-id" class="box">Box 1</div>
```

```css
/* Style by element */
div {
  padding 20px
}

/* Style by class */
.box {
  margin: 10px; /* Give all sides the same margin */
  padding: 10px;
  border: 2px solid black; /*  border-width, border-style and border-color*/
}
```

[Back to top](#semantic-html-and-css)

## Selectors

**Selectors** define which HTML elements a style rule applies to.

### Types of selectors:

- **Element**: `p`, `h1`, `ul`
- **Class**: `.highlight`, `.card`
- **ID**: `#main-header`
- **Group**: `h1, h2, h3`
- **Descendant**: `section p`
- **Attribute**: `input[type="text"]`
- **Pseudo-class**: `a:hover`, `li:first-child`
- **Pseudo-element**: `p::before`

**Example:**

```css
.card .title {
  font-weight: bold;
}
```

This targets any element with class `title` inside an element with class `card`.

[Back to top](#semantic-html-and-css)

## Specificity

**Specificity** determines which CSS rule is applied when multiple rules target the same element. Higher specificity wins.

There is a **built-in points system** in the browser that compares how specific a selector is

- ID selectors count as **100 points**
- Class selectors, attributes, and pseudo-classes count as **10 points**
- Type selectors and pseudo-elements count as **1 point**
- Inline styles are even stronger (roughly **1000 points**)
- `!important` overrides almost everything (but should be avoided)

The browser adds these up for each selector. The one with the highest total wins if there's a conflict.

### Specificity example:

```css
p {
  color: black;
} /* (0, 0, 1) → 1 point */

.article p {
  color: gray;
} /* (0, 1, 1) → 11 points */

#main .article p {
  color: blue;
} /* (1, 1, 1) → 111 points */
```

### Tips

- More selectors = higher specificity

- Inline styles override most CSS

- Try to avoid !important unless absolutely necessary

[Back to top](#what-is-semantic-meaning-in-html)
