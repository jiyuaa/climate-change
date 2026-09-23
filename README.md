# Climate Module

!-- EDIT with your badge link --
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

This repository contains the climate module notebook, `climate.ipynb`, covering the
first two parts of the module:

[💻 Assignment template](climate.ipynb)  
[💯 Assignment rubric](rubric.md)  
[📊 Session 2 benchmarking exercise](benchmark.md)   

1. **Part 1 — Long-term Atmospheric CO₂ Trends at Mauna Loa .** Load the Mauna Loa monthly CO₂ record and
   verify the parser against the raw header: column names, negative missing-value
   sentinels, prose caveats, alternative data formats, and an `ibis` load.

2. **Part 2 —Arctic Sea Ice Loss Across Multiple Months.** Build the complete NSIDC G02135 record from all 12
   monthly files and defend using the September minimum vs. the annual mean.

Each part ends with a verification block (extent, missing data, units, completeness,
cross-check).

As a team we will work through and adapt the questions given in the climate notebook to reproduce indicators to answer the questions : Is Arctic sea ice actually declining and by how much? Does the answer change depending on whether we use the September minimum or annual mean ?, Is the rate of Arctic sea-loss changing as CO2 accumulates or is it a steady loss rate? This module will allow you to answer these questions. We work through the first two parts - Mauna Loa CO₂ and Arctic sea ice. The language model will write code that runs ; our job is to identify mistakes and errors in this assignment. 


## Key Finding and Core Narrative 
### 1. Is Arctic sea ice actually declining and by how much? 
Yes, Arctic sea ice is clearly declining. The data in task 2.3 shows that September Minium is declining at  −0.76 M km² per decade (or −0.076 M km²/yr) over the 1979–2025 record.The annual mean is declining at −0.51 M km² per decade over full years (1979–2025).I was able to know by using the NSIDC data on Arctic sea ice. 

### 2. Does the answer change depending on whether we use the September minimum or annual mean? 
No, the direction does not depend on the index as both September minimum or annual mean decline. 

### 3. Is the rate of Arctic sea-loss changing as CO2 accumulates or is it a steady loss rate? 
 The model for steady linear fit vs CO2 Accumulation shows a linear trend to caputure the trend. CO2 levels were measured at Mauna Loa rose steadily at 315ppm to 425ppm. 


> How do I know these numbers are right?

I was able to understand if my numbers are right by comparing it to the data and able to double-check my code. One way was to compare the unit consistency that part one the units are ppm ( parts per million) and part 2 million sqaure kilometers. I can also verify the raw text headers like the column name corrections. To make sure the model labels the correct identifying data. 


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
