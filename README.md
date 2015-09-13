# Miller and Ulrich Response
The second draft of a response to Miller and Ulrich's "Interpreting Confidence intervals: A comment on Hoekstra, Morey, Rouder, and Wagenmakers (2014)" (Miller and Ulrich is, as of July 2015, in press in Psychonomic Bulletin & Review).


DOI for citing version 0.2: [![DOI](https://zenodo.org/badge/doi/10.5281/zenodo.30916.svg)](http://dx.doi.org/10.5281/zenodo.30916)


### Guide to the data set

This repository now includes the data set from [Hoekstra, Morey, Rouder, and Wagenmakers (2014)](http://link.springer.com/article/10.3758%2Fs13423-013-0572-3), as `HoekstraEtAl2014.data.csv`. A brief description of the columns in the data follows. For all columns, `NA` indicates a missing response.

Column(s)  | Possible values | Description 
-----------|-----------------|-------------
`Q1` - `Q6`    | `0`, `1`, `NA`        | Did the survey respondent endorse the item (`1`) or not (`0`)?
`expertise`| Numeric value between 1 and 10, inclusive, or `NA` | Self-rated statistical expertise (see paper for details)
`group` | string variable | Group the survey respondent was a part of (see paper for details)
`Nendorsed` | Integers between `0` and `6`, inclusive, or `NA` | Total number of statements endorsed; sum of first six columns
