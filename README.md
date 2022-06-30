# Fontys beamer theme

A beamer theme implementing the Fontys style ([huisstijl](https://fontys.nl/Fontys-Huisstijl-Positionering-en-profilering-1.htm)).

An example of this theme can be found [here](/example.pdf)

## Installation

The default paths for latex beamer templates are the following:

Linux:
```sh
$HOME/texmf/tex/latex/
```

MacOS
```sh
$HOME/Library/texmf/tex/latex/
```

Windows:
```sh

```

Install the theme:

- Git:
  - clone the repository in the default path
- Manually:
  1. Create a new folder in the default directory
  2. Copy all the `.sty` files from this directory into the newly created folder

## Usage

Start by specifying that you want to use Beamer (aspectratio is optional)

```latex
\documentclass[aspectratio=169]{beamer}
```

Now we can specify that we want to use the Fontys theme

```latex
\usetheme[lang=en]{Fontys}
```

The language option is used to include the correct images for either the Dutch (NL) template or the international (EN) template, for more information see [huisstijl](https://fontys.nl/Fontys-Huisstijl-Positionering-en-profilering-1.htm).

The theme so for has support for two slide types, the normal slide and the title page slide.

Normal slide:
```latex
\begin{frame}
    \frametitle{Title}}
\end{frame}
```

Title page slide:
```latex
\begin{titleframe}
    \titlepage
\end{titleframe}
```