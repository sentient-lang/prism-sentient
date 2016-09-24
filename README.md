## sentient.prism

[Prism](http://prismjs.com/) syntax highlighting for
[Sentient](http://sentient-lang.org/). For use in web pages.

You can view a demo
[here](https://sentient-lang.github.io/prism-sentient/demo/).

## Instructions

Add a link to the stylesheet inside `head`:

```html
<link href="sentient.prism.css" rel="stylesheet" />
```

Add the Prism library and this extension immediately before the `body` close
tag:

```html
<script src="prism.js"></script>
<script src="sentient.prism.js"></script>
```

Add a preformatted code block in the `body`:
```html
<pre>
  <code class="language-sentient">
    a = [1, 2, 3];
  </code>
</pre>
```

Note: You may wish to include the
[Normalize Whitespace](http://prismjs.com/plugins/normalize-whitespace/) plugin
to remove surplus whitespace.

## License

Copyright © 2016 Sentient Lang.

Distributed under the MIT License.
