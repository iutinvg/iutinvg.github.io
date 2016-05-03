---
layout: post
title: Mastering Python, the Steps
---

Ok, you have faced Python at some point. You decided it might be awesome to
use it in your job. Probably, you already get on well with its syntax. And now
you are about to follow one of the main principles of the pros: "master your tools",
which is a journey with an indefinite destination.

Unsurprisingly, the first steps are the most complicated because the choice is
too wide and probability to waste a lot of time sorting out garbage is high.

This article is mostly about books. There are also a couple of tips which could
be useful. But the primary objective is get a list of really good books which worked
for me. And I hope it will for you to make a start your route.

## Step 1: Start a Project

Yes, it is not a book to read, but to start your own project.
Of course if you are not a lucky guy who already has a commercial project where
Python is used. So if you are not you have to create a project which would give you
practice on regular basis and which will be a source of real problems.
I strongly believe just reading without practice is wasting of time.

## Step 2: Basics

The second step is to obtain basic knowledge about standard Python features and
libraries. No, not all of them, but I would start with:

* list / dictionary comprehensions [[1]](#llists)
* decorators and functools [[2]](#ldecorators)
* collections [[3]](#lcollections)
* itertools [[4]](#litertools)
* generators [[5]](#lgenerators)

Authors of the most books below suppose you already fine with it. So it will be
very hard to read them without comprehension of the notions above. Besides, you
will enjoy the temptation to change the whole codebase of the project you are working
on at the moment as you get better with these awesome tools.

## Book 1: Python in Practice, by Mark Summerfield
What an amazing book! This is why I love
this book: it's quite short and full of deep enough explanations of the programming
technics on the whole. The author describes and compares the design patterns as deep as
it's really necessary. Neither too shallow to be mysterious, nor too profoundly to be boring.
Yes, definitely it's number one in my list.

## Book 2: Test-Driven Development with Python. Obey the Testing Goat: Using Django, Selenium, and JavaScript by Harry J.W. Percival [[6]](#lPercival)

You, probably have seen a lot of blogs and articles where authors tells how it's thrilling to ensure that test below is passing:

<pre>
a = 1 + 1
self.assertEqual(2, a)
</pre>

Well... yes, it's "awesome". Apart the fact it's useless and explains nothing just because it's disconnected from any real problem you face daily doing your job.

The book by Harry J.W. Percival is very far from these miserable "unit-test library reviews". He explains how to deal with real problems you get during testing. Besides you will also know about the test-driven design approach which might change your way for building apps tremendously.

## Book 3: Python Cookbook, 3rd Edition Recipes for Mastering Python 3 By David Beazley, Brian K. Jones

A huge collection of extremely useful programming technics and approaches. The only point which could confuse you is it explains everything in context of Python 3. But it's not a problem of the book, it's probably a problem of your choice.

My recommendation about this book is not to skip recipes. Often they sound very familiar and you think "oh, it's clear for me, next...". But look inside! I'm sure you'll find some neat and unexpected things.

## References:
<a name="llists"></a>
\[1\] The best materials are in [Python Documentation](https://docs.python.org/2/tutorial/datastructures.html#tut-listcomps). Also give special attentions to comprehensions for [Sets](https://docs.python.org/2/tutorial/datastructures.html#sets) and [Dictionaries](https://docs.python.org/2/tutorial/datastructures.html#dictionaries).

<a name="ldecorators"></a>
\[2\] <http://simeonfranklin.com/blog/2012/jul/1/python-decorators-in-12-steps/> and then <https://docs.python.org/2/library/functools.html>.

<a name="lcollections"></a>
\[3\] <https://docs.python.org/2/library/collections.html>

<a name="litertools"></a>
\[4\] <https://docs.python.org/2/library/itertools.html> According to my practice, comprehension of this section is esspecially useful. It worth spending some more time reading about it as you are going to use it daily.

<a name="lgenerators"></a>
\[5\] Good luck! <http://stackoverflow.com/questions/231767/what-does-the-yield-keyword-do-in-python>

<a name="lPercival"></a>
\[6\] You can get this book for free <http://www.obeythetestinggoat.com/> though it's worth buying it.
