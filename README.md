# Gerrymandering whiplash
This repo houses the code to reproduce the results in the [Gerrymandering Whiplash](https://protectdemocracy.org/wp-content/uploads/2026/09/Re-gerrymandering-Report.pdf) report.
Most of the relevant code and discussion is found in `redistricting_changes.ipynb`. 

Learn more about the report [here](https://protectdemocracy.org/work/what-gerrymandering-costs-voters/). You can also read the Associated Press story about this report [here](https://apnews.com/article/redistricting-house-trump-congress-c92f3e147771920edfb00eac5f1503f3).

## Data
The necessary data to run the analysis in `redistricting_changes.ipynb` should be placed in a `data/` directory. You'll need:
  - Block equivalency files for the 119th and 120th Congresses. You can find them [here](https://www.census.gov/geographies/mapping-files/2025/dec/rdo/119-congressional-district-bef.html) and [here](https://www.census.gov/geographies/mapping-files/2027/dec/rdo/120-congressional-district-bef.html), respectively. You can extract the state-level text files from the 120th Congress file into the `data/` directory directly.
  - P.L. 94-171 files for the ten states in question. You can find information on how to download them [here](https://www.census.gov/programs-surveys/decennial-census/about/rdo/summary-files.html). These should be placed in the `data/` directory as ZIP files with names like `al2020.pl.zip`.

`florida_districts_map.ipynb` additionally needs the TIGER/Line 2020 census block shapefile for Florida, `tl_2020_12_tabblock20.zip`, available [here](https://www2.census.gov/geo/tiger/TIGER2020/TABBLOCK20/tl_2020_12_tabblock20.zip). It should also be placed directly in `data/`.
