# Markdown Cheatsheet
---------------------

Vapor's naughty lil cheatsheet for using markdown.

**Table of Contents**

[Headers](#Headers)/
[Emphasis](#Emphasis)

[Lists](#Lists)

[Images](#Images)

[Code and Syntax Highlighting](#Code-and-Syntax-Highlighting)

[Tables](#Tables)

[Blockquotes](#Blockquotes)

[Inline HTML](#Inline-HTML)

[Horizontal Rule](#Horizontal-Rule)

[Line Breaks](#Line-Breaks)

[YouTube Videos](#YouTube-Videos)


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
--------

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
---------

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
--------------------------------

Code blocks are part of the Markdown spec, but syntax highlighting isn't.
 
However, many renderers -- like Github's and *Markdown Here* -- support syntax highlighting.

Which Languages are supported and how those language names should be written will vary from renderer to renderer. *Markdown Here* supports highlighting for dozens of languages (and not-really-languages, like diffs and HTTP headers).

```

`Inline `code` has `back-ticks around` it. 

```

Inline `code` has `back-ticks around` it. 

Blocks of code are either fenced by lines with three back-ticks, or are indented with four spaces. I recommend only using the fenced code blocks -- They're easier and only they support syntax highlighting. 

```

```javascript
var s="JavaScript syntax highlighting";
alert(s)
\``` (ignore the backslash, just using to escape)

```

```
```python
s= "Python syntax highlighting"
print s
\```
```

```
\```
No language indicated, so no syntax highlighting 

But let's throw in a <b>tag</b>
\```
```

```javascript
var s="JavaScript syntax highlighting";
alert(s)
```

```python
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting in mardown here (varies on Github).
But let's throw in a <b>tag</b>
```

## Tables

Tables aren't part of the core Markdown spec, but they are part of GFM and *Markdown Here* supports them. They are an easy way of adding tables to your email --a task that would otherwise require copy-pasting from another application. 

```

Colons can be used to align columns.

| Tables        | Are           | Cool   |
| ------------- |:-------------:| ------:|
| col 3 is      | right-aligned |  $1600 | 
| col 2 is      | centered      |    $12 | 
| zebra stripes | are neat      |     $1 |

There must be at least 3 dashes seperating each header cell. 
The outer pips (|) are optional, and you don't need to make the
raw Markdown line up prettily. You can also use inline Markdown.  

Markdown | Less | Pretty
 --- | --- | ---
*still* | `renders` | **nicely**
1 | 2 | 3

```
Colons can be used to align columns.

| Tables        | Are           | Cool   |
| ------------- |:-------------:| ------:|
| col 3 is      | right-aligned |  $1600 | 
| col 2 is      | centered      |    $12 | 
| zebra stripes | are neat      |     $1 |

There must be at least 3 dashes seperating each header cell. 
The outer pips (|) are optional, and you don't need to make the
raw Markdown line up prettily. You can also use inline Markdown.  

Markdown | Less | Pretty
 --- | --- | ---
*still* | `renders` | **nicely**
1 | 2 | 3

## Blockquotes

```
> Blockquotes are very handy in email to emulate reply text. 
> This line is part of the same quote. 

Quote Break 

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **markdown** into a blockquote. 

```
> Blockquotes are very handy in email to emulate reply text. 
> This line is part of the same quote. 

Quote Break 

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **markdown** into a blockquote. 

## Inline HTML 

You can also use raw HTML in your Markdown, and it'll mostly work pretty well. 

```

<dl>
    <dt>Definition list</dd>
    <dd>Is something people use sometimes.</dd>

    <dt>Markdown in HTML</dt>
    <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

```

<dl>
    <dt>Definition list</dd>
    <dd>Is something people use sometimes.</dd>

    <dt>Markdown in HTML</dt>
    <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

## Horizontal Rule

```

Three or more...

---

Hyphens

***

Asterisks 

___

Undersocres

```

Three or more...

---

Hyphens 

__________

Undersocres

## Line Breaks

My basic recommendation for learning how line breaks work is to experiment and discover
 --hit<Enter> once (i.e., insert one newline), then hit it twice (i.e., insert two newlines),
see what happens. You'll soon learn to get what you want. "Markdown Toggle" is your friend. 

Here are some things to try out:

```

Here's a line for us to start with. 

This line is seperated from the one above by two newlines, so it will be a *seperate paragraph*

This line is also a seperate paragraph, but...
This line is only seperated by a single newline, so it's a seperate line in the *same paragraph*

```

Here's a line for us to start with. 

This line is seperated from the one above by two newlines, so it will be a *seperate paragraph*

This line is also a seperate paragraph, but...
This line is only seperated by a single newline, so it's a seperate line in the *same paragraph*

(Technical note: *Markdown Here* uses GFM line breaks, so there's no need to use 
MD's two-space line breaks.)


## YouTube Videos

They can't be added directly but you can add an image with a link to the video like this:

```
<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

Or, in pure Markdown, but losing the image sizing and border:

```
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)

```


