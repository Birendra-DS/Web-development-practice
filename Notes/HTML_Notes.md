# HTML foundation 
- HTML is the structure of a webpage
- CSS adds style 
- Javascript adds logic
## HTML, head, body
- <html>
Root of the full page

-<head>
Invisible setup area:
title
metadata
SEO
links to CSS

- <body>
Visible page content

## Headings and paragraphs
- Tags: h1 to h6 and p
- Rule: Use heading for structure not just for big text

## Text tags
- <b> → bold
- <i> → italic
- <u> → underline
- <br> → line break
- <hr> → horizontal line
- <small> → smaller text
- <sub> → subscript
- <sup> → superscript
- <pre> → preserve formatting

## Link(<a>) and images(<img>)
### Anchor tag
- <a href="link"> name to show </a>
- Attributes
    - href → destination
    - target="_blank" → open in new tab
- <a href="link" target="_blank">Open Github</a>

### Image tag
- <img src="image link" alt="Image name">
- Attributes
    - src → image path
    - alt → text if image fails / accessibility
    - width / height
- <img src="assets/images/profile.jpg" alt="Profile photo" width="200">
- It is good practice to put anything one width or height with image tags because it makes your website look professional during loading.
- If we give only width then height will autoadjust and viceversa

# Tables, list, forms
## Tables
- Use tables only for real tabular data, not page layout
- Important tags
    - table: whole table -> <table>
    - tr: rows -> <tr>
    - th: header cell -> <th>
    - td: data cell -> <td>
    - border: give border to table
        - <table border="1">
    - captions: to show what is that table about
    - Colspan: Take given input column space
        - colspan:2 means it takes 2 column space (as merge in excel)
    - rowspan: take given ipput row space
### Header, body and footer in table
- these are use to group data in tables just to apply CSS easily
- There is no effect on table structure due to these tags
- Header syntax: <thead>
- body sytax: <tbody>
- footer syntax: <tfoot>

## List
### Defination list
- dl: A name-value group consists of one or more names (dt elements) followed by one or more values (dd elements), ignoring any nodes other than dt and dd elements.
- dt: The dt element represents the term, or name, part of a term-description group in a description list (dl element).
- dd: The dd element represents the description, definition, or value, part of a term-description group in a description list (dl element).

### Unordered list(ul)
- It means bullet points
- <ul> = Unordered List
- <li> = List Item
- type="square" = bullet style

### Ordered list
- It means step by step list
- Here type is important thing
- type = "I" : uppercase Roman number
- type = "i" : Lowecase Roman number
- tpye = "1" : default(arabic number)
- type = "a" : lowercase small aphabets
- type = "A" : uppercase alphabets


# Semantics tags
- Semantic = tags that describe meaning of content.
- Semantic layout helps readability and SEO
- Instead of using only
    - <div>
    - <div>
    - <div>
- Use:
    - <header>
    - <nav>
    - <main>
    - <section>
    - <article>
    - <aside>
    - <footer>
## Header tag: <header>
- Top section of page
- Usually contains:
    - logo
    - site title
    - intro
    - navigation sometimes

## why use semantic tags
- Cleaner structure
- Easy to read
- Better SEO
- Easier CSS styling

## Navigation links: <nav>
- <nav>
-   <a href="www.google.com">click here</a>
</nav>

## Main tag: <main>
- Main important content of page.
- Only one main ideally.

## Section: <section>
- Groups related content.
-
## Article tag: <article>
- Independent content.
- Use article only when content can stand alone.
- Ex:
    - blog post
    - news card
    - product card

## Aside tag: <aside>
- Side content.
- Ex:
    - sidebar
    - ads
    - tips
    - related links
- code:
    - <aside>
        Related Projects
    - </aside>

## Footer tag: <footer>
- Bottom section

## Rule
- Use meaning-based tags before using div.


