
<!-- README.md is generated from README.Rmd. Please edit that file -->

## DoSStoolkit <img src="man/figures/stitches_hex_all.png" align="right" height="200" />

The DoSS Toolkit is a bunch of self-paced modules to help you learn and
use R.

We all know that R is a critical part of applied statistics and data
science these days, but it can have a steep learning curve and be
intimidating to get started with.

The [Department of Statistical Sciences](http://www.utstat.utoronto.ca/)
(DoSS) toolkit is a free series of open source online modules written by
undergraduates, that their fellow students and the public can use to
learn the essentials of R.

## How to use this resource

### If you have never used R before

You use this resource by running R code! This may sound intimidating if
you’ve never used R before, so we’ve made a video that walks through
what you need to do.

<iframe width="560" height="315" src="https://www.youtube.com/embed/7mymJEEXux4?start=3" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
</iframe>

Get started by going to R Studio Cloud - <https://rstudio.cloud> - and
creating an account. When you’ve signed up, start a new project, and
copy-paste the code below to install packages. (If you already have R
and R Studio working on your local computer then you don’t have to use R
Studio Cloud, you can install the packages on your local machine
instead.)

``` r
install.packages('tidyverse')
install.packages('remotes')
install.packages('opendatatoronto')
remotes::install_github("rstudio-education/gradethis")
```

Then you can install the `DoSStoolkit`:

``` r
remotes::install_github("RohanAlexander/DoSStoolkit")
```

You’ll use the function `run_tutorial` to run each module. At the moment
we have nine modules. So you can pick one to start with. For instance,
if you wanted to run the ‘hello world’ module then run:

``` r
learnr::run_tutorial("hello_world", package = "DoSStoolkit")
```

### If you already have R and R Studio on your computer

You can install `DoSStoolkit` from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("RohanAlexander/heapsofpapers")

# install.packages('tidyverse')
# install.packages('remotes')
# install.packages('opendatatoronto')
remotes::install_github("rstudio-education/gradethis")
```

Then you can install the `DoSStoolkit`:

``` r
remotes::install_github("RohanAlexander/DoSStoolkit")
```

You’ll use the function `run_tutorial` to run each module. At the moment
we have ten modules. So you can pick one to start with. For instance, if
you wanted to run the ‘hello world’ module then run:

``` r
learnr::run_tutorial("hello_world", package = "DoSStoolkit")
```

## Content

We have ten modules. A complete collection is here:

``` r
learnr::run_tutorial("hello_world", package = "DoSStoolkit")
learnr::run_tutorial("holding_the_chaos_at_bay", package = "DoSStoolkit")
learnr::run_tutorial("operating_in_an_error_prone_world", package = "DoSStoolkit")
learnr::run_tutorial("hand_me_my_plyrs", package = "DoSStoolkit")
learnr::run_tutorial("totally_addicted_to_base", package = "DoSStoolkit")
learnr::run_tutorial("he_was_a_d8er_boi", package = "DoSStoolkit")
learnr::run_tutorial("to_ggplot_or_not_to_ggplot", package = "DoSStoolkit")
learnr::run_tutorial("r_marky_markdown", package = "DoSStoolkit")
learnr::run_tutorial("git_outta_here", package = "DoSStoolkit")
learnr::run_tutorial("indistinguishable_from_magic", package = "DoSStoolkit")
```

### Hello world!

How to run this module:

``` r
learnr::run_tutorial("hello_world", package = "DoSStoolkit")
```

Module content:

-   Why I love R, by Liza Bolton.
-   Setting up RStudio, by Annie Collins.
-   Getting to know what is what - console, terminal, etc, by Annie
    Collins.
-   A fun hello world exercise, by Annie Collins.
-   Another fun hello world exercise, by Shirley Deng.
-   R Weekly newsletter, R Ladies, R meetups, by Annie Collins.

### Operating in an error prone world

How to run this module:

``` r
learnr::run_tutorial("holding_the_chaos_at_bay", package = "DoSStoolkit")
```

Module content:

-   Why I love R, by Monica Alexander.
-   Getting help is normal, by Michael Chong.
-   Using Google and Stack Overflow, by Michael Chong.
-   Stack overflow, by Annie Collins.
-   How to problem solve when your code doesn’t work, by Michael Chong.
-   How to ask for help, by Michael Chong.
-   Making reproducible examples, by Marija Pejcinovska.
-   How to make the most of R’s cryptic error messages, by Shirley Deng.

### Holding the chaos at bay

How to run this module:

``` r
learnr::run_tutorial("operating_in_an_error_prone_world", package = "DoSStoolkit")
```

Module content:

-   Why I love R, by Samantha-Jo Caetano.
-   R projects (and setwd() and why you should not use it), by Isaac
    Ehrlich.
-   Folder set up, by Isaac Ehrlich.
-   Writing comments, by Isaac Ehrlich.
-   Installing packages from CRAN, by Haoluan Chen.
-   Installing packages from GitHub, by Haoluan Chen.
-   Calling libraries, by Mariam Walaa.
-   Updating libraries, by Mariam Walaa.
-   read\_csv(), by Marija Pejcinovska.
-   Other file types: read.table(), read\_excel(), haven and
    read\_dta(), read\_rds(), load() with .Rda files, anything else
    useful in readr?, by Isaac Ehrlich.

### Hand me my plyrs

How to run this module:

``` r
learnr::run_tutorial("hand_me_my_plyrs", package = "DoSStoolkit")
```

Module content:

-   Why I love R, by Sabrina Sixta.
-   What is the tidyverse?, by Yena Joo.
-   The pipe, by Mariam Walaa.
-   select(), by Yena Joo.
-   filter(), by Shirley Deng.
-   group\_by() / ungroup(), by Matthew Wankiewicz.
-   summarise(), by Mariam Walaa.
-   arrange(), by Isaac Ehrlich.
-   mutate(), by Haoluan Chen.
-   pivot\_wider() / pivot\_longer(), by Annie Collins.
-   rename(), by Mariam Walaa.
-   count() and uncount(), by Annie Collins.
-   slice(), by Annie Collins.
-   class() and basics of data types - character, numeric, dates,
    logical, by Michael Chong.
-   vectors, matrices, dataframes, and tibbles, by Matthew Wankiewicz.
-   length(), nrow(), and ncol(), by Isaac Ehrlich.

### Totally addicted to base

How to run this module:

``` r
learnr::run_tutorial("totally_addicted_to_base", package = "DoSStoolkit")
```

Module content:

-   Why I love R, by Rohan Alexander.
-   mean(), median(), sd(), lm(), and summary(), by Mariam Walaa.
-   functions, by Haoluan Chen.
-   for and while, by Yena Joo.
-   if, if\_else() and case\_when(), by Haoluan Chen.
-   c(), seq(), seq\_along() and rep(), by Matthew Wankiewicz.
-   hist() and the other base graphing options including exporting base
    graphs, by Yena Joo.

### He was a d8er boi

How to run this module:

``` r
learnr::run_tutorial("he_was_a_d8er_boi", package = "DoSStoolkit")
```

Module content:

-   An overview of R and data and head(), tail(), glance() and
    summary(), by Haoluan Chen.
-   strings: paste() and glue() and stringr generally but especially
    str\_detect() and str\_remove() etc, by Marija Pejcinovska.
-   names(), cbind(), and rbind(), by Isaac Ehrlich.
-   left\_join(), anti\_join(), full\_join, distinct() and duplicated(),
    by Haoluan Chen.
-   Looking for missing data, such as complete() and other ways, by
    Mariam Walaa.
-   set.seed(), runif(), rnorm(), and sample(), by Haoluan Chen.
-   Putting them together to simulate regression datasets for common
    scenarios, by Mariam Walaa.
-   across() and conditional mutating and conditional summarise etc, by
    Mariam Walaa.
-   tidying up datasets including recode(), replace\_na(), coalesce(),
    n\_distinct(), distinct(), fill(), lag() and lead(), by Mariam
    Walaa.
-   pluck(), unnest(), pull(), by Isaac Ehrlich.
-   forcats and factors espectially relevel() and fct\_reorder(), by
    Matthew Wankiewicz.
-   strings especially separate(), separate\_rows(), text, str\_match(),
    str\_remove(), str\_detect() (Check what is covered in the earlier
    module that gets started with strings (\#43) and mention that also,
    by Annie Collins.
-   regular expressions, by Shirley Deng.
-   dates, especially lubridate, by Mariam Walaa.
-   janitor, especially clean\_names(), by Mariam Walaa.
-   tidyr - TBD -
    <https://github.com/rstudio/cheatsheets/blob/master/data-import.pdf>
    See if there’s anythign that should be added, by Mariam Walaa.

### To ggplot or not to ggplot

How to run this module:

``` r
learnr::run_tutorial("to_ggplot_or_not_to_ggplot", package = "DoSStoolkit")
```

Module content:

-   What is ggplot, aes, etc, by Shirley Deng.
-   Bar charts (one categorical variable), by Matthew Wankiewicz.
-   Histograms (one continuous variable), by Haoluan Chen.
-   Scatter plots (two variables), by Haoluan Chen.
-   Static maps with ggmap, by Annie Collins.
-   Various useful options including: facets, labels, and colours,
    breaks\_pretty(), other?, by Yena Joo.
-   Saving graphs in a ggplot world and changing their size and other
    options, by Yena Joo.

### R Marky Markdown and the Funky Docs

How to run this module:

``` r
learnr::run_tutorial("r_marky_markdown", package = "DoSStoolkit")
```

Module content:

-   What is R Markdown and why might you use it, Sections, sub-section,
    etc, bold, italics, maths, by Shirley Deng.
-   Figures and cross-references, by Isaac Ehrlich.
-   Top matter: title, date, author, abstract, by Yena Joo.
-   Tables, kable, kableextra and gt, by Yena Joo.
-   Formatting regression results - modelsummary(), stargazer(),
    others????, by Isaac Ehrlich.
-   Patchwork, by Michael Chong.
-   References and bibtex, by Yena Joo.
-   PDF outputs, by Yena Joo.
-   here and filepaths, by Matthew Wankiewicz.

### Git outta here

How to run this module:

``` r
learnr::run_tutorial("git_outta_here", package = "DoSStoolkit")
```

Module content:

-   What is version control and GitHub?, by Mariam Walaa.
-   Pull, status, add, commit, push, by Mariam Walaa.
-   Branches, by Matthew Wankiewicz.
-   Dealing with conflicts, by Matthew Wankiewicz.
-   Doing all this in R Studio, by Matthew Wankiewicz.

### Indistinguishable from magic

How to run this module:

``` r
learnr::run_tutorial("indistinguishable_from_magic", package = "DoSStoolkit")
```

Module content:

-   Iterating on iteration, by Michael Chong.
-   Coding style, by Marija Pejcinovska.
-   Writing R packages, by Matthew Wankiewicz.
-   Getting started with Blogdown, by Annie Collins.
-   Getting started with Shiny, by Matthew Wankiewicz.
-   Installing Stan and related adventures, by Marija Pejcinovska.

## Contributors

-   Annie Collins is an undergraduate student in the Department of
    Mathematics specializing in applied mathematics and statistics with
    a minor in history and philosophy of science. In her free time, she
    focuses her efforts on student governance, promoting women’s
    representation in STEM, and working with data in the non-profit and
    charitable sector.
-   Haoluan Chen is an undergraduate student in the Department of
    Statistical Science specializing in applied statistics. He is
    interested in applying data science techniques, especially in NLP,
    to gain insight from the data.
-   Isaac Ehrlich is an undergraduate student in Statistics and
    Cognitive Science at the University of Toronto. He enjoys using R
    for everything from analysing trends in his recent movie-viewing
    history, to his past research building models on human
    categorization.
-   Mariam Walaa is an undergraduate student in the Department of
    Computer and Mathematical Sciences at University of Toronto
    Scarborough, majoring in Mathematics and minoring in GIS and
    statistics. Mariam enjoys learning about how to work with data such
    as spatial and text data to extract insights.
-   Marija Pejcinovska is a graduate student in the Department of
    Statistical Sciences. Her research is motivated by modelling
    challenges that arise with “complicated” data (sparse/highly
    biased/poor quality data), usually in the context of social or
    health inequalities.
-   Matthew Wankiewicz is an undergraduate student at the University of
    Toronto, majoring in Statistics and minoring in Mathematics and the
    History and Philosophy of Science.
-   Michael Chong is a graduate student in the Department of Statistical
    Sciences. His research aims to build statistical models for
    demographic estimation in contexts where high quality data are
    unavailable. There is almost always an active R session on his
    computer!
-   Paul Hodgetts is a Master of Information candidate concentrating in
    Human-Centred Data Science in the Faculty of Information, University
    of Toronto. He sincerely believes that Calvin and Hobbes is the
    greatest comic ever produced.
-   Rohan Alexander is an assistant professor in the Faculty of
    Information and the Department of Statistical Sciences. Some people
    convert to catholicism upon marriage, Rohan converted to R. His
    greatest professional achievement is probably getting a pull request
    accepted into R for Data Science (it was just fixing a minor typo
    but still).
-   Samantha-Jo Caetano is an assistant professor (teaching stream) in
    the Department of Statistical Sciences. She loves statistics,
    socializing, her family, and her dogs, not necessarily in that
    order.
-   Shirley Deng - Shirley is an undergraduate student specializing in
    Statistics and majoring in Mathematics. Meticulous and soft-hearted,
    she often finds herself engrossed in new pastimes by the second at
    the influence of her peers. One of which that has remained a
    longtime constant - spending an excessive amount of time helping
    people debug their R code.
-   Yena Joo is an undergraduate student majoring in Economics and
    double minoring in Statistics and Computer Science.

## Pedagogical underpinnings

*Coming soon.*

## Acknowledgements

We gratefully acknowledge the support of Professor Bethany White, Chair
Radu Craiu, and the U of T Faculty of Arts & Sciences Pedagogical
Innovation and Experimentation Fund.

We’d like to acknowledge the help of:

-   Liza Bolton
-   Monica Alexander
-   Sabrina Sixta

We’d like to thank Alex Cookson for his collection of datasets.

This toolkit builds on, and complements, the work of many others,
including:

-   Alex Stringer - <https://github.com/awstringer1/course-materials>
-   Alison Gibbs, Jeff Rosenthal, Nathan Taback -
    <https://stats.onlinelearning.utoronto.ca/>
-   Bethany White and Jennifer Peter - <https://rscidata.utoronto.ca/>
-   Desirée De Leon and Alison Hill -
    <https://rstudio4edu.github.io/rstudio4edu-book/>
-   Hasse Walum and Desirée De Leon -
    <https://tinystats.github.io/teacups-giraffes-and-statistics/index.html>
-   Nathan Taback -
    <https://ntaback.github.io/UofT_STA130/R_resources.html>
-   Radford Neal - <http://www.cs.utoronto.ca/~radford/csc121.S17/>

Rohan would like to thank Greg Wilson, for sharing his experience,
thoughts, and leadership.

## References

We draw on the open-source statistical programming language R and a
variety of packages. We are grateful for the work that we build on.

-   Barret Schloerke, JJ Allaire, Barbara Borges and Garrick Aden-Buie
    (2021). learnr: Interactive Tutorials for R.
    <https://rstudio.github.io/learnr/>,
    <https://github.com/rstudio/learnr>.
-   Bodwin, Kelly, and Hunter Glanz (2020). flair: Highlight, Annotate,
    and Format your R Source Code. R package version 0.0.2.
    <https://CRAN.R-project.org/package=flair>
-   Chen, Daniel, Barret Schloerke, Garrick Aden-Buie and Garrett
    Grolemund (2021). gradethis: Automated Feedback for Student
    Exercises in ‘learnr’ Tutorials.
    <https://rstudio-education.github.io/gradethis/>,
    <https://rstudio.github.io/learnr/>,
    <https://github.com/rstudio-education/gradethis>.
-   de Vries, Andrie, Barret Schloerke and Kenton Russell (2020).
    sortable: Drag-and-Drop in ‘shiny’ Apps with ‘SortableJS’. R package
    version 0.4.4. <https://CRAN.R-project.org/package=sortable>
-   Gelfand, Sharla, (2020). opendatatoronto: Access the City of Toronto
    Open Data Portal. R package version 0.1.4.
    <https://CRAN.R-project.org/package=opendatatoronto>
-   Hester, Jim, Gábor Csárdi, Hadley Wickham, Winston Chang, Martin
    Morgan and Dan Tenenbaum (2020). remotes: R Package Installation
    from Remote Repositories, Including ‘GitHub’. R package version
    2.2.0. <https://CRAN.R-project.org/package=remotes>
-   R Core Team (2020). R: A language and environment for statistical
    computing. R Foundation for Statistical Computing, Vienna, Austria.
    URL <https://www.R-project.org/>.
-   Wickham et al., (2019). Welcome to the tidyverse. Journal of Open
    Source Software, 4(43), 1686, <https://doi.org/10.21105/joss.01686>

## Related packages

-   TBD

## Next steps

-   Assessment
-   Modules
    -   Iteration
    -   Data II
    -   Strings
    -   Dates
    -   Stan
    -   Packages
    -   Shiny
    -   Teaching
-   French language version

# Citation

We have a pre-print coming soon.

## How to contribute

The best way to contribute fixes and minor typos is to make a pull
request on GitHub.

If you are interested in contributing lessons or modules, then please
contact Rohan Alexander. We are particularly interested in partnering
with an institution where the language of instruction is French to
develop a French language version.

## Contact

Please contact Rohan (<rohan.alexander@utoronto.ca>) with any questions,
comments, and suggestions.
