# markdown-demo

A repository to test some markdown


## Headers

# H1
## H2
### H3
#### H4
##### H5
###### H6


## Horizontal Rules
___
---
***


## Emphasis

Italic characters between *asterisks* or _underscores_ 
Strong characters between double **asterisks** or double __underscores__
Scratch characters between ~~tildes~~


## Links

[regular link](https://github.com/hernanimedeiros)
[regular link](https://github.com/hernanimedeiros "this is title!")


## Lists

### Unordered

+ To create a line star a line with +, - or *
+ To sublist ident 2 spaces:
  + Item 1
  - Item 2
  * Item 3

### Ordered

1. Use sequential number
2. Like this
3. And this
1. Or you can
1. Use everytime 1.
1. Easy!


## Blockquotes

> To blockquote just use greather-than sign
>> To nested just add another sign
>>> Again
> > > > It's aloud to have spaces bettwen signs


## Code

A piece of `inline code`

Intended code (4 spaces)
    // comments
    line 1
    line 2

Block code delimeted:
```
I am a proud block code!
```

Block code with syntax highlights
``` js
function myFunction(p1, p2) {
    var result = p1 * p2
    return result   // Dummy comment!
    console.log(result)
}
```


## SHA references

16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac


## Issue references within a repository

#1
mojombo#1
mojombo/github-flavored-markdown#1


## Username @mentions

@hernanimedeiros


## Tables

| Items  | Description |
| -------| ----------- |
| item 1 | This descri |
| item 2 | This description is out of boundaries? |
| item 3 larger! | This description is out of boundaries? |

Right aligned columns

| Items  | Description |
| ------:| -----------:|
| item 1 | Description |


## Task list

- [x] Done
- [x] This one already done
- [x] This one I just finished now!
- [ ] I will do it tomorow


## Images

Regular image
![Vue logo]
(https://vuejs.org/images/logo.png "The Vue logo")

Image with footenote
![Alt text][image_id]

[image_id]
(https://nuxtjs.org/logos/nuxt-emoji.png "The Nuxt logo")


## Typographic replacements

(c) (C) (r) (R) (tm) (TM) (p) (P) +-
test.. test... test..... test?..... test!....
!!!!!! ???? ,,  -- ---
"Smartypants, double quotes" and 'single quotes'


## Plugins

Welcome to the [syntax plugins](https://www.npmjs.org/browse/keyword/markdown-it-plugin)

### Emojies

* Shortcuts: :-) :-( 8-) ;)
* Classic: :wink: :crush: :cry: :tear: :laughing: :yum:

### Subscript/Superscript

* Subscript: 29<sup>th</sup>
* Subscript: 19^th^
* Superscript: H~2~O
* Superscript: H<sub>2</sub>O

### Inserted text/Marked text

* ++I am a inserted text++
* ==I am a inserted text==

### Footnotes

* Check my footnote [^first]
* Check my another footnote [^second]
* This is inline footnote^[Text of footnote]

[^first]: Footnote with __can have some style__.
[^second]: OR not

### Definition list

* Regular style
List A
:   Definition A
List B
:   Definition **B**

* Compact style
List A
  ~ Item 1
  ~ Item 2

List B
  ~ Item 1
  ~ Item 2
  ~ Item 3
  ~ Item 4

### Abbreviations

This is HTML abbreviation example.

It converts "HTML", but keep intact partial entries like "xxxHTMLyyy" and so on.

*[HTML]: Hyper Text Markup Language

### Custom containers

::: success
*Don't release me*
:::


## References

[Mastering Markdown](https://guides.github.com/features/mastering-markdown/)

[Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax)

[Mardown-it demo](https://markdown-it.github.io/)
