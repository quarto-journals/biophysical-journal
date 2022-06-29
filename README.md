# Biophysicl Journal (BJ) Template

Use with quarto to create a manuscript suitable for submitting to the biophysical journal: <https://www.cell.com/biophysj/author-resources>

This is based on the BJ Overleaf template
<https://www.overleaf.com/articles/biophysical%E2%80%90journaltemplate/pxxcptphxdhv>

The LaTeX `.cls` was only changed in one place, to remove math packages as those are already handled by quarto/pandoc.

## Installation

```bash
quarto install extension quarto-journals/biophysical-journal
```

And then set

```yaml
format: quarto-journals/bj-pdf
```

Or use the complete template:

```bash
quarto use template quarto-journals/biophysical-journal
```

## Screenshot of the rendered template

![Screenshot](./style-guide/screenshot.png) 

