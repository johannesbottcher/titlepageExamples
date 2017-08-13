# Examples of LaTeX title pages

Some titlepages done in LaTeX, a png preview is available for
some of them. Click on *view Code* on mobile devices to get the
list of files.

Those are mere examples, there is no warranty that the code will
work for your projects or that the code is in any form *correct*.
Use it at your own risk and with some common sense.  All examples
are self-contained and ready to compile. In most examples, the
documentclass can be changed if needed.  Special requirements
will be noted in comments. There is absolutely no naming scheme,
names will mostly consist of animal names. If you decide to use
one of the examples as a base for your own titlepage, please
leave a link to the example in your tex-code.

-------

[The titlepage is one of the first pages of a book or thesis. This
page contains only the title in a fashion similar to the rest of
the text within the
book.](http://en.wikipedia.org/wiki/Title_page)

That is what Wikipedia tells us, now we have a perspective to
follow, the titlepage should match the appearance of the rest of
the book or thesis or report. That means at least, that the font
has to match.

A titlepage, not to be confused with a cover, is somehow static.
It often needs special formatting (especially margins), to follow
some university requirements. It is possible to change the page
layout just for the titlepage, but it isn't worth the trouble. It
is much easier to simply generate the titlepage in an extra
document and include it in the real project using package
`pdfpages`.


Some of the examples here come from the inital answer at [How to
customize my
titlepage](http://tex.stackexchange.com/questions/209993/how-to-customize-my-titlepage).
Many more examples of titlepages can be found at [TitlePages on
CTAN](https://www.ctan.org/tex-archive/info/latex-samples/TitlePages).


Almost all examples use the `titlepage`  environment. If you are
going to include the titlepage as a separate pdf in your main
document, you can replace the environment by a simple
`\pagestyle{ampty}`.
