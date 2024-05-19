---
title: dDocent
summary: 
tags:
- dDocent
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image: 
  caption: This is 1000 simulated ddRAD data loci being assembled across a variety of parameters for each pipeline.
  focal_point: Smart

links:
- icon: book
  icon_pack: fas
  name: Documentation
  url: https://www.dDocent.com
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/jpuritz/dDocent
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---
[![alt text](https://anaconda.org/bioconda/ddocent/badges/downloads.svg)](https://anaconda.org/bioconda/ddocent) 

dDocent is simple bash wrapper to QC, assemble, map, and call SNPs from almost any kind of RAD sequencing. If you have a reference already, dDocent can be used to call SNPs from almost any type of NGS data set. It is designed to run on Linux based machines with large memory capacity and multiple processing cores, and it can be modified for use on HPC. 

## Why use dDocent?
### Accuracy
#### *de novo* assembly

dDocent employs a series of data reduction techniques, aligment based clustering (using CD-hit), and, for PE assembly, a specialized RAD assembly software (rainbow. This combination allows for accurate and effecient de novo assembly.



#### Bayesian, haplotype based, population-aware, genotyping from FreeBayes

FreeBayes is a Bayesian genetic variant detector designed to detect SNPs, INDels (insertions and deletions), and complex events (composite insertion and substitution events) smaller than the length of a short-read sequencing alignment. FreeBayes is haplotype-based, in the sense that it calls variants based on the literal sequences of reads aligned to a particular target, not their precise alignment, and for any number of individuals from a population and a to determine the most-likely combination of genotypes for the population at each position in the reference.
