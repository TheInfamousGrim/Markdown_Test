# Markdown Cheatsheet
---------------------

Vapor's naughty lil cheatsheet for using markdown.

**Table of Contents**

[Headers](#Headers)



## Headers
---------- 

```

# H1
## H2
### H3
#### H4
##### H5
###### H6

Alt-H1
======

Alt-H2
------

```
# H1
## H2
### H3
#### H4
##### H5
###### H6

Alt-H1
======

Alt-H2
------

## Emphasis 
-----------

```
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

strikethrough uses two tildes ~~Scratch this.~~

```

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

strikethrough uses two tildes ~~Scratch this.~~


## Lists
--------

(In this example, leading and trailing spaces are shown with dots : &middot;) )

```

1. First ordered list item
2. Another item
..* Unordered sub-list.
1. Actual numbers don't matter, just that it's a number
··1. Ordered sub-list
4. And another item.



    First ordered list item···You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown.)

···To have a line break without a paragraph, you will need to use two trailin spaces.··
···Note that this line is seperate, but within the same paragraph.··
···(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered lists can use asterisks
- Or minuses
+ Or Pluses

```

1. First ordered list item
2. Another item
..* Unordered sub-list.*
1. Actual numbers don't matter, just that it's a number
··1. Ordered sub-list
4. And another item.



    First ordered list item···You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown.)

···To have a line break without a paragraph, you will need to use two trailin spaces.··
···Note that this line is seperate, but within the same paragraph.··
···(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered lists can use asterisks
- Or minuses
+ Or Pluses

## Links

There are two ways to create links

```
[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](README.md)

[You can use numbers for reference-style link definitions][1]

Or leave it emepty and use the [link text itself]

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later. 

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

```
[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](README.md)

[You can use numbers for reference-style link definitions][1]

Or leave it emepty and use the [link text itself]

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later. 

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

## Images

```

Here's our logo (hover to see the title text):

Inline-style:
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1"

Reference-style:
![alt text][logo]

[logo\: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

```

Here's our logo (hover to see the title text):

Inline-style:
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style:
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"


## Code and Syntax Highlighting

Code blocks are part of the Markdown spec, but syntax highlighting isn't. However, many renderers -- like Github's 
