## A LaTeX package to improve the padova theme for the beamer class.

It provides commands to generate a suitable title page and some macros to simplify tasks like highlight a text, break lines and generate a proper spaces between text blocks.


### Installation

The package can be installed locally in the same position of the main `.tex` file adding to the preamble the line
`\input{PadovaThesis.sty}`

For an installation in your LaTeX distribution, according to your operating system and distribution the procedure may vary. At [this page](https://en.wikibooks.org/wiki/LaTeX/Installing_Extra_Packages) there are some general information.


### Main commands

Commands available for the title page are (see the italian meaning):
+ `\titolo{text}`
+ `\titoletto{text}`
+ `\candidato[candidate label]{candidate}`
+ `\relatore[supervisor label]{supervisor}`
+ `\correlatore[assistant label]{assistant}`
+ `\altricorrelatori{others supervisors}`
+ `\data{date}`
+ `\affiliazione{institution}`
+ `\spazio{value}`

Commands for the slides are
+ `\evidenzia{text}`
+ `\acapo`
+ `\referenza{text}`

Other visual improved are added both on the slide and the title page.
