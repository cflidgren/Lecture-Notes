# Lecture Notes
This repository is for a collection of LaTeX typeset notes on an assortment of topics, primarily within category theory and geometry, though there is no particular goal in mind. Mostly, it's just meant to store personal notes I've made when trying to learn about a subject.

The format of the notes is such that topics are divided into lecture-sized chunks, aiming at having roughly an amount of content that could be covered in two hours, or maybe three.

**Warning:** _Very often, the notes have been prepared without too much care made, and so one should expect mistakes and, more broadly, subotimality. Furthermore, I have not typically been careful about tracking references consistently, and so there is much material left unattributed. A general rule would be that unless otherwise stated, the material is not new and can probably be found in some standard reference._


### Build instructions
Build `lectures.tex` using a modern LaTeX compilation tools, such as `latexmk` with `LuaLaTeX`. **Warning:** `pdflatex` will not work.

Each "lecture" is contained in its own file `include`d into the main file, `lectures.tex`. I use Sublime Text, with `LaTeXTools` to compile my LaTeX code; each file thus has a magic comment `%!TEX root = ../lectures.tex` at the start telling `LaTeXTools` which file to send to compilation.
