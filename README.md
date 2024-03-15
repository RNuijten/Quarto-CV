# CV
 
I would like to acknowldge Cynthia A Huang for creating the initial Quarto CV template (https://www.cynthiahqy.com/posts/cv-html-pdf/). Furthermore, the icons that can be found in the pdf version of the CV are from:

* academicons (https://jpswalsh.github.io/academicons/)
* iconify (https://icon-sets.iconify.design/)



Rendering of the html/pdf files was done using the weasyprint engine, which requires the following software installations:

* quarto (installation instructions here: https://quarto.org/docs/download/)
* weasyprint (installation instructions here: https://doc.courtbouillon.org/weasyprint/v52.5/install.html#windows)
* weasytools (R installation command: devtools::install_github('RLesur/weasydoc'))


Rendering was done from the command line, following the activation of the Python Environment with Quarto. Use this command:
* quarto render cv.qmd --to html --output-dir docs