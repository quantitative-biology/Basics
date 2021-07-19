# quant-bio 

A repository for building the document for our five modules. To build it you need the available modules (in our quantitative-biology organisation) cloned to your computer, and then:

In RStudio, click the render button (not the knitr) button. **Luwen - is that correct??????**

In R,
 
```
bookdown::render_book("index.Rmd", "bookdown::gitbook")
```

You'll need to install some R packages for some of the modules, so check the error messages you get.


