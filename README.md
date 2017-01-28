# latex-macros

Add the .sty file to either the folder where the latex document is, or to the appropriate part of your `texmf`
directory, which is found at:

Windows: `C:\Users\<user name>\texmf\tex\latex\local\`

Mac: `/Users/<user name>/Library/texmf/tex/latex/local/`

Linux: `~/texmf/tex/latex/local/`

Then, just need

`\usepackage{mathmacros}`

before `\begin{document}`. I think you might need the package `amsmath`, I didn't really go through and play around
with the dependencies. Feel free to propose additions to the file; these are just the few I've used relatively recently.
