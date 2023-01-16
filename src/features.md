# Features

This theme comes with some additional features, inspired by latex generated texts.

## Blockquote


```markdown
> To use the default blockquote, use the markdown syntax to display it.
```

Produces:

> To use the default blockquote, use the markdown syntax to display it.


To change the color of the blockquote, use the tag  `<blockquote></blockquote>` and add one of the following classes: `primary`, `blue`, `green` and `yellow`

```html
<blockquote class="blue">

    # Blue blockquote

    Additionally we can use headers

</blockquote>
```

Produces:

<blockquote class="blue">

# Blue blockquote

Additionally we can use headers.

</blockquote>



> # ***Note***
> It is important that you leave a space between the tags.

## Boxes

You can enclose content around a box using the `<mbox></mbox>` tag. To change color you just have to add one of the following classes: `blue`, `green` and `yellow`.

```html
<mbox class="blue">

    ...
    
</mbox>
```

<mbox class="blue">

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam eu orci fermentum nunc accumsan pulvinar at sit amet felis. Nulla purus mauris, tincidunt eu gravida ut, viverra eget massa. Interdum et malesuada fames ac ante ipsum primis in faucibus. Morbi aliquet nulla a dictum interdum. Donec consectetur urna felis, vel egestas velit imperdiet vitae. Nam non erat efficitur, rhoncus nisi non, finibus libero. Sed viverra dapibus magna, ut commodo mauris.

</mbox>

You can also add a header, it changes its style according to the importance of the header.

<mbox class="green">

# Simple title

For this we use `#`

</mbox>

<mbox>

## Simple title

For this we use `##`

</mbox>

<mbox class="blue">

### Simple title

For this we use `###`

</mbox>

## Math

If you install [mdbook-katex](https://github.com/lzanini/mdbook-katex) you can use mathematical formulas

<mbox class="blue">

# Euler's identity

$$
e^{i\pi} + 1 = 0
$$

</mbox>

You can also write formulas inline with `\$`. for example $\sin^2 x + \cos^2 x = 1$