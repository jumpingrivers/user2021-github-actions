# Continuous Integration with GitHub Actions for Data Scientists

useR! 2021

by Rhian Davies & Colin Gillespie

-----

:spiral_calendar: TBC
:alarm_clock: TBC

-----

## Overview

After you’ve created your first package and put it on GitHub, the next step to the journey is to implement Continuous Integration (CI). Over the last few years, GitHub Actions has emerged as the preferred form of CI within the R community. The key idea is that a single commit can automatically launch a variety of other services. This can lead to massive savings in time, as well as reducing bugs.
This tutorial will start by using “off-the-shelf” actions provided by {usethis}. We’ll then move on to extending and customising these actions. The idea is for participants to complete the course with the practical skills to immediately implement the techniques, combined with a deeper understanding of the topic.

## Learning Objectives

At the end of the workshop, attendees will have learnt:

* What GitHub Actions and continuous integration are
* How to use “off-the-shelf" GitHub Actions via {usethis}
* Hot to check packages, code style and generate package websites with GitHub Actions
* How to customise GitHub Actions

## Is this course for me?

This course will be appropriate for you if you answer yes to these questions:

1. Have you created a simple R package before?
2. Are you comfortable with basic git commands?
3. Would you like to learn how to automate package checks and documentation using GitHub Actions?

## Prework

Attendees are expected to use the provided training environment, and therefore there is no pre-work.

If you wish to use your own set up, please install the following packages.

```r
install.packages(c("lintr", "testthat","usethis"))
```



## Example Schedule

| Time          |          | Activity                                                    |
| :------------ | -------- | :---------------------------------------------------------- |
| 14:00 - 14:50 | :package:        | Getting started with GitHub Actions |
| 14:50 - 15:05 | :coffee: | *Break*                                                     |
| 15:05 - 15:55 |    :sparkles:      | Fancy Actions with {pkgdown} websites, {lintr} and {testthat} |
| 15:55 - 16:10 | :coffee: | *Break*                                                     |
| 16:50 - 17:00 |      :nail_care:	    | Customising GitHub Actions                                  |

## Instructors

### Dr Rhian Davies

Rhian loves using statistics to help people make data driven decisions.
As a data scientist, she has worked closely with varied domain experts
including physicists, psychologists, game designers and engineers.

### Dr Colin Gillespie

Colin has been using R since 1999 and is the co-founder of [Jumping
Rivers](https://www.jumpingrivers.com). He’s the author of a number of R
packages and has published the book Efficient R Programming with
O’Reilly. As well as working in industry, Colin is also a part-time
Senior Statistics lecturer at Newcastle University.

[Code of conduct](https://user2021.r-project.org/participation/coc/)

