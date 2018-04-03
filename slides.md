Facilitating Reproducibility and Collaboration with Literate Programming
========================================================
author: Harrison Dekker
date: April 5, 2018
transition: fade

Getting Started
========================================================
This is a *hands on* demo. Slides and supplementary materials are available at <https://support.rstudio.com/hc/en-us/articles/200486468>. We'll be using RStudio, but to save you the trouble of installing it, I've set up RStudio Server accounts for this workshop. The server will only be accessible today, so if you want to try out the code later, you'll need to either install RStudio or use [RStudio.Cloud]<https://rstudio.cloud>.

I'm passing around a sheet with detail. Choose a username and password, then open the provided url in a web browser. If you have RStudio installed locally, you can use that instead.

Cloning from GitHub
========================================================
RStudio has built-in support for GitHub. Here's what you need to do to clone the repository for this talk.

1. Choose **New Project** from the **File** menu.
2. From the **Create Project** menu, select **Version Control**.
3. From the next menu, choose **Git**
4. Finally, type the following url into the **Repository URL** box, then click **Create Project**.

Since you're running RStudio in the cloud, you haven't actually copied any files to your local machine. They are in a directory on the server. If you want to run the presentation, find the file named slides.Rpres in the files tab in the lower right panel in RStudio.

Overview
========================================================
type:section
- Motivation for *literate programming*
- R + Markdown = RMarkdown
- RMarkdown exercise
- Academic paper: working example


Motivation
========================================================
type:section

Rethinking Programming
========================================================
> A traditional computer program consists of a text file containing program code. Scattered in amongst the program code are comments which describe the various parts of the code... In **literate programming** the emphasis is reversed. Instead of writing code containing documentation, the literate programmer writes documentation containing code.

<small>Ross Williams. FunnelWeb Tutorial Manual, pg 4. (2000)</small>

Other issues compound the problem. Scientific computing invariably involves a variety of inputs (data) and outputs (reports, more data, etc.) which, like code, benefit from organization and description.


Benefits
========================================================
* Minimize **workflow** processes that are tedious, manual.
* Better **organize** our code, data, documentation, and results.
* Facilitate **communication** and collaboration thoughout the research lifecycle
* Conduct **better science** - that is easier to interpret, repeat, and build upon.

R + Markdown
========================================================
type:section

R
========================================================


Markdown
========================================================


RMarkdown
========================================================

Interactive knitr document
========================================================
type:prompt

========================================================
* Reading code is often difficult, even if you are the programmer. 
* **Literate programming** is an approach to writing code that combines plain English interspersed with code to help explain the why and how behind the code. 
* The end result is often a report that provides narrative to your work.


Step 1: Open .Rmd Document and Run Code
========================================================
Open [countryPick4.Rmd](https://github.com/datacarpentry/rr-literate-programming/blob/gh-pages/files/lit-prog/countryPick4.Rmd). This is a report exploring population size of four countries.

Save this document with a new filename. The filename should end in `.Rmd`.

>##Challenge 1 - Modify the report. 
> 1. Re-run the report, but modify the code to choose four new countries. 
> 2. (Bonus) If you are familiar with `R` and `ggplot`, try adding a fifth country to this report.


Acknowledgement
========================================================
Parts of this presentation were adapted from Jenny Bryan's software carpentry lesson which can be found here <https://github.com/datacarpentry/rr-literate-programming>

This is a Markdown document.
========================================================
<pre>
## Medium header <!-- header 2, actually -->

It's easy to do *italics* or __make things bold__.

> All models are wrong, but some are useful. An approximate answer to the right problem is worth a good deal more than an exact answer to an approximate problem. 

Code block below. Just affects formatting here.

```
x <- 3 * 4
```
</pre>
***
## Medium header

It's easy to do *italics* or __make things bold__.

> All models are wrong, but some are useful. An approximate answer to the right problem is worth a good deal more than an exact answer to an approximate problem. 

Code block below. Just affects formatting here.

```
x <- 3 * 4
```

Slide With Plot
========================================================

![plot of chunk unnamed-chunk-1](slides-figure/unnamed-chunk-1-1.png)
