# stat679selfassessment


This repository contains the `learnr` self-assessment for STAT679-III: Spatial Statistics for Lattice Data.

It is intended to be used as a review guide for students prior to the course.

## How to use this self-assessment

1) You can install the github version using the following:

```
install.packages("remotes")
remotes::install_github("mkamenet3/stat679selfassessment")
```

To run the self-assessment on your computer:

```
library(stat679selfassessment)
learnr::run_tutorial("selfassessment", package = "stat679selfassessment")

```

The self-assessment will open up in a new window.

2) You can also run the self-assessment using mybinder.org:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mkamenet3/stat679selfassessment/main?urlpath=shiny/selfassessment/)

Once you click on the link, you will be taken to a new window where the self-assessment will be built. *This may take several minutes (up to 15 minutes) the first time you load it*. It should go faster the second time.

### Goals of the self-assessment

The goal of this self-assessment is to help students refresh on some basic `R` skills and statistics terminology and concepts. Answers can be resubmitted as many times as you like. Both correct and incorrect answers have **helpful links and resources** for additional readings. This self-assessment is for students to help themselves. No instructor nor TA receive any answers answers.

### Feedback

Feedback on the self-assessment is welcome! If you found this helpful or have suggestions, please let me know either in the [issues](https://github.com/mkamenet3/stat679selfassessment/issues) or via [email](mkamenetsky@wisc.edu).
