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

[Back to top](#semantic-html-and-css)

## Example (semantic)


[Back to top](#semantic-html-and-css)

# Common Semantic HTML Elements

This is a guide to the most common **semantic HTML elements**, their meaning, when to use them, and examples.

## `<header>`

**Semantic meaning:** Introductory content for a page or section. Often includes a title, logo, or navigation.

**When to use it:** At the beginning of a webpage or article.

**Example:**

```html
```

[Back to top](#semantic-html-and-css)

## `<nav>`

**Semantic meaning:** A navigation menu with links to other parts of the site or page.

**When to use it:** For main site navigation or in-page navigation.

**Example:**

```html
```

[Back to top](#semantic-html-and-css)

## `<main>`

**Semantic meaning:** The main content of the page. Should only appear once per page.

**When to use it:** Wrap the unique content of the current page.

**Example:**

```html
```

[Back to top](#semantic-html-and-css)

## `<section>`

**Semantic meaning:** A thematic grouping of content, typically with a heading.

**When to use it:** To divide your content into logical blocks.

**Example:**

```html
```

[Back to top](#semantic-html-and-css)

## `<article>`

**Semantic meaning:** A self-contained piece of content that can stand alone.

**When to use it:** For blog posts, news articles, product descriptions, etc.

**Example:**

```html
```

[Back to top](#semantic-html-and-css)

## `<aside>`

**Semantic meaning:** Content related to the main content, but not part of it.

**When to use it:** For sidebars, tips, related links, etc.

**Example:**

```html
```

[Back to top](#semantic-html-and-css)

## `<footer>`

**Semantic meaning:** Footer of a page or section. Usually includes copyright, links, or contact info.

**When to use it:** At the bottom of a page or article.

**Example:**

```html
```

[Back to top](#semantic-html-and-css)

## `<h1>` to `<h6>`

**Semantic meaning:** Headings to structure content hierarchically.

**When to use them:** Use `<h1>` for the main title, then `<h2>`.. for subsections, etc. Only use one `<h1>` per page.

**Example:**

```html
```

[Back to top](#semantic-html-and-css)

## `<p>`

**Semantic meaning:** A paragraph of text.

**When to use it:** To separate blocks of text.

**Example:**

```html
```

[Back to top](#semantic-html-and-css)

## `<ul>`, `<ol>`, `<li>`

**Semantic meaning:** Lists (unordered and ordered).

**When to use them:** For groups of related items.

**Example:**

```html
```

[Back to top](#semantic-html-and-css)

## `<img>`

**Semantic meaning:** An image.

**When to use it:** To display a relevant image, always with alt text for accessibility.

**Example:**

```html
```

[Back to top](#semantic-html-and-css)

## `<a>`

**Semantic meaning:** A hyperlink.

**When to use it:** To link to another page or part of the same page.

**Example:**

```html
```

[Back to top](#semantic-html-and-css)

## `<div>` and `<span>`

**Semantic meaning:** None – these are generic containers.

**When to use them:** When no semantic element fits, or for styling/layout purposes.

**Example:**

```html
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
```

```html
```

[Back to top](#semantic-html-and-css)

## CSS Rules

A **CSS rule** defines how an HTML element should be styled. Each rule is made up of a **selector** and a **declaration block**.

### Syntax:

```
selector {
  property: value;
  property: value;
}
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

```css
```

[Back to top](#semantic-html-and-css)

## Selectors

**Selectors** define which HTML elements a style rule applies to.

### Types of selectors:

- **Type**: `p`, `h1`, `ul`
- **Class**: `.highlight`, `.card`
- **ID**: `#main-header`
- **Group**: `h1, h2, h3`
- **Descendant**: `section p`
- **Attribute**: `input[type="text"]`
- **Pseudo-class**: `a:hover`, `li:first-child`
- **Pseudo-element**: `p::before`

**Example:**

```css
```

This targets any element with class `title` inside an element with class `card`.

[Back to top](#semantic-html-and-css)

## Specificity

**Specificity** determines which CSS rule is applied when multiple rules target the same element. Higher specificity wins.

There is a **built-in points system** in the browser that compares how specific a selector is:

- ID selectors count as **100 points**
- Class selectors, attributes, and pseudo-classes count as **10 points**
- Type selectors and pseudo-elements count as **1 point**
- Inline styles are even stronger (roughly **1000 points**)
- `!important` overrides almost everything (but should be avoided)

The browser adds these up for each selector. The one with the highest total wins if there's a conflict.

### Specificity hierarchy:

1. Type selectors (`p`, `div`) → 1 point each
2. Class selectors (`.btn`), attributes (`[type="text"]`), pseudo-classes (`:hover`) → 10 points each
3. ID selectors (`#header`) → 100 points each
4. Inline styles → 1000 points
5. `!important` → forces override unless another rule with `!important` has higher specificity

### Specificity example:

```css
```

### Tips

- More selectors = higher specificity

- Inline styles override most CSS

- Try to avoid !important unless absolutely necessary

[Back to top](#what-is-semantic-meaning-in-html)
