---
marp: true
theme: gaia
size: 16:9
paginate: true
header: "Aprendiendo Markdown con Marp"
footer: "@educacion4ti"
---

# Diapositiva 1. Encabezado Nivel 1

---
<!--
  _backgroundColor: black
  _color: white
-->

# Este es otro encabezado nivel 1

* Bullet 1
* Bullet 2
* Bulletproof

---

* Bullet 1
* Bullet 2
* Bulletproof

---


El paso clásico _“Lorem ipsum dolor sit amet…”_ se atribuye a una remixación del texto de De Finibus Bonorum et Malorum (_“En los extremos del bien y del mal”_), del filósofo romano Cicerón, de 45 aC. Más específicamente, se piensa que el pasaje proviene de las secciones 1.10.32 - 33 de su texto, con la parte más notable extraída a continuación:

>_Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, ..._

[Plataforma Educacion4TI](https://educacion4ti.moodlecloud.com/login/index.php 'Ir a educacion4TI') 

---

Quick Markdown Syntax Guide
===========================

* <http://greg.vario.us/doc/markdown.txt> - Plain text
* <http://greg.vario.us/doc/markdown.text> - Markdown applied


This guide shows you how to use Markdown instead of HTML when
writing posts or comments. Markdown is way easier to use than HTML.  

Just write in the comment box *the same way it's shown in this file*, it's
really that simple. (See bottom for more info about Markdown itself.)

---

Links
-----

For a URL or email, just write it like this:

<http://someurl>

<somebbob@example.com>


To use text for the link, write it [like this](http://someurl).

You can add a *title* (which shows up under the cursor), 
[like this](http://someurl "this title shows up when you hover").

---

Reference Links
---------------

You can also put the [link URL][1] below the current paragraph like [this][2].

   [1]: http://url
   [2]: http://another.url "A funky title"

Here the text "link URL" gets linked to "http://url", and the lines showing 
"[1]: http://url" won't show anything.


Or you can use a [shortcut][] reference, which links the text "shortcut" 
to the link named "[shortcut]" on the next paragraph.

   [shortcut]: http://goes/with/the/link/name/text
   
---

Text
----
Use * or _ to emphasize things:

*this is in italic*  and _so is this_
**this is in bold**  and __so is this__
***this is bold and italic***  and ___so is this___

Just write paragraphs like in a text file and they will display how you would expect.  A blank line separates paragraphs.

So this is a new paragraph. But any text on adjacent lines
will all end up in the same paragraph.

---

Blockquotes
----------

> Use the > character in front of a line, *just like in email*.
> Use it if you're quoting a person, a song or whatever.

> You can use *italic* or lists inside them also.
And just like with other paragraphs,
all of these lines are still
part of the blockquote, even without the > character in front.  

To end the blockquote, just put a blank line before the following paragraph.

---

Preformatted Text
----------------

If you want some text to show up exactly as you write it, without Markdown
doing anything to it, just indent every line by at least 4 spaces (or 1 tab).

    This line won't *have any markdown* formatting applied.
    I can even write <b>HTML</b> and it will show up as text.
    This is great for showing program source code, or HTML or even Markdown. 
    
(In a normal paragraph, <b>this will show up in bold</b> just like normal HTML.)
    
---

  Remember, you have to indent by *at least 4 spaces* to do it.  This paragraph won't be preformatted.
   
And if you use [reference][] links, make sure the links are indented 
by *fewer than* 4 spaces.
   
 [reference]: http://example.com/blah

(woops, that link didn't work, see? It just got displayed as preformatted text.)  

As a shortcut you can use backquotes to do the same thing while inside a normal pargraph.  `This won't be *italic* or **bold** at all.`

---

Lists
--------

* an asterisk starts an unordered list
* and this is another item in the list
+ or you can also use the + character
- or the - character

To start an ordered list, write this:

---

1. this starts a list *with* numbers
1. this will show as number "2"
1.   this will show as number "3."
1. any number, +, -, or * will keep the list going.
    * just indent by 4 spaces (or tab) to make a sub-list
        a) keep indenting for more sub lists
    * here i'm back to the second level
        
---

Headers
---------

This is a huge header
=

this is a smaller header
-

Just put 1 or more dashes or equals signs (--- or ===) below the title.

You might use the huge header at the very top of your text for a title or
something (except weblog posts usually already have a title), and use the
smaller header for subtitles or sections.


Horizontal Rule
---------------

just put three or more *'s or -'s on a line:

----------------

or you can use single spaces between then, like this:

* * *

or 

- - - - - - - 

Make sure you have a blank line above the dashes, though, or else:

you will get a header
--- 

---
Images
-----------

To include an image, just put a "!" in front of a text link:

![bg right alternate text](https://media.giphy.com/media/5A7sTpwSe204tzael4/giphy.gif)

The "alternate text" will show up if the browser can't load the image.

---

You can also use a title if you want, like this:

![bandera mexico](https://icons.iconarchive.com/icons/hopstarter/flag-borderless/96/Mexico-icon.png "icono México")

---

Escapes
---------

What if you want to just show asterisks, not italics?

* this shows up in italics: *a happy day*
* this shows the asterisks: \*a happy day\*

The backslashes will disappear and leave the asterisks.

You can do the same with any of the characters that have a special meaning
for Markdown.

---

More ways of doing headers:

# this is a huge header
## this is a smaller header
### this is even smaller
#### more small
##### even smaller
###### smallest still: `<h6>` header

---

You can use up to 6 `#` characters at the beginning of the line.   (You can optionally put them on the end, too, and they will disappear.)

---

HTML crap
-------------

Don't worry about special HTML characters. I can write an ampersand & a 
less-than sign, and they show up as I intend them to:  3 < 4.

(You can still write `&amp;` (& character) and `&lt;` (<) or `&gt;` (>) if you
want.  or ignore what I just said.)

---

About
---------

This text file shows you how to use [Markdown][] instead of crappy HTML when
writing posts or comments.
   
   [Markdown]: http://daringfireball.net/projects/markdown/syntax

Markdown is an easier way of making HTML pages from text, rather than having to
know HTML.

* See this file as it looks when [rendered with Markdown][].
* See the [original text file][].

   [rendered with Markdown]: http://greg.vario.us/doc/markdown.text
   [original text file]: http://greg.vario.us/doc/markdown.txt

---

Thanks
---------

Thanks to John Gruber and Aaron Swartz for creating Markdown.

Fin
---------

No rights reserved, do with this what you like.
Written by Greg Schueler, <greg@vario.us>



