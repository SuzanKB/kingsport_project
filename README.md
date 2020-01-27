# Kingsport_project

Version 0.1.0

Things that happen in Kingsport.
Source data is published at https://www.vektis.nl/open-data
Disclamer from source Vektis:
"Disclaimer Vektis open databestand
De Open Databestanden zijn toegankelijk voor persoonlijke en/of onderzoeksdoeleinden. Het is niet toegestaan de data door te verkopen of te gebruiken voor commerciële doeleinden. Vektis kan niet aansprakelijk worden gesteld voor het gebruik of de gevolgen van het gebruik van de data door derden. Bij elk gebruik van de data dient de bronvermelding te worden opgenomen (bron Vektis).

Heb je vragen over onze open databestanden? Mail ons: opendata@vektis.nl."


## Project organization

```
.
├── .gitignore
├── CITATION.md
├── LICENSE.md
├── README.md
├── requirements.txt
├── bin                <- Compiled and external code, ignored by git (PG)
│   └── external       <- Any external source code, ignored by git (RO)
├── config             <- Configuration files (HW)
├── data               <- All project data, ignored by git
│   ├── processed      <- The final, canonical data sets for modeling. (PG)
│   ├── raw            <- The original, immutable data dump. (RO)
│   └── temp           <- Intermediate data that has been transformed. (PG)
├── docs               <- Documentation notebook for users (HW)
│   ├── manuscript     <- Manuscript source, e.g., LaTeX, Markdown, etc. (HW)
│   └── reports        <- Other project reports and notebooks (e.g. Jupyter, .Rmd) (HW)
├── results
│   ├── figures        <- Figures for the manuscript or reports (PG)
│   └── output         <- Other output for the manuscript or reports (PG)
└── src                <- Source code for this project (HW)

```


## License

This project is licensed under the terms of the [MIT License](/LICENSE.md)

## Citation

Please [cite this project as described here](/CITATION.md).
