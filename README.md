# HTML:
```html
<img src='data:image/svg+xml;utf8,<svg ... > ... </svg>'>
```
Drop the svg-element and be sure to use single qoutes on the `src`.

# CSS:
```css
.bg {
  background: url('data:image/svg+xml;utf8,<svg ...> ... </svg>');
}
```