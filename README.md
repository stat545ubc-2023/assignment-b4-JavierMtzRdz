# Strings and Functional Programming in R

## Description

This repository contains two projects completed as part of **Option A - Strings and Functional Programming in R**. The selected exercises are **Exercise 1: Book Analysis** and **Exercise 2: Custom Pig Latin Function**.

## Repository Contents

-   `exercise-1_book-analysis.Rmd`: R Markdown file containing the textual analysis of "The Divine Comedy".
-   `exercise-1_book-analysis.md`: Rendered Markdown document of the analysis.
-   `exercise-1_book-analysis-files/`: Directory containing additional files generated during the analysis.
-   `exercise-2_my-pig-latin-function.Rmd`: R Markdown file demonstrating creating and using a custom Pig Latin conversion function.
-   `exercise-2_my-pig-latin-function.md`: Rendered Markdown document of the Pig Latin function.

## Exercise 1: Book Analysis of "The Divine Comedy"

This project focuses on the textual analysis of ["The Divine Comedy" by Dante Alighieri from the Project Gutenberg](https://dev.gutenberg.org/ebooks/8800). It involves the following steps:

1.  **Download of "The Divine Comedy"**: Fetching the text of "The Divine Comedy" from an external source.
2.  **Stopwords remotion**: Utilization of [tidytext](https://github.com/juliasilge/tidytext) and [Stephen Wittek's (MacGill) early modern](http://earlymodernconversions.com/computer-based-textual-analysis-and-early-modern-literature-notes-on-some-recent-research/) stopwords datasets to refine the textual analysis.
3.  **Visualization of Most Common Words**: Creation of visualizations displaying the most frequently used words categorized by the three parts of "The Divine Comedy".

## Exercise 2: Custom Pig Latin Conversion Function Creation

This exercise involves the creation of a custom function, `pig_latinator`, which converts words or sentences into a personalized version of Pig Latin. Key components of the project include:

1.  **Development of `pig_latinator` Function**: Creation of the function to format words or sentences into a customized Pig Latin format.
2.  **Rearrangement Component Implementation**: Application of specific rules to rearrange letters according to [Pig Latin on Wikipedia](https://en.wikipedia.org/wiki/Pig_Latin).
3.  **Addition Component Integration**: Retention of punctuation, uppercase logic and the flexibility to return either a vector of words or a combined string.

## How to Run Code from This Repository

### Pre-requisites

Ensure the following R packages are installed:

``` r
install.packages("tidyverse")
install.packages("tidytext")
install.packages("testthat")
devtools::install_github("JavierMtzRdz/mytidyfunctions")
```

### Steps

1.  Clone or download the repository to your local machine.

-   Launch RStudio.
-   Go to `File -> New Project`.
-   Choose `Version Control`.
-   Select `Git`.
-   In the "Repository URL" field, paste the GitHub repository URL.
-   Choose where to save the repository in the "Create project as a subdirectory of" field.
-   Click `Create Project`.

2.  Execute the `exercise-1_book-analysis.Rmd` file for a detailed analysis of "The Divine Comedy". You can knit the document by clicking the `Knit` button.
3.  Execute the `exercise-2_my-pig-latin-function.Rmd` file to understand and utilize the custom Pig Latin function. You can knit the document by clicking the `Knit` button.

## Acknowledgments:

Here are the main sources used in this project:

-   [Stephen Wittek's early modern stopwords](http://earlymodernconversions.com/computer-based-textual-analysis-and-early-modern-literature-notes-on-some-recent-research/).

-   [Tidytext stopwords](https://github.com/juliasilge/tidytext).

-   ["The Divine Comedy" by Dante Alighieri from Project Gutenberg](https://dev.gutenberg.org/ebooks/8800)
