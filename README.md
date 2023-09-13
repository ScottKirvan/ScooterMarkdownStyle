<div align="center">

  <img src="assets/media/logo.jpg" alt="logo" width="200" height="auto" />
    <h1><a href="https://github.com/ScottKirvan/ScooterMarkdownStyle">ScottKirvan/ScooterMarkdownStyle</a></h1>
  <h3>
  A testbed repo for GitHub Pages markdown styling.
  </h3>
  
<!-- Badges -->
<p>
  <a href="https://github.com/ScottKirvan/ScooterMarkdownStyle/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/ScottKirvan/ScooterMarkdownStyle" alt="contributors" />
  </a>
  <a href="">
    <img src="https://img.shields.io/github/last-commit/ScottKirvan/ScooterMarkdownStyle" alt="last update" />
  </a>
  <a href="https://github.com/ScottKirvan/ScooterMarkdownStyle/network/members">
    <img src="https://img.shields.io/github/forks/ScottKirvan/ScooterMarkdownStyle" alt="forks" />
  </a>
  <a href="https://github.com/ScottKirvan/ScooterMarkdownStyle/stargazers">
    <img src="https://img.shields.io/github/stars/ScottKirvan/ScooterMarkdownStyle" alt="stars" />
  </a>
  <a href="https://github.com/ScottKirvan/ScooterMarkdownStyle/issues/">
    <img src="https://img.shields.io/github/issues/ScottKirvan/ScooterMarkdownStyle" alt="open issues" />
  </a>
  <a href="https://github.com/ScottKirvan/ScooterMarkdownStyle/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/ScottKirvan/ScooterMarkdownStyle.svg" alt="license" />
  </a>
  <a href="https://discord.gg/gQH4mXWQRT">
    <!--<img src="https://img.shields.io/discord/704680098577514527?style=flat-square&label=%F0%9F%92%AC%20discord&color=00ACD7">-->
    <img src="https://img.shields.io/discord/1052011377415438346?style=flat-square&label=discord&color=00ACD7">
  </a>
</p>
   
<h4>
    <a href="https://github.com/ScottKirvan/ScooterMarkdownStyle/">View Demo</a>
  <span> · </span>
    <a href="https://github.com/ScottKirvan/ScooterMarkdownStyle">Documentation</a>
  <span> · </span>
    <a href="https://github.com/ScottKirvan/ScooterMarkdownStyle/issues/">Report Bug</a>
  <span> · </span>
    <a href="https://github.com/ScottKirvan/ScooterMarkdownStyle/issues/">Request Feature</a>
  </h4>
</div>

This README file will serve as a test page for github pages/jekyll styling.  If you already have a GitHub.io page set up, any additional repos you have can be served as a subfolder to that website.  Those repos, by default, do not inherit the style/theme rules set out in the GitHub.io site, therefore you have to set up your own css or theme for each repo.  This readme will have  markdown examples for as much syntax as I can find (and specifically that github supports). The markdown in this README is a superset of GitHub Markdown, so some features will not be parsed on GitHub.


---
__Advertisement :)__

