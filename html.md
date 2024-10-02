# HTML: Hypertext Markup Language

## Table of Contents
1. [Introduction](#introduction)
2. [What is Markup?](#what-is-markup)
3. [Hello World Example](#hello-world-example)
4. [HTML Syntax](#html-syntax)
5. [Key Attributes](#key-attributes)
6. [Important Notes for Professionals](#important-notes-for-professionals)
7. [Additional Resources](#additional-resources)

## Introduction

HTML (Hypertext Markup Language) is the backbone of the web. It extends any document, in any language, with structured, multimedia, and interactive markup, transforming it into a dynamic digital document, webpage, website, or app.

Key features of HTML include:
- Structured content (e.g., [`<title>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/title), [`<h1>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements))
- Multimedia support (e.g., [`<video>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video), [`<audio>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/audio), [`<img>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img))
- Interactive elements (e.g., [`<input>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input), [`<canvas>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/canvas))

## What is Markup?

A markup language is a declarative programming language that extends written natural language. Markup languages have **semantics** because they build upon the inherent meaning in natural language.

## Hello World Example

```html
<!-- ./hello-world.html -->
<!DOCTYPE html>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width">
Hello, World!
```

For a detailed explanation of this structure, refer to [web.dev's HTML document structure guide](https://web.dev/learn/html/document-structure).

## HTML Syntax

Basic HTML syntax includes:

- Comments: `<!-- comment -->`
- Unicode character references: `&#x` + $UNICODE + `;`
- Styling: `<style>` for CSS
- Scripting: `<script type="module">` for JavaScript
- Elements: `<tagname>content</tagname>` or `<tagname />`

## Key Attributes

### `lang` Attribute

The `lang` attribute sets the language of the markup using [IETF language tags](https://en.wikipedia.org/wiki/IETF_language_tag). It can include real and fantasy languages:

- `lang="en-GB"` - British English
- `lang="gsw-u-sd-chzh"` - [Zürich German](https://en.wikipedia.org/wiki/Z%C3%BCrich_German)
- `lang="x-sga"` - [Minecraft Enchanting Table](https://minecraft.wiki/w/Enchanting_Table#Standard_Galactic_Alphabet)

### `class` Attribute

The `class` attribute extends elements with semantic meaning:

```html
<button class="signup">Sign Up</button>
<button class="signin">Sign In</button>
<button class="signout">Sign Out</button>
```

## Important Notes for Professionals

- HTML is not XHTML (HTML in XML syntax)
- HTML is not JSX (HTML-like syntax in JavaScript)
- The current HTML standard is WHATWG's HTML5, not W3C's HTML4
- A merger between Mozilla and WHATWG may lead to HTML6 in the future

## Additional Resources

- [Official WHATWG HTML Specification](https://html.spec.whatwg.org/)
- [MDN Web Docs HTML Reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference)
- [web.dev Learn HTML Course](https://web.dev/learn/html)
- [WHATWG HTML GitHub Repository](https://github.com/whatwg/html)

This README provides an overview of HTML. For in-depth information and implementation details, please consult the official documentation and resources linked above.
