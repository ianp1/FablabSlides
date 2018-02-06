## Slide-Template for Fablab Lübeck

This is a fork of [Metropolis](https://github.com/matze/mtheme) to provide a slide-template for members of fablab lübeck

## Installation

To install a stable version of this theme, please refer to update instructions
of your TeX distribution. Metropolis is on [CTAN][] since December
2014 thus it is part of MikTeX and will be part of TeX Live 2016.

Installing Metropolis from source, like any Beamer theme, involves four easy
steps:

1. **Download the source** with a `git clone` of the [Metropolis repository](https://github.com/matze/mtheme) or as a [zip archive](https://github.com/matze/mtheme/archive/master.zip) of the latest development version.

2. **Compile the style files** by running `make sty` inside the downloaded
    directory. (Or run LaTeX directly on `source/metropolistheme.ins`.)

3. **Move the resulting `*.sty` files** to the folder containing your
   presentation. To use Metropolis with many presentations, run `make install`
   or move the `*.sty` files to a folder in your TeX path instead (might require
   `sudo` rights).

4. **Use the theme for your presentation** by declaring `\usetheme{metropolis}` in
    the preamble of your Beamer document.


## Usage

The following code shows a minimal example of a Beamer presentation using
Metropolis.

```latex
\documentclass{beamer}
\usetheme{metropolis}           % Use metropolis theme
\title{A minimal example}
\date{\today}
\author{Matthias Vogelgesang}
\institute{Centre for Modern Beamer Themes}
\begin{document}
  \maketitle
  \section{First Section}
  \begin{frame}{First Frame}
    Hello, world!
  \end{frame}
\end{document}
```

Detailed information on using Metropolis can be found in the [manual][].

For an alternative dark color theme, please have a look at Ross Churchley's
excellent [owl](https://github.com/rchurchley/beamercolortheme-owl) theme.


## License

The theme itself is licensed under a [Creative Commons Attribution-ShareAlike
4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/). This
means that if you change the theme and re-distribute it, you *must* retain the
copyright notice header and license it under the same CC-BY-SA license. This
does not affect the presentation that you create with the theme.

