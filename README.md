# Hugo shortcode: preview html/css snippet

Hugo shortcode to showcase HTML/CSS snippets.

Shows two panels with HTML and CSS, and a panel rendering the
given HTML and CSS. An alternative to embedding a Codepen.

More info & demos: [Hugo Shortcode: HTML/CSS snippet preview](https://arcomul.nl/posts/tech/hugo-shortcode-html-css-snippet-preview)

## Setup

- Include `snippet.html` in Hugo layouts/shortcodes folder.
- Include content of `snippet.css` in CSS.

## Usage

Initiate a snippet preview in the following format:

```html
{{< snippet preview-only="true|false" height=Number|300 >}}
<style>
  h1 {
    color: red;
  }
</style>
<div>
  <h1>Hello world!</h1>
</div>
{{< /snippet >}}
```
