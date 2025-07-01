# Markdown Quick Reference

## Table of content
1. [Text Formatting](#text-formatting)
2. [Inline Code](#inline-code)
3. [Code Block](#code-block)
4. [Blockquote](#blockquote)
5. [Headers](#headers)
6. [Horizontal Seperator](#horizontal-seperator)
7. [List](#list)
8. [Emoji](#emoji)
9. [Markdown for GitHub](#markdown-for-github)
10. [References](#references)

## Text Formatting 

### Italic 
Put the text between a pair of asterisk ( `* * `)

Rendred as 
*italicized text*

### Bold
Put the text between a pair of asterisks ( `** ** `)

Rendred as 
**bold text**

### Strikethrough 
Put the text between a pair of tilde's ( `~~  ~~` )

Rendred as 
~~text~~

## Inline Code 
Put the code between a pair of back quote (\` ` ` \`)

Rendred as 
`print("Hello, World!")`


## Code Block
Put the code block between a pair of triple back quote (\```  \```)

Rendered as 
```python
def hello():
    print("Hello, VPS!")
```

## Blockquote
To create blockquotes, put the text after a greater than symbol `>`

A **Blockquote** is a way to visually emphasize a section of text by indenting it and typically styling it differently (for example, with a left border or italic font). It’s very common for quoting text from another source or for visually highlighting tips, notes, or warnings.

`> This is a blockquote.`

Rendered as 
> This is a blockquote.

A **Nested Blockquote** can be created by multiple greater than symbol `> >` 

In the example given below, while outer blockquote has only one > symbol, the Nested blockquote has two > symbols 

```md
> Outer blockquote
> 
> > Nested blockquote

```

Rendered as 
> Outer blockquote
> 
> > Nested blockquote

## Headers 

Use as many hash (`#`) followed by text to create header of level 1, 2 and so on..

`# H1`

Rendered as 
# H1

`## H2`

Rendered as 
## H2

`### H3`

Rendered as 
### H3

 and so on..


## Horizontal Seperator

Three dashes(`---`)

Rendered as as document wide horizontal line as shown below

---

## List 

### Basic List
An ordered list is created by prefixing lines with numbers followed by a period (`1.`)

```md
1. First item
2. Second item
3. Third item

```

Rendered as 
1. First item
2. Second item
3. Third item

### Nested Ordered Lists
To nest an ordered list inside another, indent by at least 4 spaces or a tab

```md
1. First
    1. Sub-item A
    2. Sub-item B
2. Second
```

Rendered as 
1. First
    1. Sub-item A
    2. Sub-item B
2. Second


### Mix Ordered & Unordered List
We an mix ordered and unordered lists — useful for breakdowns

```md
1. Fruits
    - Apple
    - Banana
2. Vegetables
    - Carrot
    - Broccoli
```

Rendered as 
1. Fruits
    - Apple
    - Banana
2. Vegetables
    - Carrot
    - Broccoli


### Task Lists (Checkboxes)

```md
1. [x] task completed
2. [x] another task completyed
3. [ ] task in progress
4. [ ] another task in progress
```

Rendered as 
1. [x] task completed
2. [x] another task completyed
3. [ ] task in progress
4. [ ] another task in progress


## Emoji

## Tables

### Basic table

```md
| Column 1 | Column 2 | Column 3 |
| -------- | -------- | -------- |
| Row 1, Cell 1 | Row 1, Cell 2 | Row 1, Cell 3 |
| Row 2, Cell 1 | Row 2, Cell 2 | Row 2, Cell 3 |


```

Rendered as 

| Column 1 | Column 2 | Column 3 |
| -------- | -------- | -------- |
| Row 1, Cell 1 | Row 1, Cell 2 | Row 1, Cell 3 |
| Row 2, Cell 1 | Row 2, Cell 2 | Row 2, Cell 3 |


### Table with content alignment

We can control column text alignment with colons : in the separator line as shown below

```md
| Left Aligned | Center Aligned| Right Aligned|
| :--- | :----: | ----: |
| 1 | 2 | 3 |
| A | B | C |

```

Rendered as 

| Left Aligned | Center Aligned| Right Aligned|
| :--- | :----: | ----: |
| 1 | 2 | 3 |
| A | B | C |


Summary

`:---`  → left-aligned

`:---:` → centered

`---:`  → right-aligned


## Links and Images

```
[zestifai](https://zestifai.com)

![Build](https://img.shields.io/github/actions/workflow/status/user/repo/ci.yml)

```


[zestifai](https://zestifai.com)

![Build](https://img.shields.io/github/actions/workflow/status/user/repo/ci.yml)





## Markdown for GitHub

GitHub uses an extended version of standard Markdown called GitHub Flavored Markdown (GFM). It supports:

- Basic Markdown syntax (headings, lists, links, images, code blocks)
- Tables
- Task lists (checkboxes)
- Syntax-highlighted code blocks
- Emoji shortcodes `:smile:`
- Mentions (`@user`), issue/PR links (`#123`)


### Mentions

An @ symbol followed by the username/team will mention and notify that user/team.

```md
Hi @vikrampsingh, please review #123 :rocket:

```

Rendered as 

Hi @vikrampsingh, please review #123 :rocket:

Here, 

`@username` → mentions  @vikrampsingh

`#123` → links to issue or PR

`:emoji:` → :rocket:





