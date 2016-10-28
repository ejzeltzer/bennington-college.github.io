---
layout: page
title: About
permalink: /markdown/
---

## About (h2)
> Blacksheep music is a New-England based collective for friends and artists alike. The basic idea is that we (the artists)
> pool resources and energy together in order to help one another achieve both personal and cooperative artistic projects. Ultimately,
> we hope to collect enough funds to establish a communal recording studio. If interested in getting involved, email elizeltzer@bennington.edu
Make a link by putting the text in square brackets, followed by the url in parentheses:

> For a complete markdown reference, see [here](http://kramdown.gettalong.org/syntax.html#link-definitions).

To render an image, put an exclamation mark in front of a link to the image file (the link text becomes metadata for search engines and screen readers).

![Apples and Oranges (Cezanne)](/assets/image.jpg)

A code block:

```js
if ( honor.pawn() === honor ) {
	console.log(Object.getOwnPropertyNames(honor.prototype));
}
```

A list:

- Forgotten ideas
- Commentaries
- Dialogues


{% comment %}
Include an include:
{% include my-themes-great-include.html %}
{% endcomment %}

