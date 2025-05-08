---
title: "Cloud Computing and Open/Reproducible Research"
teaching: 45
exercises: 2
editor_options: 
  markdown: 
    wrap: 72
---

:::::::::::::::::::::::::::::::::::::: questions

-   What is cloud computing?
-   What are the reasons researchers might need to use a cloud computer?
-   What cloud computing services might be available to researchers at
    an academic institution?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

-   Explain the concept of cloud computing
-   Describe three benefits of cloud computing in open and reproducible
    research
-   Identify cloud computing providers within and beyond your
    institution
-   List at least three parameters that one may need to choose when
    creating an instance of a cloud computer
-   Identify resources typically needed to utilize cloud computing
-   Identify advantages and disadvantages of cloud computing versus
    local computing when presented with various researcher scenarios

::::::::::::::::::::::::::::::::::::::::::::::::

## Introduction

The majority of our researchers, outside of a few specialized fields,
usually have a laptop that they use for most of their work. When they
need to work with a data set, they typically download it to their laptop
and use some sort of data analysis software on their laptop to conduct
their analysis.

::::::::::::::::::::::::::::::::::::: challenge

## Discussion

With the person next to you, discuss:

If a researcher came to you for advice on the following questions, what
advice would you give?

-   "I need to analyze a data set that is too large to fit on my laptop.
    What should I do?"
-   "My analysis needs to run for many hours and I can't keep my laptop
    on for that whole time."
-   "My analysis would take many days or weeks to run on my laptop"
-   "The tools I need to use for my analysis need to run in a Linux
    environment, but I only have a Windows or Mac laptop."

:::::::::::::::::::::::: solution

## Solution

Some common answers might be:

-   "I need to analyze a data set that is too large to fit on my laptop.
    What should I do?"
    -   Break the data up and analyze it in parts
    -   Use a cloud computing provider (e.g. AWS, Google Cloud, Azure)
-   "My analysis needs to run for many hours and I can't keep my laptop
    on for that whole time."
    -   Use a cloud computing provider (e.g. AWS, Google Cloud, Azure)
-   "My analysis would take many days or weeks to run on my laptop"
    -   Use a cloud computing provider (e.g. AWS, Google Cloud, Azure)
-   "The tools I need to use for my analysis need to run in a Linux
    environment, but I only have a Windows or Mac laptop."
    -   Try using a virtualized environment on your laptop
    -   Use a cloud computing provider (e.g. AWS, Google Cloud, Azure)

:::::::::::::::::::::::::::::::::
::::::::::::::::::::::::::::::::::::::::::::::::

## What is cloud computing?

Cloud computing is a pivotal technology for researchers, offering
unparalleled access to vast computing resources and data storage
capabilities via the internet. For academic librarians assisting
researchers, understanding cloud computing is crucial as it enables the
efficient handling of large datasets, complex computations, and
collaborative projects. Researchers can leverage cloud services to
perform high-performance computing tasks, run sophisticated simulations,
and analyze extensive data sets without the need for substantial local
infrastructure. This technology also facilitates seamless collaboration
across institutions and geographical boundaries, fostering a more
integrated and dynamic research environment. By utilizing cloud
computing, researchers can accelerate their work, reduce costs, and
enhance the reproducibility and scalability of their studies. This makes
cloud computing an indispensable tool in advancing scientific discovery
and innovation.

## Options for cloud computing

-   Institutional infrastructure (for example, institutional cluster
    computing)
-   Public/national research infrastructure (TODO: Examples)
-   Commercial services: Amazon Web Services, Microsoft Azure, Google
    Cloud
-   Discipline-specific commercial services (TODO: Examples)

::::::::::::::::::::::::::::::::::::::: challenge

## Discussion

-   Does your institution have its own cloud and/or cluster computing
    infrastructure?
-   Does your institution provide researchers with access to commercial
    cloud computing resources?
-   How do specific research projects pay for cloud services?
-   As a librarian, is there a cloud/cluster computing environment that
    you can access?

::::::::::::::::::::::::::::::::::::::::::::::::::

## Cloud computing benefits

### How does cloud computing make scientific research easier or faster?

- TODO

### How can cloud computing reduce costs for research?

- Cloud computing often allows you to specify the storage size, processing power, chip type, internet bandwidth etc. that you need.
- If a researcher has a big computation to run, they can control costs by creating a cloud computer instance, running the analysis, and then shutting down the instance.

### How can cloud computing lead to more reproducible research?

Review/define this concept here. Use Turing Way definitions.

![Turing Way reproducibility definitions](fig/reproducibility-turingway.jpg)

### Scalability?

TODO

::::::::::::::::::::::::::::::::::::: keypoints

- Cloud computing can make computational research easier, faster, less expensive, and/or more reproducible.
- Researchers need to use cloud computing when they need more storage space and/or processing power; cloud computing can also enhance reproducibility.
- Many institutions either have their own cloud infrastructure or have arrangements with commercial providers.
An institutional cloud infrastructure costs money to maintain, and commercial services cost money to use.

::::::::::::::::::::::::::::::::::::::::::::::::
