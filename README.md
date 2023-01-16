# Mdbook Custom theme

This is a custom theme for mdbook, focused on writing math texts and notes, it takes inspiration from latex generated documents.

## How to Install

1. First you need to **install mdbook** on your computer. You can see the mdbook installation guide [here](https://github.com/Danelnov/mdbook-template.git).

2. Copy the content of `custom.css` to a file with the same name.

3. Add in your `book.toml` the following lines:
    ```toml
    [output.html]
    additional-css = ["custom.css"]
    ```

You now have the theme installed in your book. Optionally for writing mathematical texts it is recommended to install [mdbook-katex](https://github.com/lzanini/mdbook-katex).