- __[pica](https://nodeca.github.io/pica/demo/)__ - high quality and fast image
  resize in browser.
- __[babelfish](https://github.com/nodeca/babelfish/)__ - developer friendly
  i18n with plurals support and easy syntax.

You will like those projects!

---

# h1 Heading 
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading

## Alternate Heading Syntax

h1 Heading
==============
h2 Heading
----------

## Paragraphs

Paragraph text
on three
seperate lines.

Line break forced  
with double spaces.

Using a slash\
for force a line break.

## Horizontal Rules

___

---

***


## Typographic replacements

Enable typographer option to see result.

(c) (C) (r) (R) (tm) (TM) (p) (P) +-

test.. test... test..... test?..... test!....

!!!!!! ???? ,,  -- ---

"Smartypants, double quotes" and 'single quotes'


## Emphasis

**This is bold text**

__This is bold text__

*This is italic text*

_This is italic text_

~~Strikethrough~~


## Blockquotes


> basic blockquote
> following normal paragraph  
> doublespace rules

> **Note** 
> GitHub Note callout

> **Warning** 
> GitHub Warning callout

> Blockquotes can also be nested...
>> ...by using additional greater-than signs right next to each other...
> > > ...or with spaces between arrows.

> You can also do a
>
> Multi-paragraph blockquote


## Lists

Unordered

+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    * Ac tristique libero volutpat at
    + Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
+ Very easy!

Ordered

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa


1. You can use sequential numbers...
1. ...or keep all the numbers as `1.`

Start numbering with offset:

57. foo
1. bar


## Code

Inline `code`

Indented code

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code


Block code "fences"

```
Sample text here...
```

Syntax highlighting

``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

## Tables

| Option | Description                                                               |
| ------ | ------------------------------------------------------------------------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default.    |
| ext    | extension to be used for dest files.                                      |

Right aligned columns

| Option |                                                               Description |
| -----: | ------------------------------------------------------------------------: |
|   data | path to data files to supply the data that will be passed into templates. |
| engine |    engine to be used for processing templates. Handlebars is the default. |
|    ext |                                      extension to be used for dest files. |


## Links

[link text](http://dev.nodeca.com)

[link with title](http://nodeca.github.io/pica/demo/ "title text!")

Autoconverted link https://github.com/nodeca/pica (enable linkify to see)


## Images

![Minion](https://octodex.github.com/images/minion.png)
![Stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat")

Like links, Images also have a footnote style syntax

![Alt text][id]

With a reference later in the document defining the URL location:

[id]: https://octodex.github.com/images/dojocat.jpg  "The Dojocat"


## Plugins

The killer feature of `markdown-it` is very effective support of
[syntax plugins](https://www.npmjs.org/browse/keyword/markdown-it-plugin).


### [Emojies](https://github.com/markdown-it/markdown-it-emoji)

> Classic markup: :wink: :crush: :cry: :tear: :laughing: :yum:
>
> Shortcuts (emoticons): :-) :-( 8-) ;)

see [how to change output](https://github.com/markdown-it/markdown-it-emoji#change-output) with twemoji.


### [Subscript](https://github.com/markdown-it/markdown-it-sub) / [Superscript](https://github.com/markdown-it/markdown-it-sup)

- 19^th^
- H~2~O


### [\<ins>](https://github.com/markdown-it/markdown-it-ins)

++Inserted text++


### [\<mark>](https://github.com/markdown-it/markdown-it-mark)

==Marked text==


### [Footnotes](https://github.com/markdown-it/markdown-it-footnote)

Footnote 1 link[^first].

Footnote 2 link[^second].

Inline footnote^[Text of inline footnote] definition.

Duplicated footnote reference[^second].

[^first]: Footnote **can have markup**

    and multiple paragraphs.

[^second]: Footnote text.


### [Definition lists](https://github.com/markdown-it/markdown-it-deflist)

Term 1

:   Definition 1
with lazy continuation.

Term 2 with *inline markup*

:   Definition 2

        { some code, part of Definition 2 }

    Third paragraph of definition 2.

_Compact style:_

Term 1
  ~ Definition 1

Term 2
  ~ Definition 2a
  ~ Definition 2b


### [Abbreviations](https://github.com/markdown-it/markdown-it-abbr)

This is HTML abbreviation example.

It converts "HTML", but keep intact partial entries like "xxxHTMLyyy" and so on.

*[HTML]: Hyper Text Markup Language

### [Custom containers](https://github.com/markdown-it/markdown-it-container)

::: warning
*here be dragons*
:::


Credits
-------
**Copyright (c) (2023):** [Scott Kirvan](https://github.com/ScottKirvan)  - All rights reserved   
Much of the text in this README was copied from [Markdown it!](https://markdown-it.github.io/), **Copyright (c) 2014** Vitaly Puzrin, Alex Kocharin.  
*ScooterMarkdownStyle is licensed under the [MIT License](LICENSE.md).*  

Project Link:  [ScooterMarkdownStyle](https://github.com/ScottKirvan/ScooterMarkdownStyle)  
[CHANGELOG](notes/CHANGELOG.md)  
[TODO](notes/TODO.md)
