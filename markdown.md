# Markdown Learning Document
This material is referenced from the site [Lear markdown in Y Minutes](https://learnxinyminutes.com/docs/markdown/).

## HTML Elements
Markdown is a superset of HTML, so any HTML file is valid markdown.
For example, you can use `<!-- comments are written here -->` to denote comments, then you won't see comments on the page, such as follows:
<!-- We can use HTML elements in Markdown. So you won't see this line on the production page.-->

## HTML Headings
To create headings in different order, you assign different number of `#` symbol infront of the texts.

# These are `<h1>` level texts with one # inserted before the texts
## These are `<h2>` level texts with two # inserted before the texts
### `<h3>` level texts with three # inserted before the texts
#### `<h4>` level texts with four # inserted before the texts
##### `<h5>` level texts with five # inserted before the texts
###### `<h6>` level texts with six # inserted before the texts


**Two alternative ways of indicating h1 and h2:**

`<h1>` level texts with at least one `=` symbol below the texts
=

`<h2>` level texts with at least one `-` symbol below the texts
-

## Simple text styles
`*Texts in italic style*` : *Here is the example*

`**Texts in bold style**` : **Here is the example**

`***Texts in both italic and bold style***` : ***Here is the example***


## Paragraphs
Paragraphs are a one or multiple adjacent lines of text separated by one or multiple blank lines

Here is paragraph 1.

Here is paragraph 2.


Here is paragraph 3.


Block quotes are easy and done with the `>` inserted before the quotes.
> This is a block quote.


## Lists
**Unordered lists:**

`* item1` 

`* item2` 

`* item3`

or

`+ item1` 

`+ item2` 

`+ item3` 

or

`- item1` 

`- item2` 

`- item3` 

**Ordered lists:**

`1. item 1`

`2. item 2`

`3. item 3`

**Nested-lists:**

`1. item 1`

`2. item 2`

`3. item 3`

    `* sub-item 1`

    `* sub-item 2`
  
`4. item 4`

1. item 1
2. item 2
3. item 3
  * sub-item 1
  * sub-item 2
4. item 4


**Task lists:**

`- [ ] task 1`

`- [ ] task 2`

`- [x] task 3 finished`
  
- [ ] task 1
- [ ] task 2
- [x] task 3 finished





