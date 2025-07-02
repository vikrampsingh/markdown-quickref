# Markdown Tutorial: A Comprehensive Guide

This tutorial provides a comprehensive overview of commonly used Markdown syntax, demonstrating how each element renders. It is designed for developers, content writers, bloggers, and researchers.

## Table of Contents

* [Headers](#headers)
* [Paragraphs and Line Breaks](#paragraphs-and-line-breaks)
* [Emphasis](#emphasis)
* [Lists](#lists)
  * [Unordered Lists](#unordered-lists)
  * [Ordered Lists](#ordered-lists)
* [Links](#links)
* [Images](#images)
* [Code Blocks](#code-blocks)
* [Blockquotes](#blockquotes)
* [Horizontal Rules](#horizontal-rules)
* [Tables](#tables)
* [Strikethrough](#strikethrough)
* [Task Lists](#task-lists)
* [Escaping Characters](#escaping-characters)
* [HTML in Markdown](#html-in-markdown)


## Headers

Headers are used to create titles and subtitles. Markdown supports six levels of headers, from `<h1>` to `<h6>`.

### Syntax

```markdown
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6
```

### Renders As

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6




## Paragraphs and Line Breaks

A paragraph is simply one or more consecutive lines of text, separated by one or more blank lines. To create a line break within a paragraph, you can use two or more spaces at the end of the line, or a backslash.

### Syntax

```markdown
This is a paragraph.
It continues on the next line.

This is another paragraph.
This line has a soft break.  
This line is also part of the same paragraph.

This line has a soft break.\
This line is also part of the same paragraph.
```

### Renders As

This is a paragraph.
It continues on the next line.

This is another paragraph.
This line has a soft break.  
This line is also part of the same paragraph.

This line has a soft break.\
This line is also part of the same paragraph.




## Emphasis

Emphasis is used to italicize or bold text. You can use asterisks (`*`) or underscores (`_`) for emphasis.

### Syntax

```markdown
*This text will be italic*
_This text will also be italic_

**This text will be bold**
__This text will also be bold__

***This text will be bold and italic***
___This text will also be bold and italic___
```

### Renders As

*This text will be italic*
_This text will also be italic_

**This text will be bold**
__This text will also be bold__

***This text will be bold and italic***
___This text will also be bold and italic___




## Lists

Markdown supports both unordered (bulleted) and ordered (numbered) lists.

### Unordered Lists

Unordered lists use asterisks (`*`), plus signs (`+`), or hyphens (`-`) as list markers.

#### Syntax

```markdown
* Item 1
* Item 2
  * Sub-item 2.1
  * Sub-item 2.2
* Item 3

+ Item A
+ Item B

- Item X
- Item Y
```

#### Renders As

* Item 1
* Item 2
  * Sub-item 2.1
  * Sub-item 2.2
* Item 3

+ Item A
+ Item B

- Item X
- Item Y

### Ordered Lists

Ordered lists use numbers followed by a period (`.`).

#### Syntax

```markdown
1. First item
2. Second item
3. Third item
   1. Sub-item 3.1
   2. Sub-item 3.2
```

#### Renders As

1. First item
2. Second item
3. Third item
   1. Sub-item 3.1
   2. Sub-item 3.2




## Links

Links are used to connect to other web pages or resources. Markdown supports inline links and reference-style links.

### Syntax

```markdown
[Google](https://www.google.com)

[Visit Google][1]

[1]: https://www.google.com "Google's Homepage"
```

### Renders As

[Google](https://www.google.com)

[Visit Google][1]

[1]: https://www.google.com "Google's Homepage"




## Images

Images are embedded in Markdown using a syntax similar to links, but prefixed with an exclamation mark (`!`).

### Syntax

```markdown
![Alt text for image](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png "Google Logo")

![Alt text for image][logo]

[logo]: https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png "Google Logo"
```

### Renders As

![Alt text for image](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png "Google Logo")

![Alt text for image][logo]

[logo]: https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png "Google Logo"




## Code Blocks

Code blocks are used to display code snippets. You can use backticks (`) for inline code or triple backticks (```) for multi-line code blocks.

### Syntax

```markdown
This is `inline code`.

```python
def hello_world():
    print("Hello, world!")
```
```

### Renders As

This is `inline code`.

```python
def hello_world():
    print("Hello, world!")
```




## Blockquotes

Blockquotes are used to quote text from another source. They are created by preceding each line with a `>` character.

### Syntax

```markdown
> This is a blockquote.
> It can span multiple lines.
> > Nested blockquote.
> This is still part of the first blockquote.
```

### Renders As

> This is a blockquote.
> It can span multiple lines.
> > Nested blockquote.
> This is still part of the first blockquote.




## Horizontal Rules

Horizontal rules are used to separate content. You can create a horizontal rule by using three or more hyphens (`-`), asterisks (`*`), or underscores (`_`) on a line by themselves.

### Syntax

```markdown
---

***

___
```

### Renders As

---

***

___




## Tables

Tables allow you to organize data in rows and columns.

### Syntax

```markdown
| Header 1 | Header 2 |
| -------- | -------- |
| Row 1 Col 1 | Row 1 Col 2 |
| Row 2 Col 1 | Row 2 Col 2 |
```

### Renders As

| Header 1 | Header 2 |
| -------- | -------- |
| Row 1 Col 1 | Row 1 Col 2 |
| Row 2 Col 1 | Row 2 Col 2 |




## Strikethrough

Strikethrough is used to cross out text. It is created by wrapping text in two tildes (`~~`).

### Syntax

```markdown
~~This text will be struck through~~
```

### Renders As

~~This text will be struck through~~




## Task Lists

Task lists are useful for tracking tasks. They are created using hyphens (`-`) followed by `[ ]` for an unchecked task or `[x]` for a checked task.

### Syntax

```markdown
- [x] Task 1 (completed)
- [ ] Task 2 (pending)
- [ ] Task 3 (pending)
```

### Renders As

- [x] Task 1 (completed)
- [ ] Task 2 (pending)
- [ ] Task 3 (pending)




## Escaping Characters

To display a literal character that would otherwise be used to format text in Markdown, you can escape it by preceding it with a backslash (`\`).

### Syntax

```markdown
\* Not italic \*

\`Not code\`
```

### Renders As

\* Not italic \*

\`Not code\`




## HTML in Markdown

Markdown allows you to use raw HTML directly within your Markdown document. This is useful for more complex formatting that Markdown doesn't support natively.

### Syntax

```markdown
<p>This is a <b>paragraph</b> with <i>HTML</i> tags.</p>

<img src="https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png" alt="Google Logo" width="100" height="35">
```

### Renders As

<p>This is a <b>paragraph</b> with <i>HTML</i> tags.</p>

<img src="https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png" alt="Google Logo" width="100" height="35">



