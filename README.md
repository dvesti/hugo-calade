SLURM
================

**SLURM** is a Hugo theme that adapts the **Xmin** theme. The original
theme is intended to be e**X**tremely **MIN**imal. This extension is an
attempt to be **S**lightly **L**ess **U**n**R**ealistically **M**inimal.
My main goal though was to make sure I understand the basics of how Hugo
works.

## Getting started

To create the example site using the SLURM template into a fresh
directory:

``` r
blogdown::new_site(
  dir = "~/../Desktop/slurm", 
  theme = "djnavarro/hugo-slurm",
  theme_example = TRUE,
  sample = FALSE
)
```

By setting `theme_example = TRUE` (the default) it installs the example
site, and by setting `sample = FALSE` it prevents Hugo from
automatically including the default content.

To serve an existing site, assuming that R the working directory is set
to the home directory for the site:

``` r
blogdown::serve_site()
```
