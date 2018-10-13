# Package description

This package creates includes an RMarkdown template for the Anatomy of Morbidity project.

# Installation instructions

To install the template, run the following code in R:

```
  install.package('devtools')
  devtools::install_github('raiphilibert/anatomyOfMorbidityTemplate')
```

# Ouput
If you are using R-Studio, the template will now be on the list of templates. To create a document using the template, go to ** File > New File > R Markdown **. Select 'From Template' and you will see "Group Report".

# Tips
To include a shiny app into the Rmarkdown document, use the following line:

```
knitr::include_app("https://yihui.shinyapps.io/miniUI/", 
  height = "600px")
```
