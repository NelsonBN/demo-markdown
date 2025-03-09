# Documentation - Markdown - Tables
[[Home]](/README.md)


## Basic Table Structure
A simple table with headers and aligned content:

| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Cell 1   | Cell 2   | Cell 3   |
| Cell 4   | Cell 5   | Cell 6   |


## Column Alignment
You can align text in columns to the left, right, or center:

| Left-aligned | Center-aligned | Right-aligned |
|:-------------|:--------------:|--------------:|
| Left         | Center         | Right         |
| Text         | Text           | Text          |


## Complex Table Example
Tables can include links, code, and formatting:

| Feature  | Syntax        | Example                               |
|----------|---------------|---------------------------------------|
| **Bold** | `**text**`    | **Bold text**                         |
| *Italic* | `*text*`      | *Italic text*                         |
| Code     | `` `code` ``  | `console.log()`                       |
| Link     | `[text](url)` | [Markdown Guide](https://example.com) |


## Relaxed Syntax Tables
Markdown tables don't need to be perfectly aligned in the source to render correctly:

| Header 1|Header 2|Header 3|
|---|---|----|
|Cell 1|Cell 2|Cell 3|
|Longer cell content|Short|Another cell with more text|

This renders the same as a neatly formatted table. The separator row only needs to have at least 3 dashes per column and pipes between them.

Even more relaxed syntax still works:

|Header 1 | Header 2|Header 3
|--- | -------------- | ---
Cell 1|Cell 2|Cell 3
Another row|with content|here

Markdown processors will interpret this correctly despite the inconsistent spacing and missing end pipe.
