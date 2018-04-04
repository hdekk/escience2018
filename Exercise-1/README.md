# Interactive knitr document
## Introduction

* Reading code is often difficult, even if you are the programmer. 
* **Literate programming** is an approach to writing code that combines plain English interspersed with code to help explain the why and how behind the code. 
* The end result is often a report that provides narrative to your work. 
* These reports alleviate many of the problems associating with computational work including:

  1. Making your code pleasurable to read.
  1. Reduction of tedium and manual processes when making changes to experiments.
  1. Reduction of friction for communication of results.
  1. Begins the process of writing papers as the data, figures and rationale for each project are all in one place and can be copied and edited when writing your papers.

* Essentially literate programming acts as your lab notebook for your computational work.
* As with scientific notebooks, there are many styles to writing in one. 
* Every project is unique, but the end goal is always to make it as easy as possible for you and others to reproduce your work.

* In this lesson we are going to use `RStudio` to combine `R` code, markdown, and knitr to create reports that can be saved in many formats for distribution. 
* Depending on the language you can combine the same or similar tools for creating literate programming reports, for example for `Python` reports, `IPython` and `Project Jupyter` are powerful options.

### Step 1: Open .Rmd Document and Run Code

Open [countryPick4.Rmd](https://github.com/datacarpentry/rr-literate-programming/blob/gh-pages/files/lit-prog/countryPick4.Rmd). This is a report exploring population size of four countries.

Save this document with a new filename. The filename should end in `.Rmd`.

>##Challenge 1 - Modify the report. 
> 1. Re-run the report, but modify the code to choose four new countries. 
> 2. (Bonus) If you are familiar with `R` and `ggplot`, try adding a fifth country to this report.


### Step 2: Save new report and knit

Click on “Knit HTML” or do `File > Knit`. `RStudio` should display a preview of the resulting HTML. Also look at the file browser (which should be pointed at the directory where you saved the .Rmd file). You should see the `RMarkdown` document, i.e. `foo.Rmd` and the resulting HTML `foo.html`.

- Distinguish what was the input and output in creating this document. What role did the `.Rmd` file take and what the .html file?
- Which file can you delete while still being able to fully reproduce the result? What are all the files that are needed to re-create the `.html` file?

