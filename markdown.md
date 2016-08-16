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


## Code blocks
You can indicate a code block by indenting a line with **four** spaces or a tab. 
Note that in GitHub Flavored Markdown, you can also use a special syntax for code(add ``` before and after the code),
it will use syntax highlighting of the language you specify after the ``` symbol.(Don't need
to indent the text first.)

```javascript
function() {
    console.log('hello world!');
}
```


## Horizontal rule
It is easily added with three or more *(asterisks) or -(hyphens), with or without spaces.

For example:

`***`

`---`

`- - - `

`************`    

---

## Links
Put the texts to display in hard brackets [] followed by the url in parentheses ()

`[Go to Google.com!](http://www.google.com)`

[Go to Google.com!](http://www.google.com)

Add a link title using quotes inside the parentehses

`[Go to Google.com!](http://www.google.com "Link to Google.com")`

[Go to Google.com!](http://www.google.com "Link to Google.com")

Relative paths also work

`[Go to music](/music/)`

Reference style links

`[Click this link][link1] for more info about it!`

`[link1]: http://www.google.com "Google.com"`

[Click this link][link1] for more info about it!

[link1]: http://www.google.com "Google.com"


## Images
Image are done the same ways as links but with an exclamation mark in front!

`![This is an image](http://www.browngirlmagazine.com/wp-content/uploads/2016/07/love-01.jpg "An image")`

![This is an image](http://www.browngirlmagazine.com/wp-content/uploads/2016/07/love-01.jpg "An image")

Using reference style

`![This is an image][image]`

`[image]: relative/urls/cool/image.jpg "if you need a title, it's here"`


## Miscellany
** Auto-links

<http://www.google.com> is equivalent to
`[http://www.google.com](http://www.google.com)`

** Auto-links for emails

`<cure100061148@gmail.com>` : <cure100061148@gmail.com>

** Escaping characters

Add \ before the symbols that create some effect that you dislike. For example, 
add \ before * can make texts surrounded by asterisks not to be italic.

** Keyboard keys

In GitHub Flavored Markdown, you can use a `<kbd>` tag to represent keyboard keys,
for example, `<kbd>Alt</kbd>` : <kbd>Alt</kbd>

** Tables

Tables are only available in GitHub Flavored Markdown.

For example,

`Col1 | Col2 | Col3`

`:-- | :-: | --:`

`left aligned | centered | right-aligned`

`1 | 2 | 3`


Col1 | Col2 | Col3
:-- | :-: | --:
left-aligned | centered | right-aligned
1 | 2 | 3

## To deep further
1. [Jonh Gruber's official post of syntax](http://daringfireball.net/projects/markdown/syntax)
2. [Adam Pritchard's great cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
