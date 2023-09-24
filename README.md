
<!-- README.md is generated from README.Rmd. Please edit that file -->

# tesesusp

<!-- badges: start -->

[![Project Status: WIP – Initial development is in progress, but there
has not yet been a stable, usable release suitable for the
public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)
[![License:
MIT](https://img.shields.io/badge/license-MIT-green)](https://choosealicense.com/licenses/mit/)
<!-- badges: end -->

## Overview

`tesesusp` is a [Quarto](https://quarto.org) format designed for theses
and dissertations of the University of São Paulo (USP). It is based on
the [`abntex2`](https://www.abntex.net.br/) suite, the
[`abntex2ppgsi`](https://www.overleaf.com/project/64f7bdf1641ad4a3a8482800)
template, and adheres to the [USP guidelines for creating thesis and
dissertation
documents](https://teses.usp.br/index.php?option=com_content&view=article&id=52&Itemid=67&lang=en).

This format extension also includes a [Quarto
book](https://quarto.org/docs/books/) template based on the [R
programming language](https://www.r-project.org/). While you can use
[other Quarto supported
languages](https://quarto.org/docs/computations/python.html) with this
format, some adaptations may be necessary.

For more detailed information about USP guidelines, please visit
<https://teses.usp.br>.

You can view a preview of the rendered template in the `preview` folder.

<!-- To see a practical example of this Quarto format, you can refer to <https://github.com/danielvartan/mastersthesis>. -->

## Instalation

To create a new thesis from scratch, use the following command:

``` bash
quarto use template danielvartan/tesesusp
```

This command will install the extension and generate an example `qmd`
file and bibliography that you can use as a starting point.

You can also use this format with an existing Quarto project or
document. To do so, navigate to the Quarto project or document directory
and run the following command:

``` bash
quarto add danielvartan/tesesusp
```

## Usage

To apply the format, you can use the format name `tesesusp-pdf`. For
example:

`quarto render --to tesesusp-pdf`

or in your document `yaml`

``` yaml
format:
  tesesusp-pdf:
    babel-lang: english
```

Since USP guidelines are plentiful, some formatting had to be made using
alternative ways. The easy way to start using `tesesusp` is cloning this
repository and building on top of its [Quarto
book](https://quarto.org/docs/books/).

<!-- ## Format Options -->
<!-- See <https://github.com/quarto-journals/elsevier>. -->
<!-- See <https://quarto.org/docs/extensions/formats.html>. -->
<!-- *TODO*: If your format has options that can be set via document metadata, describe them. -->
