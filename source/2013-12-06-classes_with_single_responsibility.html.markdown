---
date: 2013-12-06 14:39 UTC
title: Code with Single Responsibility
tags: Object Oriented Design
---

# Code with Single Responsibility

Change tolerant code  is so because of its organization, not because of
its technical wizardy; furthermore, anyone can hack a program to do what
it should, but it takes a great amount of skill to write code that both 
does its job and can be easily changed by other humans.

The first step to change tolerant code is to design classes and
methods to each have a single responsibility.

What is Single Responsibilty? Sandi Metz gives us a brilliant litmus
test that also serves as a great definition:

> That [class] ought to be simple to describe. If the simplest description
> you can devise uses the word “and,” the class likely has more than one
> responsibility. If it uses the word “or,” then the class has more than
> one responsibility and they aren’t even very related.

- [Practical Object Oriented Design in Ruby, Sandi Metz,
  p.22](http://www.amazon.com/Practical-Object-Oriented-Design-Ruby-Addison-Wesley/dp/0321721330)


