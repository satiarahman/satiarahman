# Markdown Formatting Guide

## Overview
This guide covers the essential Markdown formatting syntax for creating well-structured, readable documents.

---

## Headings

Markdown supports six levels of headings using hash symbols (`#`):

```markdown
# Heading 1 (H1)
## Heading 2 (H2)
### Heading 3 (H3)
#### Heading 4 (H4)
##### Heading 5 (H5)
###### Heading 6 (H6)
```

**Best Practice:** Use only one H1 per document as the main title.

---

## Text Formatting

### Bold
Use double asterisks or double underscores:

```markdown
**bold text** or __bold text__
```

Result: **bold text**

### Italic
Use single asterisks or single underscores:

```markdown
*italic text* or _italic text_
```

Result: *italic text*

### Bold and Italic
Use triple asterisks or triple underscores:

```markdown
***bold and italic*** or ___bold and italic___
```

Result: ***bold and italic***

### Strikethrough
Use double tildes:

```markdown
~~strikethrough text~~
```

Result: ~~strikethrough text~~

---

## Lists

### Unordered Lists
Use hyphens (`-`), asterisks (`*`), or plus signs (`+`):

```markdown
- Item 1
- Item 2
  - Nested item 2.1
  - Nested item 2.2
- Item 3
```

Result:
- Item 1
- Item 2
  - Nested item 2.1
  - Nested item 2.2
- Item 3

### Ordered Lists
Use numbers followed by periods:

```markdown
1. First item
2. Second item
   1. Nested item 2.1
   2. Nested item 2.2
3. Third item
```

Result:
1. First item
2. Second item
   1. Nested item 2.1
   2. Nested item 2.2
3. Third item

### Task Lists
Use checkboxes with square brackets:

```markdown
- [x] Completed task
- [ ] Incomplete task
- [ ] Another incomplete task
```

Result:
- [x] Completed task
- [ ] Incomplete task
- [ ] Another incomplete task

---

## Links and URLs

### Inline Links
```markdown
[Link text](https://example.com)
```

Result: [Link text](https://example.com)

### Links with Titles
```markdown
[Link text](https://example.com "hover title")
```

### Reference Links
```markdown
[Link text][reference]

[reference]: https://example.com
```

### Automatic Links
```markdown
<https://example.com>
<user@example.com>
```

---

## Images

### Basic Image
```markdown
![Alt text](image-url.jpg)
```

### Image with Link
```markdown
[![Alt text](image-url.jpg)](https://example.com)
```

### Image with Size (HTML)
```markdown
<img src="image-url.jpg" width="200" height="200" alt="Alt text">
```

---

## Code

### Inline Code
Use single backticks:

```markdown
This is `inline code` in a sentence.
```

Result: This is `inline code` in a sentence.

### Code Blocks
Use triple backticks with optional language specification:

````markdown
```python
def hello_world():
    print("Hello, World!")
```
````

**Supported languages:** `python`, `javascript`, `java`, `c`, `cpp`, `css`, `html`, `json`, `xml`, `bash`, `sql`, and many more.

### Indented Code Block
Indent with 4 spaces or a tab:

```markdown
    code block
    second line
```

---

## Blockquotes

Use the greater-than symbol (`>`):

```markdown
> This is a blockquote.
> 
> It can span multiple lines.
> 
> > Nested blockquote
```

Result:
> This is a blockquote.
> 
> It can span multiple lines.
> 
> > Nested blockquote

---

## Horizontal Rules

Create a horizontal line using three or more hyphens, asterisks, or underscores:

```markdown
---
***
___
```

Result:

---

## Tables

Use pipes and hyphens to create tables:

```markdown
| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Row 1, Col 1 | Row 1, Col 2 | Row 1, Col 3 |
| Row 2, Col 1 | Row 2, Col 2 | Row 2, Col 3 |
```

Result:

| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Row 1, Col 1 | Row 1, Col 2 | Row 1, Col 3 |
| Row 2, Col 1 | Row 2, Col 2 | Row 2, Col 3 |

### Table Alignment

```markdown
| Left | Center | Right |
|:-----|:------:|------:|
| L1 | C1 | R1 |
| L2 | C2 | R2 |
```

---

## Escape Characters

Use a backslash (`\`) to escape special Markdown characters:

```markdown
\*not italic\*
\[not a link\]
\# not a heading
```

---

## HTML

Markdown supports inline HTML:

```markdown
<div style="color: red;">This is red text</div>

<details>
  <summary>Click to expand</summary>
  Hidden content here
</details>
```

---

## Best Practices

1. **Use headings hierarchically** - Don't skip levels
2. **Add blank lines** between sections for readability
3. **Use consistent formatting** - Pick a style and stick with it
4. **Keep lines under 80 characters** when possible
5. **Use descriptive link text** - Avoid "click here"
6. **Add alt text to images** - Improves accessibility
7. **Use code blocks** for technical content
8. **Use emphasis sparingly** - Too much formatting reduces readability
9. **Preview your Markdown** - Always check the rendered output
10. **Use comments** - Some Markdown parsers support `<!-- comment -->`

---

## Additional Resources

- [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)
- [CommonMark Specification](https://spec.commonmark.org/)
- [GitHub Flavored Markdown](https://github.github.com/gfm/)

