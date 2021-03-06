---
title: File extensions
layout: topic
order: 103
---

It is a convention to indicate a file's type by putting a dot followed by a
code at the end of its name. 

The code is called the file's _extension_ and is often — but not always — three
letters long.

This is only a convention but it's a very useful one, that's helpful to humans
and computers: it allows you to reliably guess what kind of file something is.

For example, `assignment-3.pdf` has the extension "pdf". This _suggests_ it is
a PDF document ("Portable Document Format"), and not a spreadsheet or a Python
program.

However, it is _only_ a convention: the extension is only advisory, and _really_
it's just part of the name. Most graphical user interfaces will warn you if you
try to change the extension on a filename, because it often causes confusion
later.

> You put a tiger in a box, and put a label on the box that says `TIGER`.
> That might be helpful to the next person who opens the box. If you then
> change the label (that's like renaming the file) to `FOOTBALLS`, obviously
> the box still contains a tiger.
>
> <div class="center not-too-wide"><img alt="tiger in a box marked FOOTBALLS" src="{{site.baseurl}}/images/tiger-box.svg"></div>
>
> Changing the name doesn't affect its contents. But it _will_ probably affect
> how people treat that box, and what happens when they open it.

It's very common for your computer to choose which application or program to
use to open a file based on its extension — so be very careful about deviating
from this convention. There are other ways to determine what type of thing is
really inside a file, but it's not as straightforward as you might expect so
the file extension convention is very widely used.

However, in computer science you are very often dealing _directly_ with files,
so you can and should call them what you want. From your point of view, the
filename, including the extension, is often just a name. Be disciplined about
how you use extensions.

A filename does not need to have an extension. Directories — which in many ways
are really just another kind of file — typically do not.

A filename can contain more than one dot. The extension is comprised of the
characters after the _last_ dot.

In earlier versions of some operating systems, filenames needed to have a
three-letter extension. That is no longer the case, but it's where the
convention of three-letters comes from.

