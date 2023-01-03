# Welcome to test MkDocs

A PDF version of this document is available [here]({{ pdf_url }}).  

For full documentation visit [mkdocs.org](https://www.mkdocs.org).
PDF generated by [mkdocs-with-pdf](https://github.com/orzih/mkdocs-with-pdf/blob/master/README.md).  

## Test env vars

 - test_var: **{{ test_var }}**
 - test_var2: **{{ test_complex_obj.test_var2 }}**
 - test_var3: **{{ test_complex_obj.test_var3 }}**

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## Code test

Some Python code


``` py title="Some Python test code" linenums="1"
test = True
if test:
    print('Test ok')
```

Some JS


``` js title="some-code.js"
test = true;
if (test == true):
    console.log('Test ok');
```

## Image test

<img class="cordoba-river-imag"
    src="{{ assets_folder }}/img/cordoba-rio.jpg" alt="Cordoba river"
    title="Cordoba river"
    style="float: left; width: 150px; padding: 14px; margin: 14px; border: 2px solid red"/> 

This image has a style for html and a different one for PDF.   