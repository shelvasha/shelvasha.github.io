---
layout: post
title: RepBox
description: A bioinformatics pipeline for the identification and analysis of novel repeats.
img:
---

<img class="col" src="/img/image.jpg">

<!-- View on Github Button -->
<a href="https://github.com/shelvasha/RepBox" style=
" border-radius: 25px;
  background-color: #6cc644;
  border: none;
  color: white;
  padding: 10px 30px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;">View on Github
</a>

A bioinformatics pipeline that identifies and analyzes novel repeats. This pipeline uses updated software packages specific in identifying classes and families of repeats as well as traditional repeat identification and masking tools RepeatModeler and RepeatMasker.

### Dependencies
- Perl v5.30.2
- Python 3.0+
- Homebrew/Linuxbrew
- Other (Installed by install.sh):
  - RepeatModeler v2.0.1
    - NINJA v0.95
    - BLAST v2.10+
    - LTR_retriever v2.8.5
  - RepeatMasker v4.10
  - CD-Hit v4.6
  - HelitronScanner v1.1
  - MITEFinder v1.0.006
  - SINE_Scan v1.1.1
  - VSEARCH v2.14.1
  - Other RepeatModeler dependencies (Located in /bin directory)

### Installation
RepBox uses bash script to install dependencies and requires super-user permissions for the installation of some Perl and Python modules.


### Usage
RepBox is simple to run, however it is suggested to place the Github download in your home directory. After installation of all dependencies, simply place your genome of interest in the /genome subdirectory in the main directory of RepBox. The pipeline accepts various extensions representing a fasta file (.fa, .fasta, .fna, .fas).


### Runtime
Due to the dependence of RepBox on RepeatModeler, it can take some time to properly analyze any provided genome. We are hoping to implement multi-threading in the future, but in the meantime, it is suggested that analysis be performed on a high-performance cluster.
