# What is "arxivist" ?
"arxivist" is a LaTeX package that creates a dense two-column style similar to what can be found on arXiv. It is easy to use, with minimal modifications of a standart LaTeX article file.

# How to use

- Include the .sty file in the same folder as your .tex
- Add `\usepackage{arxivist}` after the other `usepackage` commands
- Put all the main content of your article (everything after the abstract and before the bibliography) in the environment "maincontent" (with `\begin{maincontent}` and `\end{maincontent}`). Otherwise it won't be in two columns.
- Compile ! (I have only tested this with pdflatex, it might not work with other compilers)

# Development

Ideally, I would want the figures to be only on one column, as part of the two-column layout, but couldn't figure out how to do this. 
Other minor adjustments and personalizations could also be done.
