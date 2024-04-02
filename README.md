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
  - Clone the repository to the default path
- Manually:
  1. Create a new folder to the default directory
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

The theme has support for two slide types, the normal slide and the title page slide.

We can also specify if we want to use dark mode. By default it is not enabled, if you would like to enable it, modify theme declaration

```latex
\usetheme[lang=en, mode=dark]{Fontys}
```

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

## Colours

The following colours are available by default and can be used by their name:

| Name | Color |
| --- | --- |
| fontys |  ![fontys](images/fontys.png) |
| fontyspink | ![fontys](images/fontyspink.png) |
| fontysblue | ![fontys](images/fontysblue.png) |
| fontystitle | ![fontys](images/fontystitle.png)|
| slidebgcolor | ![fontys](images/slidebgcolor.png) |
| slidetextcolor| ![fontys](images/slidetextcolor.png) |
| f-secondary-blue | ![fontys](images/f-secondary-blue.png) |
| f-secondary-cyan | ![fontys](images/f-secondary-cyan.png) |
| f-secondary-dark-green | ![fontys](images/f-secondary-dark-green.png) |
| f-secondary-green | ![fontys](images/f-secondary-green.png) |
| f-secondary-dark-orange | ![fontys](images/f-secondary-dark-orange.png) |
| f-secondary-orange | ![fontys](images/f-secondary-orange.png) |
| f-secondary-yellow | ![fontys](images/f-secondary-yellow.png)| 
| f-grey | ![fontys](images/f-grey.png) |
