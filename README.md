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
| fontys | <span style="border: 1px solid #000;display:block;width: 15px;height: 15px; background-color: rgb(102,51,102)"></span> |
| fontyspink | <span style="border: 1px solid #000;display:block;width: 15px;height: 15px; background-color: rgb(230,0,126)"></span> | 
| fontysblue | <span style="border: 1px solid #000;display:block;width: 15px;height: 15px; background-color: rgb(0,118,224)"></span> |
| fontystitle | <span style="border: 1px solid #000;display:block;width: 15px;height: 15px; background-color: rgb(102,51,102)"></span> |
|slidebgcolor | <span style="border: 1px solid #000;display:block;width: 15px;height: 15px; background-color: rgb(255,255,255)"></span> | 
| slidetextcolor| <span style="border: 1px solid #000;display:block;width: 15px;height: 15px; background-color: rgb(33,33,33)"></span> |
| f-secondary-blue | <span style="border: 1px solid #000;display:block;width: 15px;height: 15px; background-color: #0099cb"></span> |
| f-secondary-cyan | <span style="border: 1px solid #000;display:block;width: 15px;height: 15px; background-color: #008387"></span> |
| f-secondary-dark-green | <span style="border: 1px solid #000;display:block;width: 15px;height: 15px; background-color: #339933"></span> |
| f-secondary-green | <span style="border: 1px solid #000;display:block;width: 15px;height: 15px; background-color: #3ab54a"></span> |
| f-secondary-dark-orange | <span style="border: 1px solid #000;display:block;width: 15px;height: 15px; background-color: #ed7425"></span> |
| f-secondary-orange | <span style="border: 1px solid #000;display:block;width: 15px;height: 15px; background-color: #ff9900"></span> |
| f-secondary-yellow | <span style="border: 1px solid #000;display:block;width: 15px;height: 15px; background-color: #ffcc00"></span> |
| f-grey | <span style="border: 1px solid #000;display:block;width: 15px;height: 15px; background-color: #878787"></span> |