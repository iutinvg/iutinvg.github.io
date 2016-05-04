---
layout: post
title: The Best Practices of Programming
---

There is a collection of practices which are useful during daily programmer job. For me, the main reason why I could say they are useful is that they allow to save time. Especially when it comes to a necessity a process setup.

Besides when you "obey" them in middle time period you find that they have substantial impact on codebase quality and maintenance cost.

## 1. The Twelwe-Factor App

The most common principles are described as [The Twelwe-Factor App](http://12factor.net/), which, as a fact, covers the most important aspects of applications development. They seems to be obvious, however, please consider the job of putting them clearly as a very well structured document.

## 2. Semantic Versioning

That's about software version management describe at <http://semver.org/>.

Again, following the simple rules saves plenty of your time which can spend resolving real tasks instead inventing the wheel.

## 3. Design Patterns

This is not a list of rules, it's an subject where you have to obtain knowledge everyday. Design patterns are general solution for a common programming problems.

For me in particular, it's quite thrilling to know how every practice can be implemented in different languages. Though, most of design patterns desciptions are language agnostic.

Some meterials to start with:

* [Design Patterns Book](http://c2.com/cgi/wiki?DesignPatternsBook) by [Gang of Four](http://c2.com/cgi/wiki?GangOfFour)
* [Refactoring: Improving the Design of Existing Code](http://www.amazon.com/Refactoring-Improving-Design-Existing-Code/dp/0201485672) by [Martin Fowler](http://www.martinfowler.com/)

## 4. The Zen

From time to time we spend time thinking of really weird stuff like what would be more correct coding style

```
if skip:
    return

for i in array:
    # ...
```

or

```
if not skip:
    for i in array:
        # ...
```

So if you find it important then consider a set of simple principles put into neat aphorisms: [The Zen of Python](https://www.python.org/dev/peps/pep-0020/). Ignore "of Python", it works for any language.

So, saying about coding styles, we won't find it surprising that [Android Code Style](http://s.android.com/source/code-style.html) is quite detached from Java actually.

---

Now let's switch from common practices (which seems to be abstract and boring until get into real troubles on your project) to more concrete things. The additional tools which can be used in conjunction with your favourite cosy editor.

## 5. Use Linters

A linter is a program that checks code for stylistic or programming errors. Usually it's a part of your IDE, but can be a plugin of an editor and even as a separate application.

As rule linters are language specific. For example, [Flake8](https://flake8.readthedocs.io/en/latest/) is a linter for Python, which is very simple to use:

```
>> flake8 <your-python-project>
```

Enjoy the output!

Compiled languages such as C++ also have similar tools. They are called *static analysis tools*. For example [Cppcheck](http://cppcheck.sourceforge.net/).

## 0. Reading

Yes, it's not a typo: **Zero**. The top. The most important practice for a software developer is the reading of books. Of books. Not blog articles, which can be quite entertaining because authors are talented writers and nice persons on the whole. I'm not saying it's always bad, but too often it's wasting of your time.

The reading of real books can be far less easy and smooth in comparison to glossy screens of the "yet-another-guy-who-found-a-cool-tool". Consider how "glamorous" [these books](https://en.wikipedia.org/wiki/The_Art_of_Computer_Programming) are. I promise you will struggle on every section.

There is an opinion that the effort you spend reading books should be equal to your daily job efforts.
