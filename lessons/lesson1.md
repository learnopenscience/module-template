# Lesson 1: using Markdown

In the module template, we use the `lesson1.md` file as a sample lesson, and introduce you to the flavor of Markdown that you will use to write the content, called **MyST Markdown**.

Whether you write your book's content in Jupyter Notebooks (`.ipynb`) or
in regular markdown files (`.md`), you'll write in the same flavor of Markdown.
This file shows some example syntax.

## What is MyST?

MyST stands for "Markedly Structured Text". It
is a variation on so-called "CommonMark" markdown,
with some syntax extensions to allow you to write **roles** and **directives**.
These offer customization and styling for the final content, based on the Sphinx documentation format.

For example, you can use a directive to get a nicely formatted Note in the final document like this:

````
```{note}
Here is a note
```
````

Other directives can produce styled boxes for: Warning, Caution, See also, and Tip.

More about MyST in the JupyterBook documentation: [MyST Markdown Overview](https://jupyterbook.org/content/myst.html).



## Citations

You can cite references from a `bibtex` file using `{cite}` roles. Several in-line citation styles are possible. 

To insert a bibliography into your page, you will use the `{bibliography}` directive. For example, if the references for your book are stored in `references.bib`,
then the bibliography is inserted with:

````
```{bibliography}
```
````