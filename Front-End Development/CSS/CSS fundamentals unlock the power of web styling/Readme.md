# CSS Crash Course & Cheat Sheet

> A practical, beginner-friendly summary of essential CSS concepts – perfect for quick reference or GitHub documentation.

## What is CSS?
CSS (Cascading Style Sheets) is a **style language** used to control the presentation (appearance) of markup languages like HTML. While HTML defines the structure of a web page, CSS defines how it looks.

### Key Benefits:
- Separates content (HTML) from presentation (CSS)
- Allows global styling from a single location
- Enables responsive design for different devices

---

## Ways to Apply CSS:
1. **Inline Styles** – Inside an HTML tag via `style="..."`
2. **Internal Styles** – Inside a `<style>` block in HTML `<head>`
3. **External Style Sheets** – In a separate `.css` file, linked via `<link>`

**Note:** Multiple style sources can be combined due to the **cascading** nature of CSS.

### Cascade Order (from least to most specific):
1. External stylesheets
2. Embedded styles
3. Inline styles
4. `!important` overrides

---

## CSS Syntax
```css
selector {
  property: value;
}
```
Example:
```css
p {
  color: blue;
  font-size: 16px;
}
```
### Comments:
```css
/* This is a comment */
```

---

## Selectors
- **Type Selector**: `p`, `h1`, `ul`
- **Class Selector**: `.classname`
- **ID Selector**: `#idname` (must be unique)
- **Descendant Selector**: `div span {}`

### Combinators:
- `A B` – descendant
- `A > B` – direct child
- `A + B` – adjacent sibling
- `A ~ B` – general sibling

---

## CSS Box Model
Each HTML element is treated as a box:
- `content` – the actual text/image
- `padding` – space around content
- `border` – wraps padding
- `margin` – space outside border

### Box Sizing
- `content-box` (default)
- `border-box` (includes padding & border in total size)

---

## Text & Fonts
- `font-family`
- `font-size`
- `font-weight`
- `font-style`

### Web Fonts
- `@font-face`
- `@import`
- `<link>` to Google Fonts

---

## Colors
**Properties**:
- `color`
- `background-color`
- `border-color`

**Value Types**:
- Named colors: `red`, `black`
- Hex: `#FF0000`
- RGB: `rgb(255, 0, 0)`
- RGBA: `rgba(255, 0, 0, 0.5)`
- HSL: `hsl(0, 100%, 50%)`

---

## Layout Techniques
### Older:
- Tables
- Floats & Clearfix

### Modern:
- **Flexbox** (1D layout – row or column)
- **Grid** (2D layout – rows and columns)

### Flexbox Example:
```css
display: flex;
flex-direction: row;
justify-content: space-between;
align-items: center;
```

### Grid Example:
```css
display: grid;
grid-template-columns: 1fr 1fr;
gap: 20px;
```

---

## Responsive Design
- Media Queries:
```css
@media (max-width: 768px) {
  body {
    font-size: 14px;
  }
}
```
- Units:
  - `px` – absolute
  - `%`, `em`, `rem` – relative

---

## Specificity & Cascade
| Selector Type  | Specificity |
|----------------|-------------|
| Element        | 0,0,1       |
| Class          | 0,1,0       |
| ID             | 1,0,0       |

### Tips:
- The more specific rule wins
- Later declarations override earlier ones
- Avoid `!important` unless necessary

---

## Best Practices
- Use meaningful class/ID names
- Comment generously
- Split large CSS files
- Use consistent formatting
- Normalize or Reset styles (e.g., `normalize.css`)

---

## Useful Tools
- [Can I use](https://caniuse.com)
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
- [CSS Lint](https://csslint.net/)
- [CSS Beautifier & Minifier](https://www.freeformatter.com/css-beautifier.html)

---

## Popular CSS Frameworks
- [Bootstrap](https://getbootstrap.com)
- [Tailwind](https://tailwindcss.com)
- [Foundation](https://get.foundation)

---

## References & Credits
This cheat sheet is created as part of a personal study and documentation practice.

---

> "CSS is what makes the web beautiful."
