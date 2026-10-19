# FA503: Drug Formulation and Production B

Data science material for **FA503 Drug Formulation and Production B** (BSc Pharmacy, University of Southern Denmark). The material shows students how to analyse experimental data in R using Quarto guides.

This repository holds the R and Quarto material only. The full course material lives in ItsLearning. See the [course description](https://odin.sdu.dk/sitecore/index.php?a=fagbesk&id=208858&lang=en&listid=) for the course content and learning outcomes.

The documents are written in English.

## Data Science Learning Outcomes

The learning outcomes from the official course description that this material supports. The student demonstrates the ability to:

- Collect, handle and process datasets using data processing and visualization tools such as R (RStudio).

## Structure

```
├── dissolution/                  Lab exercise: dissolution testing of tablets
├── uniformity_of_dosage_units/   Lab exercise: uniformity of dosage units (Ph. Eur. 2.9.40)
├── sieve_analysis/               Exercise class: particle size distribution by sieve analysis
├── CITATION.cff
├── LICENSE                       CC BY 4.0 (teaching content)
└── LICENSE-code                  MIT (code)
```

Each folder is self-contained: the guide and the files it needs sit together, so students can download a single folder and work from it.

## Setup

You need:

* [R](https://cran.r-project.org/)
* [RStudio](https://posit.co/download/rstudio-desktop/) (includes Quarto)

Install the R package used in the course:

```r
install.packages("tidyverse")
```

## Versions

The `main` branch holds the material for the current year. When a course run ends, it is archived in a branch named after the year (for example `2026`).

## Citation and license

If you reuse or adapt the material, please cite it using [CITATION.cff](CITATION.cff) (GitHub shows a "Cite this repository" button).

Teaching content is licensed under [CC BY 4.0](LICENSE) and code under [MIT](LICENSE-code).

Part of the [CPDSE](https://github.com/CPDSE-EDUX) teaching material from the Center for Pharmaceutical Data Science Education.

