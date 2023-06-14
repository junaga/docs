[book]: https://web.dev/learn/html
[book_hello_world]: https://web.dev/learn/html/document-structure
[ref]: https://developer.mozilla.org/en-US/docs/Web/HTML/Reference
[repo]: https://github.com/whatwg/html
[spec]: https://html.spec.whatwg.org/

[language]: https://en.wikipedia.org/wiki/Writing_system
[lang]: https://en.wikipedia.org/wiki/IETF_language_tag
[zuerich_german]: https://en.wikipedia.org/wiki/Z%C3%BCrich_German
[enchanting_table]: https://minecraft.wiki/w/Enchanting_Table#Standard_Galactic_Alphabet

[title]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/title
[h1]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements
[p]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p
[a]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a
[input]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input
[img]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img
[audio]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/audio
[video]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video
[canvas]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/canvas

# [/whatwg/html][repo] - [MDN][ref]

HTML - _Hypertext Markup Language_, extends any document, in any language, with structured ([`<title>`][title]), multimedia ([`<video>`][video]), interactive ([`<input>`][input]), markup, into a, _magic_, digital document, or (web)page, (web)site, or app.

### What is Markup

A markup language, is, a declarative programming language, that is a superset of [written natural language][language]. Markup languages have **semantics** because natural language does.

### Note for pros

HTML is not XHTML, XHTML is HTML in XML. HTML is not JSX, JSX is HTML in JS. HTML is not W3C/HTML, W3C made HTML4. Only WHATWG/HTML, HTML5, is HTML. Until Mozilla merges with WHATWG into HTML6.

## Hello World

```html
<!-- ./hello-world.html -->
<!DOCTYPE html>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width">

Hello, World!
```

Read [web.dev/learn/html/document-structure][book_hello_world] to understand this ~~mess~~ history.

## Syntax

- `<!-- comment  -->` - Comment
- `&#x` + $UNICODE + `;` - Escape
- `<style>` - CSS
- `<script type="module">` - JS

### `lang` Attribute

The markup's language is set with the [IETF language tag][lang]. It includes fantasy languages prefixed with `x-`.

- `lang="en-GB"` - British English
- `lang="gsw-u-sd-chzh"` - [Zuerich German][zuerich_german]
- `lang="x-sga"` - [Minecraft Enchanting Table][enchanting_table]

### `class` Attribute

Extends elements with semantic meaning.

- `<button class="signup">`
- `<button class="signin">`
- `<button class="signout">`

## See also

Learn HTML [web.dev/learn/html](https://web.dev/learn/html)
