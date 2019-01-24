Test repo
---------

**strong**

*simple emphasis*

`source code`

~~strike through~~

_this emphasis_

__this emphasis__

_**`together`**_


Newlines
are
ignored

Force a line break with  
two spaces in the end of the line

or with \
in the end of the line

or with <br/> anywhere

Links
-----

- You can insert links in text like [this](/tutorial.md)

- You may add a [title](https://agea.github.io/tutorial.md "Markdown Tutorial") to your link (can you see the tooltip?)

- If your link contains spaces you have to write the [link](<http://example.com/a space>) between `<>`

- You can use spaces and markup inside the [link **text**](https://agea.github.io/tutorial.md)

- Long links may decrease source readability, so it's posible to define all links somewhere in the document (the end is a good place) and just reference the [link][tutorial.md], you may also collapse the reference if it matches the link text (example:  [tutorial.md][])

- You may also write directly the link: <https://agea.github.io/tutorial.md>

- It will work also for email addresses: <email@example.com> (you may write vaild email links also using [mailto](mailto:email@example.com) as protocol)


[tutorial.md]: https://agea.github.io/tutorial.md


Images
------

Syntax for images is like the syntax for links, but with a `!` before:

![alt text](https://en.wikipedia.org/wiki/File:Wikipedia-logo-en-big.png "image title")

![](https://en.wikipedia.org/wiki/File:Wiki.png)

![ref]

[ref]: (https://en.wikipedia.org/wiki/File:Wiki.png)