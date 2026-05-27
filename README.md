[![Last-updated](https://img.shields.io/badge/last%20update-May%202026-brightgreen.svg)](ithub.com/sfield2/Field_and_DePlata-Peterson2026)
[![License](https://img.shields.io/github/license/mashape/apistatus.svg)](http://choosealicense.com/licenses/mit/)


# Research compendium for Glowacki et al. (under revision)
This R-based research compendium supports an analysis of the Seriation Multiverse in the US Southwest.

# Overview
The script used in this analysis "Glowacki et al_2026.qmd", which is a Quarto markdown document that includes code to perform all of the data scraping and image creation steps reported in the manuscript. 

Glowacki et al_2026.qmd performs the following steps:
1. Import `R` dependencies
2. Establish unique seriation and occupational assignment functions
3. Import Site Data (NOTE: some of this data is not publicly accessible)
4. Compare Occupational Histories of sites on Park Mesa, Mesa Verde based on different seriation techniques
   
# Directory Strucutre
1. `Glowacki et al. 2026.qmd`: `R` scripts to conduct analyses
2. `Data`: Directory containing data used in study. NOTE: Non-publicly accessible data is not included.
6. README.Rmd: This `README` file

# Citation
When using the code included in this research compenidum, please cite all of the following:

Glowacki, Donna M., Katherine Portman, and Sean Field. 2026. Methods Matters: Assessing the Seriation Multiverse in the U.S. Southwest. Journal of Archaeological Method and Theory, Under Review.

Glowacki, Donna M., Katherine Portman, and Sean Field. 2026. Research Compendium for Methods Matters: Assessing the Seriation Multiverse in the U.S. Southwest. Journal of Archaeological Method and Theory. Version 1.0.0 Zenodo [DOI]

# Requirements
This analysis requires R (≥ 4.2.0) and the following packages:
`ggplot2` `tidyterra` `dplyr` `tidyr` `stringr` `ggpubr` `scales` `lmtest` `tseries` `tidyverse` `compiler` `msm` `snowfall` `parallel` `doParallel`
