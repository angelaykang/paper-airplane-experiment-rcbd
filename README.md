# Paper Airplane Experiment - RCBD Design

A Randomized Complete Block Design (RCBD) experiment analyzing the effect of paperclip placement on paper airplane flight distance. This project demonstrates principles of experimental design, ANOVA analysis, and statistical hypothesis testing.

## Overview

The aerodynamic performance of paper airplanes depends on weight distribution. This experiment explores how paperclip placement (nose, middle, rear) affects flight distance using a rigorous statistical design:

- **Blocks:** 30 paper airplanes (each tested under all treatments)
- **Treatments:** Control (no paperclip), Nose, Middle, Rear
- **Outcome:** Flight distance (inches)

## Key Findings

- **Middle placement** produced the longest flight distances—balanced weight distribution optimizes stability
- **Rear placement** performed worst—rear-heavy designs destabilize flight
- **Nose placement** showed no significant difference from control

## Project Structure

```
paper-airplane-experiment-rcbd/
├── README.md
├── .gitignore
└── analysis/
    ├── paper_airplane_rcbd.Rmd   # R Markdown analysis
    └── paper_airplane_rcbd.pdf   # Compiled report
```

## Requirements

- R (4.0+)
- R packages: `dplyr`, `ggplot2`, `knitr`, `rmarkdown`

Install dependencies in R:

```r
install.packages(c("dplyr", "ggplot2", "knitr", "rmarkdown"))
```
