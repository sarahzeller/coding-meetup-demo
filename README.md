# Coding meetup

In this repo, you can find the material from our coding meetup.

## April 3, 2024.

-   [Demonstration](https://github.com/sarahzeller/coding-meetup-demo/blob/main/demo_for_wiesbaden_janitor_fixest.R) on how to use the `wiesbaden` package to get data, how to clean it with `janitor`, and cool tricks with `fixest`.
-   [Web page](https://sarahzeller.github.io/coding-meetup-demo/demo-dropdown.html) using a drop-down selector to display different plots based on the data you select.

Further links

-   [Link](https://quarto.org/) to the quarto framework
-   [Instructions](https://happygitwithr.com/#lets-git-started) on how to link RStudio with GitHub

## July 18, 2024

### Cool functionalities and packages

-   When using `fixest::etable`, you can use the `style.tex` argument to style the output in LaTeX. Refer to the [`style.tex()`](https://lrberge.github.io/fixest/reference/style.tex.html) function for this, and specifically the `line.bottom` argument.
-   The [`panelView`](https://yiqingxu.org/packages/panelview/articles/tutorial.html#plot-treatment-missingness) package allows you to view your panel data, specifically
    -   treatment status
    -   missingness
-   The [`ghclass`](https://rundel.github.io/ghclass/articles/ghclass.html) package allows you to
    -   manage repositories for classes
    -   automatically assign students to repositories
    -   populate the repository, e.g. add instruction in the `README`
    -   include a check, e.g. if students upload a `.rmd` /`.qmd` , they also must upload the rendered `html` file.
-   The [`plotscape`](https://github.com/bartonicek/plotscape/tree/master) package allows you to interactively explore your data, and find the same data point across multiple graphs.

### IDE: `positron` instead of `RStudio`

There's a new IDE in town!
[`positron`](https://github.com/posit-dev/positron) is based on `Visual Studio Code`, but automatically ships with `R` and a great data viewer.
It's easy to switch between different `R` versions, but also to switch to `python`.

### Connecting `Overleaf` directly to your `GitHub` repository

You can connect your `Overleaf` project directly to your `GitHub` repository.
This way, you can work on your `LaTeX` document in `Overleaf`, and push changes to your `GitHub` repository.
I explain the whole process [here](https://github.com/sarahzeller/Overleaf-git-workflow).
