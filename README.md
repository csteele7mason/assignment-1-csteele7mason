# Assignment 1: R Markdown practice

## Instructions

<table>

<tbody>

<th>First-time RStudio Server configuration</th>

<tr>

<td>

**2 Very Important Things!**

1. Before you start working on this assignment you first need to set-up RStudio. If you have already worked through the first CDS 102 lab (Lab 0), then you do not need to do this again. Otherwise, please follow **all** the directions in this section of the supplementary textbook: [RStudio Initial Set-up](https://book.cds101.com/initial-set-up.html)

2. Before you can finish this assignment, you will need to install an R package called `caTools`. To do so, please run the following two lines of code in the RStudio Console:

        require(devtools)
    
        install_version("caTools", version = "1.17.1.4", repos="https://cloud.r-project.org")


</td>

</tr>

</tbody>

</table>

### What you need to do

This GitHub repository contains a starter file called `rmarkdown_practice.Rmd`. Open this file in RStudio and click the *Knit* button at the top of the editing pane. You should see a PDF appear, corresponding to the current contents of the `rmarkdown_practice.Rmd` file.

Your job is to edit the contents of the `rmarkdown_practice.Rmd` file in RStudio so that when you Knit it to a PDF, it matches the contents and formatting of this example file (except for the diagonal watermark, and the date (see Tips below)): [`rmarkdown_practice_answer.pdf`][rmarkdown-recreate-pdf]. Use the examples from the [`RMarkdown reference guide`][rmarkdown-reference] to format the RMarkdown file correctly.

Useful tips:

* The `rmarkdown_practice.Rmd` template file is divided into two sections. 
  * The top of the file contains metadata and formatting instructions. These are provided to you, but you may need to edit their contents to get the correct formatting. 
  * Below that is a section where you will need to enter the main text of the document.
* At the top of the document, make sure that you've replaced [FirstName LastName]{.monospace} with your name.
* Also, the date at the top of your knitted document will, by default, display the current date. This is okay and you do not need to change it to match the sample document.
* Make sure to replace the location of the class with the actual room that your section of CDS 101 is held in. If you are in an online section, you can put **Online** instead of a room.
* Use the examples from the [`RMarkdown reference guide`][rmarkdown-reference] to format the RMarkdown file correctly.

When you're ready to submit, follow the directions in the **[How to submit](#how-to-submit)** section below.


## How to submit

To submit your assignment, follow the two steps below.
Your homework will be graded for credit **after** you've completed both steps!

1.  Save, commit, and push your completed R Markdown file so that everything is synchronized to GitHub.
    If you do this right, then you will be able to view your completed file on the GitHub website.

2.  Knit your R Markdown document to the PDF format, export (download) the PDF file from RStudio Server, and then upload it to the *Assignment 1* posting on Blackboard.

## Cheatsheets

You should keep the following reference handy while working on this assignment:

*   [RMarkdown reference][rmarkdown-reference]

[rmarkdown-reference]:     https://www.rstudio.com/wp-content/uploads/2015/03/rmarkdown-reference.pdf
[rmarkdown-recreate-pdf]:  https://drive.google.com/file/d/1mNQ9dD7Anallf0OTiUZ2mCrjxOUpasBr/view?usp=sharing

