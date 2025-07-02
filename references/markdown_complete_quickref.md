# 📘 Markdown Complete Quick Reference

A comprehensive Markdown cheat sheet for **developers**, **technical writers**, **researchers**, and **bloggers**. It covers essential Markdown syntax, GitHub-flavored Markdown (GFM), tips, quirks, and advanced features.

---

## 📑 Table of Contents

1. [Introduction](#introduction)
2. [Headings](#headings)
3. [Paragraphs and Line Breaks](#paragraphs-and-line-breaks)
4. [Text Formatting](#text-formatting)
5. [Blockquotes](#blockquotes)
6. [Lists](#lists)
7. [Task Lists (Checkboxes)](#task-lists-checkboxes)
8. [Code: Inline and Blocks](#code-inline-and-blocks)
9. [Links](#links)
10. [Images](#images)
11. [Tables](#tables)
12. [Horizontal Rules](#horizontal-rules)
13. [Escaping Characters](#escaping-characters)
14. [Emojis](#emojis)
15. [Footnotes](#footnotes)
16. [HTML in Markdown](#html-in-markdown)
17. [GitHub Flavored Markdown (GFM)](#github-flavored-markdown-gfm)
18. [Tips and Quirks](#tips-and-quirks)
19. [Further Resources](#further-resources)

---

## 📘 Introduction

Markdown is a lightweight markup language used to format plain text. It's widely used in **README files**, **technical documentation**, **notes**, **blogs**, and **scientific publishing workflows**.

---

## 🧱 Headings

Use `#` followed by a space to create headings.

```md
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

**Renders as:**

# H1

## H2

### H3

#### H4

##### H5

###### H6

> 💡 Don't skip heading levels for semantic clarity.

---

## ✍️ Paragraphs and Line Breaks

Separate paragraphs with a **blank line**. To create a **line break**, end a line with **two or more spaces**.

```md
First paragraph.

Second paragraph with line break.  
New line here.
```

---

## 🖋️ Text Formatting

```md
*italic* or _italic_ → *italic*
**bold** or __bold__ → **bold**
***bold italic*** → ***bold italic***
~~strikethrough~~ → ~~strikethrough~~
```

---

## 💬 Blockquotes

```md
> This is a blockquote.
>> Nested blockquote.
```

> This is a blockquote.
>
> > Nested blockquote.

> 💡 Blockquotes can contain other markdown like lists and code.

---

## 🧾 Lists

### Unordered List

```md
- Item A
* Item B
+ Item C
```

All render identically:

- Item A
- Item B
- Item C

### Ordered List

```md
1. First
2. Second
```

1. First
2. Second

### Nested Lists

```md
1. Item
   - Subitem
     - Sub-subitem
```

1. Item
   - Subitem
     - Sub-subitem

---

## ☑️ Task Lists (Checkboxes)

Only supported in **GFM**.

```md
- [x] Done
- [ ] To do
```

-

---

## 💻 Code: Inline and Blocks

### Inline Code

Use backticks:

```md
Use `git status` to check changes.
```

### Code Block

Use triple backticks:

````md
```python
def hello():
    print("Hello, world")
````

````
Renders as:
```python
def hello():
    print("Hello, world")
````

> 💡 Indentation-based code blocks (4 spaces) are discouraged today.

---

## 🔗 Links

```md
[Text](https://example.com)
[Text with title](https://example.com "Title")
```

---

## 🖼️ Images

```md
![Alt text](https://example.com/image.png)
```

> 💡 For GitHub, you can drag images into issues/PRs and get the link.

---

## 📊 Tables

GFM supports tables:

```md
| Name | Age |
|------|-----|
| John | 25  |
| Jane | 30  |
```

| Name | Age |
| ---- | --- |
| John | 25  |
| Jane | 30  |

### Align Columns

```md
| Left | Center | Right |
|:-----|:------:|------:|
| A    | B      | C     |
```

| Left | Center | Right |
| ---- | ------ | ----- |
| A    | B      | C     |

---

## ➖ Horizontal Rules

Use `---`, `***`, or `___` on a line by itself.

```md
---
```

---

## 🔤 Escaping Characters

Use `\` to escape characters:

```md
\*not italic\*
```

Renders as: *not italic*

---

## 😀 Emojis

GitHub supports emoji shortcodes:

```md
:rocket: → 🚀
:smile: → 😄
```

Full list: [https://github.com/ikatyang/emoji-cheat-sheet](https://github.com/ikatyang/emoji-cheat-sheet)

---

## 🔖 Footnotes

Some Markdown engines (e.g. Markdown-it, Obsidian) support footnotes:

```md
Here is a fact.[^1]

[^1]: This is the footnote.
```

---

## 🧩 HTML in Markdown

Raw HTML is allowed in most renderers:

```html
<b>Bold using HTML</b>
<details><summary>Click to expand</summary>Hidden content</details>
```

> ⚠️ Not all Markdown engines support all HTML tags.

---

## 🐙 GitHub Flavored Markdown (GFM)

GFM includes:

- Task lists `[ ]`
- Tables
- Emoji shortcodes
- Syntax-highlighted code blocks
- Mentions: `@username`
- References: `#123` (issues/PRs)

---

## ⚙️ Tips and Quirks

| Tip                          | Description                                 |
| ---------------------------- | ------------------------------------------- |
| Use `<br>`                   | For guaranteed line breaks across renderers |
| Indent nested lists properly | Use 4 spaces or 1 tab                       |
| Always preview your Markdown | Especially for GFM or blog usage            |
| Escape pipes in tables       | Use `\|`                                    |
| Don’t mix list markers       | Stick to `-`, `*`, or `+` consistently      |

---

## 📚 Further Resources

- [Markdown Guide](https://www.markdownguide.org/)
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
- [Obsidian Markdown Reference](https://help.obsidian.md/Editing+and+formatting/Basic+formatting+syntax)
- [CommonMark Spec](https://spec.commonmark.org/)
- [Emojipedia](https://emojipedia.org/)

---

> ✍️ **Author:** Vikram Singh\
> 🔗 [vikramsingh.ai](https://vikramsingh.ai) | [GitHub](https://github.com/vikrampsingh)

