# Packaging Code {#package}

One of the difficulties that can arise in the more manual methods of statistics production is that we have many different files relating to many different stages of the process, each of which needs to be documented, and kept up to date. Part of the heavy lifting can be done here with version control as described above, but we can go a step further: we can create a package of code. As Hadley Wickham (author of a number of essential packages for package development) puts it for R:

> Packages are the fundamental units of reproducible R code. They include reusable R functions, the documentation that describes how to use them, and sample data.
- Hadley Wickham

Since it is a matter of statute that we produce our statistical publications, it is essential that our publications are as reproducible as possible. Packaging up the code can also help with institutional knowledge transfer. This was exemplified in Chapter \@ref(exemplar) where we explored help files associated with code using the R `?` function.


```r
library(eesectors)
?clean_sic()
```


Linking the documentation to the code makes everything much easier to understand, and can help to minimising the time taken to bring new team members up to speed. This all meets the requirements of the [AQUA](https://www.gov.uk/government/publications/the-aqua-book-guidance-on-producing-quality-analysis-for-government) book in that all assumptions and constraints can be described in the package documentation asssociated tied to the relevant code.  