Fundamental Frontend
====================

semantic meaning using markup

# HTML
* browsers try to fix your tags if there is an error
* HTML5 -> introduce new parsing algorithm
* Graceful degragation

# Browser storage
* cookies -> 5kbs info
* web storage API -> 5mbs. Needs javascript.
    * Local Storage
    * Session Storage

# Html structure
* Doctype; Important for html version.
* language: important for accents, search engines `<html lang="en"`.

# Semantic
* `<b>` or `<strong>`: Important thing
* `<i>` or `<em>`: Get attention

# Tags and Attributes
Take a look at them in `w3schools.com/tags`.

# Content categories
* Flow content
* Sectioning Content
* Heading Content
* Phrasing Content

*GOOD TOOL: `https://caniuse.com/`.*

# Document Outline

# Accessibility

A11Y: `https://a11yproject.com`.

Exercise: `https://a11yproject.com/posts/skip-nav-links/`.

# Search Engine Optimization (SEO)

* Page Speed
* Correct heading structure
...
* SiteMap
* optimize images
* Metadata

*Useful properties for entities, in order to improve your search accuracy*: `https://schema.org/Person`.

*Testing Tool:* `https://search.google.com/structured-data/testing-tool/u/0/`.

# Fundamental Front-End Day 2/2

## CSS

### Browser defaults & Normalise/CSS reset

Better for Normalise rather than Reset.

### Pseudo and combinations

* `:link`
* `:hover`
* `:checked`
* `:focus`
* `:active`
* `:required`

### Pseudo elements

* `::after`
* `::before`
* `::first-letter`
* `::first-line`
* `::selection`

### Other attributes selectors

* 

## Unit

## Specifity or SpeciFISHty

## Box Model

https://codepen.io/fundamental-frontend/

## Positioning and flow

* Normal flow: by default
* Floating flow: `https://codepen.io/fundamental-frontend/pen/ajdEdL`.
* Positioning flow:
    * Border box: `https://codepen.io/fundamental-frontend/pen/YjQzYj`.

## Accessibility

`sr-only`: The .sr-only class hides an element to all devices except screen readers

```css
.sr-only {
    position: absolute;
    margin: -1px 0 0 -1px;
    padding: 0;
    display: block;
    width: 1px;
    height: 1px;
    font-size: 1px;
    line-height: 1px;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    border: 0;
    outline: 0;
}
```

```html
    <a href="#" target="_blank">
        Click to Open Site
        <span class="sr-only">This is an external link</span>
    </a>
```