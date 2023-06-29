# Biophysical Journal (BJ)

This Quarto format will help you create documents for the Biophysical Journal. To learn more about biophysical journal, see [biophysj's Information for Authors page](https://www.cell.com/biophysj/author-resources). For more about Quarto and how to use format extensions, see <https://quarto.org/docs/journals/>.


This is based on the BJ Overleaf template <https://www.overleaf.com/articles/biophysical%E2%80%90journaltemplate/pxxcptphxdhv>

The LaTeX `.cls` was only changed in one place, to remove math packages as those are already handled by quarto/pandoc.

## Creating a New Article

You can use this as a template to create an article for the Biophysical Journal. To do this, use the following command:

```quarto use template quarto-journals/biophysical-journal```

This will install the extension and create an example qmd file and bibiography that you can use as a starting place for your article.

## Installation For Existing Document

You may also use this format with an existing Quarto project or document. From the quarto project or document directory, run the following command to install this format:

```quarto add quarto-journals/biophysical-journal```

## Usage 

To use the format, you can use the format names `bj-pdf` and `bj-html`. For example:

```quarto render article.qmd --to bj-pdf```

or in your document yaml

```yaml
format:
  pdf: default
  bj-pdf:
    keep-tex: true    
```

You can view a preview of the rendered template at <https://quarto-journals.github.io/biophysical-journal/>.
