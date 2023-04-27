---
title: HeaDS courses
summary: List of courses that the HeaDS DataLab provides
date: 2023-04-28
hide:
  - navigation
  - toc
---

<!--
# Put above to hide navigation (left), toc (right) or footer (bottom)

hide:
  - navigation 
  - toc
  - footer 

# You should hide the navigation if there are no subsections
# You should hide the Table of Contents if there are no important titles
-->

<center>
# Center for Health Data Science Courses
</center>

**Updated:** 2023-04-28

[cards cols="3"(./develop/cards/cards.yaml)]

[HeaDS DataLab](https://heads.ku.dk/datalab/) provides several courses on Data Analysis such as introductions to R and python, git and github and related topics. 

!!! info "Courses calendar"

    Check the event calendar at our [official webpage](https://heads.ku.dk/course/next-courses/)   

In addition, the Danish National Sanbox for Health Data Science, ([HDS sandbox](https://hds-sandbox.github.io/)), also offers courses on omics analysis.

## DataLab Course list

### Introduction to Machine Learning in Biomedical Research

[Github link](https://github.com/Center-for-Health-Data-Science/IntroToML)

An introductory course on Machine Learning for Biomedical Research at the Faculty of Health Science by the Center for Health and Data Science.

### From Excel to R

[Github link](https://github.com/Center-for-Health-Data-Science/FromExceltoR)

The course From Excel to R is intended for users with no, or very limited, experience in the statistical programming language R. Participants will learn how to use R and R-studio to open and load in datafiles, how to manipulate data into different structures, and how to quickly visualize datasets within the R-environment. The course will mainly focus on the tidyverse/dplyr framework and ggplot2. The course provides participants with a set of fundamental R-skills, which they may utilize in the analysis of their clinical/biological datasets.

### Python Tsunami: Introduction to Programming in Python

[Github link](https://github.com/Center-for-Health-Data-Science/PythonTsunami)

[Course webpage](https://center-for-health-data-science.github.io/PythonTsunami/)

The course Python Tsunami is an 3-day introductory course to programming in the language Python. It is intended for researchers at SUND who are interested in learning how to use Python but who do not have any prior experience yet.

We will demonstrate how to run Python from Jupyter Notebooks hosted on google colab, a tool that is often used for data analysis. An overview of the fundamental Pythonic data structures will follow and participants will learn about containers, conditional statements and loops. Moreover, the course will introduce the Python library pandas that allows for efficient data manipulation. Lastly, we will give a first introduction to data visualization in Python.

### Git and Github

[Github link](https://github.com/Center-for-Health-Data-Science/git-GitHub-workshop)

This introductory workshop is intended for researchers at SUND who are interested in learning how to share their code (R, Python, or other) and reports (R Markdown or Jupyter Notebook) with group members or external collaborators as well as editing, improving, and maintaining scripts with multiple contributors. 

The one-day workshop will introduce you to the basic git language (pull, stage, commit, and push), using the command line as well as the graphical interface GitHub. Participants will learn about version control, branching, and resolving conflicts in git and, more generally, how to efficiently collaborate on this platform. The workshop will include a hands-on exercises in which participants can try out their newly acquired knowledge.

The introductory workshop is free for all researchers at SUND, including PhD students, who have no (or only very little) experience in working with git and GitHub. There is also a smaller number of free course seats available to SCIENCE employees. 

### Computerome 2.0 Users

[Github link](https://github.com/Center-for-Health-Data-Science/Computerome2.0Workshop)

The introductory workshop is intended for new users of the Computerome 2.0 platform. Participants will get an introduction to the architecture of Computerome 2.0, we will go through several fundamental concepts, such as nodes (CPUs/GPUs), parallelized computation (multithreading), etc. and we will discuss what kind of projects the supercomputer is especially useful for.

Next, we will go through the basics of logging in, the structure of directories and projects, finding and loading modules, and running jobs interactively with iqsub.

In the afternoon participants will get acquainted with how to set up a script for large computations submitted with iqsub. Importantly, we will discuss the cost of storage, computational resources, and wall times, and how to optimize these.

The one-day workshop is targeted at researchers with some computational background (e.g. basic command line skills) who need to work with large datasets (mapping or assembly of sequencing data) or perform heavy computations (neural networks, molecular dynamics simulations).

### Data Protection and GDPR for Biomedical Researcher
The course is specifically developed for upper and middle-level researchers wishing to use Danish Health and Genome data. You will learn about the implications of data protection legislation throughout the research life cycle. The focus of the workshop is health and genomic data research (within the EU). Particularly secondary research on already existing data (registries, health records, genomic data from research, and clinical biobanks).

The workshop is organized as a series of lectures presented by experts on specific topics and practical exercises on relevant cases.

### Just Bash It

[Github link](https://github.com/Center-for-Health-Data-Science/Just-Bash-It)

Knowledge on how to use a terminal command line is an essential skill, not just for data scientists, but for any biomedical researcher who needs to work with large datasets, including registry data, clinical datasets and high-throughput biological data. In combination with the basics of bash, mastering the command line will allow you to wrangle large datasets and run command line softwares for data analysis, including those for sequence alignment, gene annotation, SNP & CNV calling, web-scraping, protein structure analysis, and much much more.

This workshop contains a basic tutorial on how to use the shell and command line to manage files and develop useful scripts.

## NHDS sandbox courses

See a list of all courses [here](https://hds-sandbox.github.io/modules/index.html). 

### Introduction to bulk RNAseq analysis 

[Github link](https://hds-sandbox.github.io/bulk_RNAseq_course/)

Tutorial on how to approach RNAseq data, starting from your sequencing reads (fastq files). Thus, the workshop only briefly touches upon laboratory protocols, library preparation, and experimental design of RNA sequencing experiments, mainly for the purpose of outlining considerations in the downstream bioinformatic analysis.

### Introduction to single cell RNAseq analysis

[Github link](https://hds-sandbox.github.io/scRNASeq_course/)

This course is organized as the analysis project of a dataset with cells from human testis representing the spermatogenesis process. We will also make a comparative analysis against a dataset from a person affected by azoospermia (missing or faulty production of spermatozoa). You will learn to use the tools for integrating and analyzing multiple datasets in both python and R with the use of interactive coding on Rstudio or Jupyter Notebooks.

### Introduction to NGS data

[Github link](https://hds-sandbox.github.io/NGS_summer_course_Aarhus/)

This course is based on the material developed for the NGS summer school at Aarhus University. The material is organized in four separated jupyter notebooks in both bash, python and R where you will benefit of an interactive coding setup.

### Proteomics UCloud app

[Github link](https://hds-sandbox.github.io/NGS_summer_course_Aarhus/)https://hds-sandbox.github.io/proteomics-course/index.html)

Discover the world of proteomics with the Clinical Proteomics module of the Sandbox, offering the Proteomics Sandbox app on UCloud - an accessible resource for biomedical students and non-computational researchers. With a user-friendly interface and a lightweight clone feature, the app is perfect for those without extensive coding knowledge, providing a stable platform for proteomics software tools. You can also learn to predict protein structures based on sequence data with the independent ColabFold workshop, available on UCloud. This hands-on experience offers insights into the exciting field of proteomics analysis and is accessible for all UCloud-users.

