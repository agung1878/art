---
layout: post
title: "Markdown Syntax"
date: 2018-04-12 13:51:59 +0700
comments: true
categories: 
---

As u know octopress use markdown as a result file, and for that there is different syntax from html basic.
So here example syntax for writting in markdown.

==HEADER==

Codes:
```ruby
# H1
###### H6
```
Result:

# This is H1
###### This is H6

. . .

==LISTS==

Unordered

Codes:
```ruby
* Item 1
* Item 2
* Item 2a
* Item 2b
```
Result:

* List Unordered 1
* List Unordered 2
* List Unordered 2a
* List Unordered 2b


Ordered

Codes:
```ruby
1. Item 1
2. Item 2
3. Item 3
 * Item 3a
 * Item 3b
```
Result:

1. List Ordered 1
2. List Ordered 2
3. List Ordered 3
 * List Ordered 3a
 * List Ordered 3b

. . .

 ==IMAGES==

 Codes:
```ruby
![Linux Logo](/images/logo.png)
```
Result:

![Linux Logo](/images/linux.png)

As of this writing, Markdown has no syntax for specifying the dimensions of an image; if this is important to you, you can simply use regular HTML ```<img>``` tags.

. . .

==Links==

Codes:
```ruby
http://google.com - automatic!
[Google](http://google.com)
```
Result:

http://google.com - automatic!
[Google](http://google.com)

. . .

==BLOCKQUOTES==

Codes:
```ruby
As Grace Hopper said:
> I’ve always been more interested
> in the future than in the past.
```
Result:

As Grace Hopper said:
> I’ve always been more interested
> in the future than in the past.

. . .

==BACKSLASH ESCAPES==

Markdown allows you to use backslash escapes to generate literal characters which
would otherwise have special meaning in Markdown’s formating syntax.

Codes:
```ruby
\*literal asterisks\*
```
Result:

\*literal asterisks\*


Markdown provides backslash escapes for
the following characters:
Codes:
```ruby
\ backslash
` backtick
* asterisk
_ underscore
{} curly braces
[] square brackets
() parentheses
# hash mark
+ plus sign
- minus sign (hyphen)
. dot
! exclamation mark
```

