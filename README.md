# Climate Module

<!-- EDIT with your badge link -->
[![Reproducibility Check](https://github.com/jiyuaa/climate-change/actions/workflows/main.yml/badge.svg)](https://github.com/jiyuaa/climate-change/actions/workflows/main.yml)

## Team Members

🦸 Trang Ly <lytrang@berkeley.edu>
🦹 Jiyun Ahn <jiyuna@berkeley.edu>

## 🎓 Learning Objectives

:octocat: Use of GitHub  
:snake: Use of Jupyter Notebooks  
:abcd: Accessing tabular data  
📈 Data visualization  
🔍 Verifying code you did not write  
🗄 Working with data larger than memory  
🌡️ Become familiar with data on global climate change  

## 📖 Content Overview
 ## Key Finding and Core Narrtive 
### 1. Is Arctic sea ice actually declining and by how much? 
** Yes, Arctic sea ice is clearlier declining. The data in task 2.3 shows that September Minium is declining at  −0.76 M km² per decade (or −0.076 M km²/yr) over the 1979–2025 record.The annual mean is declining at 

### 2. Does the answer change depending on whether we use the September minimum or annual mean? 

### 3. Is the rate of Arctic sea-loss changing as CO2 accumulates or is it s steady loss rate? 

This repository contains the climate module notebook, `climate.ipynb`, covering the
first two parts of the module:

[💻 Assignment template](climate.ipynb)  
[💯 Assignment rubric](rubric.md)  
[📊 Session 2 benchmarking exercise](benchmark.md)   

1. **Part 1 — The code you didn't write.** Load the Mauna Loa monthly CO₂ record and
   verify the parser against the raw header: column names, negative missing-value
   sentinels, prose caveats, alternative data formats, and an `ibis` load.
2. **Part 2 — Arctic sea ice.** Build the complete NSIDC G02135 record from all 12
   monthly files and defend using the September minimum vs. the annual mean.

Each part ends with a verification block (extent, missing data, units, completeness,
cross-check). Parts 3–5 are not part of this submission.

As a team we will work through and adpat the questions presented in the climate notebook to reproduce key indicators of climate change. This module teaches you to answer the question scientists have always had to ask about code they did not write: *how do I know these numbers are right?* We work through the first two parts — Mauna Loa CO₂ and Arctic sea ice — where a language model writes parsing code that runs cleanly but is wrong in specific, recurring ways.
Finding those mistakes is the assignment.

A second thread runs through the module. You have a language model that will write the
parsing code for you, and it is good at it. It is also wrong in specific, recurring ways
that produce code which runs cleanly and gives the wrong answer. Each part of the notebook
pairs a climate data set with one of those failure modes. The notebook does not tell you
which; finding out is the assignment. The recurring question is the one scientists have
always had to answer about code they did not write:

We will be able to answer : Is Arctic sea ice actually declining, and by how much? And does the answer change depending on whether we use the September minimum or annual mean? 

*Is the rate of Arctic sea-ice loss changing as CO₂ accumulates, or is it steady?* 

Yes the Artctic September sea ice extent has declined 
> How do I know these numbers are right?

Every previous advance that made computing dramatically easier — screens over punchcards,
compilers over assembly, Python over C — led to more programming by more people, not less.
Efficiency gets spent on attempting more. That is why this module does not ask you to
memorize library syntax, and equally why it cannot be completed by pasting the assignment
into a model and typing "go". The work moves up a level rather than disappearing.

We work in plan mode throughout this module: you review and approve what the model
proposes before it runs.

## Data sources

- NOAA Mauna Loa CO2 record — <https://gml.noaa.gov/webdata/ccgg/trends/co2/co2_mm_mlo.txt>
- NSIDC Arctic sea ice extent (G02135) — <https://nsidc.org/data/G02135>


## Setup

Environment setup, GitHub authentication, and language model configuration are covered on
the [course website](https://espm-157.carlboettiger.info/) rather than here, since those
mechanics are shared across all four modules and change faster than the assignments do.

We use GitHub Actions to run automated reproducibility checks — click the badge up top for
details.

## Links

[🌐 Course Website](https://espm-157.carlboettiger.info/)
