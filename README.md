# Note

## Bibliography engines

By default, `.vscode/settings.json` uses biber and biblatex configs, which are hardcoded in `latex-workshop.latex.recipes`. If one wishes to change or revert to this default, try to update using one of the following configs.

### Biber and biblatex (default)

```json
{
    "name": "pdflatex ➞ biber ➞ pdflatex`×2",
    "tools": [
        "pdflatex",
        "biber",
        "pdflatex",
        "pdflatex"
    ]
},
{
    "name": "xelatex ➞ biber ➞ xelatex`×2",
    "tools": [
        "xelatex",
        "biber",
        "xelatex",
        "xelatex"
    ]
},
{
    "name": "lualatex ➞ biber ➞ lualatex`×2",
    "tools": [
        "lualatex",
        "biber",
        "lualatex",
        "lualatex"
    ]
}
```

### Natbib and bibtex

```json
{
    "name": "pdflatex ➞ bibtex ➞ pdflatex`×2",
    "tools": [
        "pdflatex",
        "bibtex",
        "pdflatex",
        "pdflatex"
    ]
},
{
    "name": "xelatex ➞ bibtex ➞ xelatex`×2",
    "tools": [
        "xelatex",
        "bibtex",
        "xelatex",
        "xelatex"
    ]
},
{
    "name": "lualatex ➞ bibtex ➞ lualatex`×2",
    "tools": [
        "lualatex",
        "bibtex",
        "lualatex",
        "lualatex"
    ]
}
```