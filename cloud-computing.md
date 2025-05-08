---
title: "Cloud Computing and Open/Reproducible Research"
teaching: 45
exercises: 2
---

:::::::::::::::::::::::::::::::::::::: questions 

- FIXME
- How do you write a lesson using Markdown and `{sandpaper}`?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Explain the concept of cloud computing
- Describe three benefits of cloud computing in open and reproducible research
- Identify cloud computing providers within and beyond your institution
- List at least three parameters that one may need to choose when creating an instance of a cloud computer
- Identify resources typically needed to utilize cloud computing
- Identify advantages and disadvantages of cloud computing versus local computing when presented with various researcher scenarios

::::::::::::::::::::::::::::::::::::::::::::::::

## Introduction

The majority of our researchers, outside of a few specialized fields, usually have a laptop that they use for most of their work.
When they need to work with a data set, they typically download it to their laptop and use 
some sort of data analysis software on their laptop to conduct their analysis.



:::::::::::::::::::::::::::::::::::::::  challenge

## Discussion

With the person next to you, discuss:

If a researcher came to you for advice on the following questions, what advice would you give?

- "I need to analyze a data set that is too large to fit on my laptop.  What should I do?"
- "My analysis needs to run for many hours and I can't keep my laptop on for that whole time."
- "My analysis would take many days or weeks to run on my laptop"
- "The tools I need to use for my analysis need to run in a Linux environment, but I only have a Windows or Mac laptop."

:::::::::::::::  solution

## Solution

Some common answers might be:

- "I need to analyze a data set that is too large to fit on my laptop.  What should I do?"
   - Break the data up and analyze it in parts
   - Use a cloud computing provider (e.g. AWS, Google Cloud, Azure)
- "My analysis needs to run for many hours and I can't keep my laptop on for that whole time."
   - Use a cloud computing provider (e.g. AWS, Google Cloud, Azure)
- "My analysis would take many days or weeks to run on my laptop"
   - Use a cloud computing provider (e.g. AWS, Google Cloud, Azure)
- "The tools I need to use for my analysis need to run in a Linux environment, but I only have a Windows or Mac laptop."
   - Try using a virtualized environment on your laptop
   - Use a cloud computing provider (e.g. AWS, Google Cloud, Azure)

  
:::::::::::::::::::::::::

## What is cloud computing?

Cloud computing is a pivotal technology for researchers, offering
unparalleled access to vast computing resources and data storage
capabilities via the internet. For academic librarians assisting
researchers, understanding cloud computing is crucial as it enables
the efficient handling of large datasets, complex computations, and
collaborative projects. Researchers can leverage cloud services to
perform high-performance computing tasks, run sophisticated simulations,
and analyze extensive data sets without the need for substantial local
infrastructure. This technology also facilitates seamless collaboration
across institutions and geographical boundaries, fostering a more
integrated and dynamic research environment. By utilizing cloud computing,
researchers can accelerate their work, reduce costs, and enhance the
reproducibility and scalability of their studies.
This makes cloud computing an indispensable tool in advancing scientific
discovery and innovation.

::::::::::::::::::::::::::::::::::::::::::::::::::

Next: Questions about reproducibility



This is a lesson created via The Carpentries Workbench. It is written in
[Pandoc-flavored Markdown](https://pandoc.org/MANUAL.txt) for static files and
[R Markdown][r-markdown] for dynamic files that can render code into output. 
Please refer to the [Introduction to The Carpentries 
Workbench](https://carpentries.github.io/sandpaper-docs/) for full documentation.

What you need to know is that there are three sections required for a valid
Carpentries lesson:

 1. `questions` are displayed at the beginning of the episode to prime the
    learner for the content.
 2. `objectives` are the learning objectives for an episode displayed with
    the questions.
 3. `keypoints` are displayed at the end of the episode to reinforce the
    objectives.

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: instructor

Inline instructor notes can help inform instructors of timing challenges
associated with the lessons. They appear in the "Instructor View"

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: challenge 

## Challenge 1: Can you do it?

What is the output of this command?

```r
paste("This", "new", "lesson", "looks", "good")
```

:::::::::::::::::::::::: solution 

## Output
 
```output
[1] "This new lesson looks good"
```

:::::::::::::::::::::::::::::::::


## Challenge 2: how do you nest solutions within challenge blocks?

:::::::::::::::::::::::: solution 

You can add a line with at least three colons and a `solution` tag.

:::::::::::::::::::::::::::::::::
::::::::::::::::::::::::::::::::::::::::::::::::

## Figures

You can use standard markdown for static figures with the following syntax:

`![optional caption that appears below the figure](figure url){alt='alt text for
accessibility purposes'}`

![You belong in The Carpentries!](https://raw.githubusercontent.com/carpentries/logo/master/Badge_Carpentries.svg){alt='Blue Carpentries hex person logo with no text.'}

::::::::::::::::::::::::::::::::::::: callout

Callout sections can highlight information.

They are sometimes used to emphasise particularly important points
but are also used in some lessons to present "asides": 
content that is not central to the narrative of the lesson,
e.g. by providing the answer to a commonly-asked question.

::::::::::::::::::::::::::::::::::::::::::::::::


## Math

One of our episodes contains $\LaTeX$ equations when describing how to create
dynamic reports with {knitr}, so we now use mathjax to describe this:

`$\alpha = \dfrac{1}{(1 - \beta)^2}$` becomes: $\alpha = \dfrac{1}{(1 - \beta)^2}$

Cool, right?

::::::::::::::::::::::::::::::::::::: keypoints 

- Use `.md` files for episodes when you want static content
- Use `.Rmd` files for episodes when you need to generate output
- Run `sandpaper::check_lesson()` to identify any issues with your lesson
- Run `sandpaper::build_lesson()` to preview your lesson locally

::::::::::::::::::::::::::::::::::::::::::::::::

[r-markdown]: https://rmarkdown.rstudio.com/
