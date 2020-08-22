Prepare file index.html

```bash
$ touch index.html
```

Add to this file:
```html
<p>Hello, world!</p>
```

Open it:
```bash
$ open index.html
```

The prototypical HTML skeleton begins with an html tag containing two elements, a head and a body. These latter tags are nested inside the html tag, as follows:

```html
<html>
  <head>
  </head>
  <body>
  </body>
</html>
```
Useful tags:

<p>paragraph</p>

<strong>bold</strong>

<em>italics</em> 

<em><strong>bold_and_italic</strong></em>

<a href="https://learnenough.com/email">link</a>

<a href="https://learnenough.com/email"><em>link_and_italic</em></a>

<img src="https://lh3.googleusercontent.com/M1XTibfCgpi5pgjSDb7kXDh21N8fpn-8evzQVAX-qGFhSyArDmSuCAv1pjVp4jbAt_g=w412-h220-rw" alt="image">

<a href="https://learnenough.com/email">
  <img src="https://lh3.googleusercontent.com/M1XTibfCgpi5pgjSDb7kXDh21N8fpn-8evzQVAX-qGFhSyArDmSuCAv1pjVp4jbAt_g=w412-h220-rw" alt="An adorable kitten">
</a>

<code>code_tag</code>

<table>
  <tr>
    <th>Tag</th>
    <th>Name</th>
    <th>Purpose</th>
  </tr>
</table>

<div>block_element</div>
<span>inline_element</span>

<ol>
  <li>ordered_list_element_1</li>
  <li>ordered_list_element_2</li>
  <li>ordered_list_element_3</li>
</ol>

<ul>
  <li>unordered_list_element_1</li>
  <li>unordered_list_element_2</li>
  <li>unordered_list_element_3</li>
</ul>

<!DOCTYPE html>
<html>
  <head>
    <title>Navigation menu presentation</title>
    <meta charset="utf-8">
  </head>
  <body>

    <div>
      <a href="index.html">Home</a>
      <a href="moby_dick.html">Moby Dick</a>
      <a href="tags.html">HTML Tags</a>
    </div>

Style in html:

```html
 <table style="width: 100%;">
```

Style in CSS:
```css
  table {
    width: 100%;
  }
```

<blockquote style="font-style: italic; font-size: 20px;">
</blockquote>