<div align="center">

# MaDTeX

**Markdown to LaTeX converter with embedded Python execution**

</div>

Converts Markdown to LaTeX by first running the file through Pandoc (`markdown` to HTML) and then translating the resulting HTML tags into LaTeX with a custom recursive parser. Inline `$...$` and display `$$...$$` math is extracted before conversion and restored untouched afterwards. Features an embedded Python mode -- code inside special HTML-comment tags is `exec`'d during conversion and its stdout is inserted into the LaTeX document.

## ■ Features

- ❖ **Markdown to LaTeX** — headings, lists, tables, links, bold/italic, strikethrough, blockquotes, definition lists
- ❖ **Math preservation** — inline `$...$` and display `$$...$$` math extracted before conversion and restored verbatim
- ❖ **Code blocks** — fenced code mapped to `lstlisting`, with the fence language carried over as `[language = ...]`
- ❖ **Embedded Python** — `<!-- *code -->` tags run `exec()` and inject the captured stdout (`import`/`sys.` are blocked)
- ❖ **Raw LaTeX** — `<!-- ?\macro -->` tags pass raw LaTeX straight into the output
- ❖ **Custom commands** — `~whodo` (author), `~note` (footnotes), `~reflist`/`~ereflist` (hyperlinked reference lists), all written as HTML comments
- ❖ **Image support** — Markdown images converted to a `\image{src}{caption}` macro
- ❖ **LaTeX comments** — plain `<!-- text -->` tags become `% text`

## ■ Stack

<div align="center">

| Component | Technology |
|-----------|------------|
| Converter | Python (single script) |
| MD to HTML | Pandoc (external) |
| Parser | Custom recursive HTML to LaTeX |
| Math | LaTeX math mode |
| Output | LaTeX (`.tex`) |

</div>

## ■ How It Works

```
1. Math expressions ($...$ and $$...$$) are extracted from the Markdown source and stashed.
2. Pandoc converts the Markdown to intermediate HTML (conf/exam.html).
3. A custom recursive parser walks the HTML tags and translates them into LaTeX constructs.
4. Embedded Python blocks (<!-- *code -->) are exec'd and their stdout is injected into the output.
5. Raw LaTeX (<!-- ?\macro -->), custom commands (~whodo, ~note, ~reflist, etc.) and plain HTML comments are resolved.
6. Stashed math is restored verbatim; the final LaTeX source is written to conf/exam.tex.
```

## ■ Screenshots

<div align="center">

![Screenshot](screenshots/main.png)

*Main conversion output — generated LaTeX source from a Markdown input*

</div>

## ■ Usage

```bash
# Requires `pandoc` on PATH.
# The input file is hard-coded as exam.md at the bottom of the script.
python MaDTeX.py

# Produces:
#   conf/exam.html  — intermediate Pandoc HTML
#   conf/exam.tex   — generated LaTeX source
```

> Note: the generated `.tex` includes a hard-coded preamble path
> (`/Users/pluttan/Documents/forMyDocs/preamb.tex`); compile to PDF separately.

## ■ License

MIT © [pluttan](https://github.com/pluttan)
