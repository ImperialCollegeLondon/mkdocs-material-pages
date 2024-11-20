# Basic Markdown

Material for MkDocs supports all standard Markdown syntax out of the box. Let's explore the most commonly used features that don't require any extensions.

## Text Formatting

Basic text formatting in Markdown is straightforward:

Normal text doesn't need any special markers.

**Bold text** uses double asterisks.
__This is also bold__ using underscores.

*Italics* use single asterisks.
_This is also italic_ using single underscore.

***Bold and italic*** uses three asterisks.

~~Strikethrough~~ uses double tildes.


## Headers

Headers use hash symbols (#). The number of hashes determines the level. 
Above is a level 2 header, and below are the rest!

### Level 3 Header
#### Level 4 Header
##### Level 5 Header
###### Level 6 Header

## Lists

### Unordered Lists


* First item
* Second item
    - Nested item
    - Another nested item
* Third item


### Ordered Lists


1. First item
2. Second item
    1. Nested item
    2. Another nested item
3. Third item


## Links and Images

### Links

[Visit Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)
[Internal link to another page](another-page.md)
[Link to a section](#links-and-images)

### Images


![Alt text for image](./assets/favicon.png)
![Remote image](https://upload.wikimedia.org/wikipedia/commons/0/06/Imperial_College_London_new_logo.png)


## Code

### Inline Code

Use backticks for `inline code` like this:




### Code Blocks

Triple backticks create code blocks and you can even specify a language
for syntax highlighting!


```python
def hello_world():
    print("Hello, MkDocs!")
```


## Blockquotes


> This is a blockquote
> It can span multiple lines
>
> Use blank lines for multiple paragraphs


## Tables


| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Cell 1   | Cell 2   | Cell 3   |
| Cell 4   | Cell 5   | Cell 6   |


### Aligning tables

| Left | Center | Right |
|:-----|:------:|------:|
| 1    |   2    |     3 |


## Horizontal Rules

Three or more hyphens, asterisks, or underscores:


---
***
___

s
## Exercise: Create Project Documentation

Create a new file called `project.md` and build documentation for an imaginary software project. Your documentation should include:

1. A main title for your project
2. A brief description using both **bold** and *italic* text
3. At least three features listed using bullet points
4. Installation steps using numbered lists with at least one nested level
5. A code block showing a simple example (in any programming language)
6. A table with three columns:
    - Version
    - Release Date
    - Key Features
7. A blockquote with an important note about usage
8. At least two links:
    - One to an imaginary API documentation page
    - One to an external website like `example.com`
9. A horizontal rule separating your content

### Example Structure

```markdown
# Project Name

Brief description of what your **amazing** project does...

## Features

* Feature 1
* Feature 2
* Feature 3

## Installation

1. Step one
   1. Sub-step
   2. Sub-step
2. Step two
3. Step three

[Rest of the requirements...]
```

Take 10 minutes to create this sample page. Focus on practicing the Markdown syntax rather than writing perfect content. 