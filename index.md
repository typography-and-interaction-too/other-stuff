---
---



# Stuff we didn’t get to!

[CSS variables](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties) (*custom properties*) help make modular, adjustable *design systems*.

> CSS variables are *set*/*declared* with a `--name: value;` syntax.
>
> They are *accessed*/*referenced* with `var(--name)`, wherever you would use a CSS *value*—colors, lengths, fonts, anything.
>
> You can also have a *fallback* value that will be used, `var(--name, fallback)`, if the variable doesn’t exist!

> Variables can be *set*/*declared* at any DOM level.

> Their value is set for all of the descendants of that element.
>
> The variables are not visible to siblings.



<!-- Writing in HTML here, just to have this highlight container. -->
<div>
	<h2>Line/bounding box</h2>
</div>

HTML renders a lot of extra space around text elements, called the [*line box*](https://iamvdo.me/en/blog/css-font-metrics-line-height-and-vertical-align) (or, in design software parlance, the *bounding box*).

It is based on the `font-family`, the `font-size`, and the `line-height`. But this makes it difficult to position type precisely—especially at large sizes! It’s always annoying, and you’ll often be adding/subtracting your spacing to account for it.

Let’s avoid it. We can use [pseudo-elements](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements), `:after` / `:before`—which are entirely created by CSS, not in your DOM—to negate this space with negative `margin`. By doing this on the pseudo elements, we can still position the parent normally.

<div>
	<h3>Much better!</h3>
</div>


