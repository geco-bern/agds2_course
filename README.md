# AGDS II Course Website

This repository contains the markdown files used to generate the website for the AGDS II course: https://geco-bern.github.io/agds2_course/

Note: online rendering was deactivated. Please render this book offline and 
manually publish to `gh-pages` by doing `quarto publish book`.

This requires two files for the leaderboard that are outside of the repository:
- `../handfull_of_pixels_LULC.txt`
- `../drought_predictors_competition_reference_results_fLUE.csv`
(Alternatively outcomment lines 61 and 135 (`read.csv(...)`) and activate
the code in lines 58 and 125 in the corresponding `leaderboard.qmd` to generate 
a mock table using random values as reference.)