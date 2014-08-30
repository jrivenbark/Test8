---
layout: post
title:  Sample Post
date:   2014-08-30
author: James McRivenbark
---

This is a sample post, with examples of how to create some of the common markdown elements.

# Header1

## Header2

### Header3

Some sample code:

{% highlight c# %}
int bob = 0;
for (int i = 0; i < 100; ++i;)
{
   bob = bob + i;
}
{% endhighlight %}

> "This is a blockquote.
> 
> This is the second paragraph in the blockquote.
>
> ## This is an H2 in a blockquote
> This is the last line"

Surround with asterisks for *emphasized* (same font as H3, but not a block) text.

Surround with two asterisks for **strong emphasized** (bold and highlight yellow) text.

For an un ordered list just put asterisk at the fron of each line in list

* first item
* second item

For an ordered list just number them

1. first item
2. second item


Here is a sample [link](http://daringfireball.net/projects/markdown/basics) back to a page with even more of the basics;

Here is an image inline ![alt text]({{site.baseurl }}/images/octocat-icon.png) with some text.

Here is the same image with a link [![alt text]({{site.baseurl }}/images/octocat-icon.png)](http://jekyllrb.com) inline.

