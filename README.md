# HTHH Impacts Analysis

This repository contains the code used to process data and reproduce the analyses and figures presented in:

> Extreme volcanic disturbance overwhelms a national network of marine protected areas

---

## Overview

This project analyses coral reef benthic and fish community responses to the 2022 Hunga Tonga–Hunga Haʻapai eruption using underwater visual census (UVC) data and benthic surveys.

All data processing, statistical analyses, and figure generation are implemented in **R** using reproducible workflows.

---

## System Requirements

- R version: 4.5.2 or later  
- Operating systems: macOS, Linux, Windows  
- Key R packages:
  - tidyverse
  - lme4 / glmmTMB
  - brms
  - ggplot2
  - sf (if spatial)
  
All dependencies are listed in script headers.

No non-standard hardware is required.

---

## Installation

1. Install R: https://cran.r-project.org  
2. Clone this repository:
   ```bash
   git clone https://github.com/PSmalls90/2022_HTHH_Eruption_Impacts
