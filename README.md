# *Doing Bayesian Data Analysis* in brms and the tidyverse

Kruschke began his text with "This book explains how to actually do Bayesian data analysis, by real people (like you), for realistic data (like yours)." Agreed. Similarly, this project is designed to help those real people do Bayesian data analysis. My contribution is converting Kruschke's JAGS code for use in Bürkner’s [brms package](https://github.com/paul-buerkner/brms) for fitting Bayeisn regression models in R using HMC. I also prefer plotting with Wickham's [ggplot2](https://cran.r-project.org/web/packages/ggplot2/index.html), and recently converted to using [tidyverse](https://www.tidyverse.org)-style syntax (which you might learn about [here](http://r4ds.had.co.nz/transform.html) or [here](http://style.tidyverse.org)). So we'll be using those methods, too.

This project is not meant to stand alone. It's a supplement to the second edition of [Kruschke’s *Doing Bayesian Data Analysis*](https://sites.google.com/site/doingbayesiandataanalysis/). I follow the structure of his text, chapter by chapter, translating his analyses into brms and tidyverse code. However, many of the sections in the text are composed entirely of equations and prose, leaving us nothing to translate. When we run into those sections, the corresponding sections in this project will be blank or even missing.

I reproduce the bulk of the figures in the text, too. However, I don't always reproduce them exactly. I’m passionate about data visualization and like to play around with [color palettes](https://github.com/EmilHvitfeldt/r-color-palettes), formatting templates, and other conventions from time to time. For more on visualization, chapters [3](http://r4ds.had.co.nz/data-visualisation.html), [7](http://r4ds.had.co.nz/exploratory-data-analysis.html), and [28](http://r4ds.had.co.nz/graphics-for-communication.html) in *R4DS* or Healy’s [*Data Visualization: A practical introduction*](https://socviz.co).

While this is still in the working-project phase, I’ll update chapters in .Rmd files and those rendered as `output: github_document`. However, the long-term goal is to stitch all this together as a coherent [bookdown](https://bookdown.org) document. With any luck, I’ll have the first version of that up sometime in the fall of 2018.
