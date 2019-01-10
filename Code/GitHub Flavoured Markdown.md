Markdown is a way to style text on the web. You can control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like # or \*.

(Click on "raw" to view the code.)

Headers

# This is an h1 tag

## This is an h2 tag

### This is an h3 tag

#### This is an h4 tag

##### This is an h5 tag

###### This is an h6 tag

Emphasis

_This text will be italics_

_This text will also be italics_

**This text will be bold**

**This text will be also be bold**

_You **can** combine them_

Lists

Unordered

-	Item 1
*	Item 2
	-   Item 2a
	*   Item 2b

Ordered

1. Item 1
2. Item 2
	- Item 2a
	* Item 2b

Images

![GitHub Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/64px-Markdown-mark.svg.png)

Links

https://github.com - automatic!

[GitHub](https://github.com)

Blockquotes

As GitHub says:

> GitHub is how people build software.
> We're supporting a community where more than 31 million people learn, share, and work together to build software as of November 2018.

Backslash Escapes

Markdown allows you to use backslash escapes to generate literal characters which would otherwise have special meaning in Markdown's formatting syntax.

\*literal asterisks\*

_literal asterisks_

Markdown provides backslash escapes for the following characters:

\ backslash

() parentheses

' backtick

\# hash mark

\* asterisk

\+ plus sign

\_ underscore

\- minus sign(hyphen)

{} curly braces

. dot

[] square brackets

! exclamation mark

GitHub uses its own version of Markdown syntax that provides an additional set of useful features, many of which make it easier to work with content on GitHub.

Username @mentions

Typing an @ symbol followed by a username, will notify that person to come and view the comment. This is called an "@mention", because you're mentioning the individual. You can also @mention teams within an organization.

Issue references

Any number that refers to an issue or pull request will be automatically converted into a link.

\#1

defunkt#1

defunkt/github-flavored-markdown#1

Task lists

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
-[x] this is a complete item
-[] this is an incomplete item
