---
layout:   post
category: software
tags:     lisp wiki
title:    LambdaWiki
---

A collaborative wiki, with a LISP syntax. And I don't mean the wiki engine is written in LISP. I mean the page content is.

...what?

Functional programming seems to have become chic again. Coming from an OO background, I have and little exposure to functional programming, save from some Scheme as an undergrad (you remember that, don't you?). Scala was a nice gateway language for me. I started to see the advantages.

LambdaWiki was my attempt at learing some of the fundamental concepts of functional programming. Writing the LISP compiler in Javascript was interesting and fun - I learned alot. Making it into a wiki started off as a goof, but it actually turned out to be semi-useful. Who'd have thought?

So, if you've ever wanted to write a link that looks like this:

```common-lisp

(defun link (url text) 
	(concat "<a href=" url ">" text "</a>"))

(link "http://kevinp.me" "Kevin's Page")

```

LambdaWiki might just be for you. [Try it out](http://lambdawiki.kevinp.me) and [check out the code](https://github.com/kevinpeterson/lambdawiki), and let me know what you think!