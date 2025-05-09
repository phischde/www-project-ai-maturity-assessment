# Markdown Showcase

This document demonstrates the Markdown features supported by the **PDF Preview Generator**. It is designed to be both a **visual reference** and a **syntax cheat sheet**.

## Headings

Use `#`, `##`, or `###` at the beginning of a line to define headings.

- Only `#` (H1) and `##` (H2) are included in the Table of Contents.
- Headings are automatically numbered in the final PDF. Do **not** manually add numbers.
- Each H1 section starts on a new page.

## Basic Text Styles

You can use the following styles:

```markdown
**bold**  
*italic*  
`monospace`
```

Result: 

**bold**  
*italic*  
`monospace`

### Lists

#### Bullet List
```markdown
- Item 1  
- Item 2  
- Item 3
```

or

```markdown
* Item 1  
* Item 2  
* Item 3
```

Result:

- Item 1
- Item 2
- Item 3

#### Numbered List
```markdown
1. First  
2. Second  
3. Third
```

Result:

1. First
2. Second
3. Third

## Blockquotes

### Standard Blockquote

Use `>` at the beginning of a line:

```markdown
 > This is a blockquote.
```

> This is a blockquote.

### Custom "NOTE" Block

Lines that begin with `> NOTE:` will be rendered as a special yellow-highlighted box. Make sure the `>` is the **first character** on the line:

```markdown
 > NOTE: This is a note.
```

> NOTE: This is a note.

### Custom "COMMENT" Block

Lines that begin with `> COMMENT:` will be rendered as a special blue-highlighted box:

```markdown
 > COMMENT: This is a comment.
```

> COMMENT: This is a comment.

*Important*: Both NOTE and COMMENT are non standard Markdown features and are meant for the draft phase only as a means to add meta information and comments into markdown. 
## Tables

Basic tables are supported using pipes (`|`) and dashes (`-`):

```markdown
| Feature       | Supported | Notes                        |
|---------------|-----------|------------------------------|
| Headings      | Yes       | Auto-numbered                |
| Blockquotes   | Yes       | NOTE and COMMENT supported   |
| Tables        | Yes       | Basic markdown tables        |
```

| Feature       | Supported | Notes                        |
|---------------|-----------|------------------------------|
| Headings      | Yes       | Auto-numbered                |
| Blockquotes   | Yes       | NOTE and COMMENT supported   |
| Tables        | Yes       | Basic markdown tables        |

## Line Breaks & Paragraphs

A new paragraph is created by using an empty line between blocks.

To create a **manual line break**, end a line with two spaces:

```markdown
Line one with break.␣␣  
Line two.
```

Line one with break.  
Line two.

## Links

Standard Markdown links will be shown as plain text in PDF output:

```markdown
[Example Link](https://example.com)
```

[Example Link](https://example.com)


# Integration 

The PDF Preview Tool is designed to run directly on GitHub. You do not need to install anything. 

Go to the `Actions` Tab on GitHub (either the main repository or your fork) and look for a workflow with the name **Build PDF Preview**. Open it and find the PDF at the bottom of the page for download.  



---

_This document was designed for use with the PDF Preview Generator. It helps verify the output structure, styles, and rendering logic._
