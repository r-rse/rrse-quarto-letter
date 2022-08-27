# Letter Format Template

This is a Quarto template to create `r-rse` branded letters using the letter format. It's been modified from template [mcanouil/quarto-letter](https://github.com/mcanouil/quarto-letter) distributed under an [MIT license](https://github.com/mcanouil/quarto-letter/blob/main/LICENSE).

See more details on the underlying [KOMA Script letter document class](https://ftp.cc.uoc.gr/mirrors/CTAN/macros/latex/contrib/koma-script/doc/scrguide-en.pdf)

## Creating a New Letter

You can use this as a template to create a letter.
To do this, use the following command:

```bash
quarto use template r-rse/rrse-quarto-letter
```

This will install the extension and create an example qmd file and bibliography that you can use as a starting place for your article.

## Installation For Existing Document

You may also use this format with an existing Quarto project or document.
From the quarto project or document directory, run the following command to install this format:

```bash
quarto install extension r-rse/rrse-quarto-letter
```

## Usage

To use the format, you can use the format name `rrse-letter-pdf`[^1].
For example:

```bash
quarto render template.qmd --to rrse-letter-pdf
```

or in your document yaml

```yaml
format: rrse-letter-pdf
```

You can view a preview of the rendered template at <https://mcanouil.github.io/quarto-letter/>.

[^1]: Currently only PDF is supported but HTML support will be added as soon as Paged.js is made available in [Quarto](https://quarto.org).
