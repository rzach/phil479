# phil479
# Incompleteness and Computability

![Book Cover](http://builds.openlogicproject.org/courses/phil479/phil479.png)\ 

Textbook for Calgary's Logic III course based on the Open Logic
Project.  Covers recursive function theory, Gödel's incompleteness
theorem, models of arithmetic, and second-order logic.

This repository/directory only contains the LaTeX files and
illustrations needed to typeset the textbook _Incompleteness
and Computability_, which in turn requires the _[Open Logic
Text](http://github.com/OpenLogicProject/OpenLogic/)_.

You can [download the
PDF](http://builds.openlogicproject.org/courses/phil479/phil479-screen.pdf)
from the [Open Logic builds
site](http://builds.openlogicproject.org/), or order a hardcopy from [Amazon](https://www.amazon.com/dp/1548138088/) [[CA](https://www.amazon.ca/dp/1548138088/)] [[UK](https://www.amazon.co.uk/dp/1548138088/)] [[DE](https://www.amazon.de/dp/1548138088/)].

To install and compile:

- Download/install the _Open Logic Text_ from
  [GitHub](http://github.com/OpenLogicProject/OpenLogic/)
- Navigate to the subdirectory `courses/`
- Put the content of this repository into a subdirectory of it, say
  `courses/phil479`.

If you use `git`, this should do it:

- `# git clone https://github.com/OpenLogicProject/OpenLogic.git`
- `# cd OpenLogic/courses`
- `# git clone https://github.com/rzach/phil479.git`

Inside `courses/phil479`, you can now compile:

- `# cd phil479`
- `# pdflatex phil479-screen` or just `# make` if you have `latexmk`
  installed. (You'll also have to do `makeglossaries phil479-screen`
  to get the glossary, and `bibtex phil479-screen` for the
  bibliography.)

The file loads `phil479.tex`, which contains the actual material. It
in turn includes other files, most of them from the `OpenLogic`
repository. So you won't get a complete book unless you download into
the right subdirectory of and compile from there.

[![Creative Commons License](http://mirrors.creativecommons.org/presskit/buttons/88x31/png/by.png)](http://creativecommons.org/licenses/by/4.0/) 

_[Incompleteness and
Computability](https://github.com/rzach/phil479/)_ by [Richard
Zach](http://richardzach.org/) is licensed under a [Creative Commons
Attribution 4.0 International
License](http://creativecommons.org/licenses/by/4.0/).
