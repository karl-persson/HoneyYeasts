# Honey-associated yeast diversity in Sweden

### Data analysis and figure generation

This repository contains the R scripts, datasets, and figures associated with the manuscript:

**Persson K, Martindale M, Winnicki L, Persson A, Geijer C.**

_Nationwide citizen science reveals core and rare osmotolerant yeast communities in Swedish honey._

Submitted to _ISME Communications_.

### Project overview

Honey represents an extreme microbial habitat characterized by high sugar concentrations, low water activity, and antimicrobial compounds. Despite these conditions, specialized yeasts persist in honey and nectar-associated environments.

In this study, we conducted a nationwide citizen science survey involving Swedish beekeepers, collecting honey samples from 103 geographic locations. Through culture-based isolation and molecular identification, we established a collection of approximately 2,400 yeast isolates representing 85 species across 26 genera.

Representative strains were characterized for osmotolerance, glucose and fructose utilization, and their ability to ferment diluted honey. Metabolite profiling was performed using HPLC, LC–MS/MS, and GC–MS.

The study investigates the relationship between yeast diversity, geographic distribution, and physiological traits associated with persistence in high-sugar environments.

### Repository contents

The repository contains all data and scripts required to reproduce the figures presented in the manuscript.

- **R Markdown script:** Main script used for data processing, statistical analyses, and figure generation.
- **DATA:** Datasets used to generate the figures and perform statistical analyses.
- **PLOTS:** Generated plots corresponding to the main and supplementary figures in the manuscript.
- **Supporting files:** Additional files required for figure generation, including custom color palettes.

### Data analysis

Data processing, statistical analyses, and visualization were primarily performed in R (version 4.6.1).

The main R Markdown script contains the code used to generate all figures presented in the manuscript, prior to final graphical adjustments and aesthetic refinement in Adobe Illustrator.

### Reproducing the figures

To reproduce the figures:

1. Clone or download this repository.
2. Open the main R Markdown script in RStudio.
3. Install the required R packages listed in the script.
4. Run the script using the provided datasets.

The script uses relative file paths and should be executed from the repository's root directory.

Generated figures are saved in the `PLOTS` folder.

### Software

Analyses were performed using R (version 4.6.1), primarily with packages from the tidyverse.

Additional packages used for statistical analyses and visualization include `ggplot2`, `dplyr`, `tidyr`, `vegan`, `growthcurver`, `ComplexHeatmap`, `metacoder`, `treemapify`, `sf`, `rnaturalearth`, `ggspatial`, and `fmsb`.

The complete list of package dependencies is available in the R Markdown script.

### Citation

If you use these data or scripts, please cite:

Persson K, Martindale M, Winnicki L, Persson A, Geijer C. _Nationwide citizen science reveals core and rare osmotolerant yeast communities in Swedish honey._

Publication details and DOI will be added following publication.