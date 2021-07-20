# quant-bio 

A repository for building the document for our five modules. To build it you need the available modules (in our quantitative-biology organisation) cloned to your computer, and then:

In RStudio, click the render button (not the knitr) button. **Luwen - is that correct??????**

In R,
 
```
bookdown::render_book("index.Rmd", "bookdown::gitbook")
```

If you get errors such as it not finding an `.Rmd` file, then make sure you've updated (`git fetch` and `git rebase`) for each separate repository called `module-X-...`. 

You'll need to install some R packages for some of the modules, so check the error messages you get.

We should list all required packages in `preamble.Rmd` so that are all loaded up front (and give errors straight away if they need installing).

To colour your text in red, use `r colorize("this text is in red")`, and for other colours do `r colorize("this text is in blue", "blue")` etc. (The function is in `preamble.Rmd` and gets loaded into R when running the full `bookdown`; for running a chapter alone just copy the function into your R console if you need it).
   


