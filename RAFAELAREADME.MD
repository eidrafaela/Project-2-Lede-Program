# Brazil paid 82% more per kilogram for liver-based products in 2025

## What I aimed to accomplish

My goal was to investigate whether Brazil's discussions since 2020 on banning foie gras have had any measurable impact on imports/exports, and whether there is a disconnect between public policy debates and actual market dynamics.

## Short description of my findings

Trade data shows no clear link between Brazil's six-year congressional debate over a foie gras ban (Bill 90/2020) and its imports from France. Official records show continued trade between 2019 and 2025, with the average price per kilogram rising 82% by 2025, the highest on record. Different databases (Comex Stat, UN Comtrade, Eurostat, FranceAgriMer) diverge significantly in their numbers, but none show evidence that the political debate has slowed the trade.

## Summary of the data collection process

The data was obtained through the websites of the databases.

- [Eurostat](https://docs.google.com/spreadsheets/d/1kuGZSPDObYOzVsnnHqJv3vDTaGV-SoTB/edit?usp=sharing&ouid=105689490645911110770&rtpof=true&sd=true)
- [Comex Stat](https://docs.google.com/spreadsheets/d/1RsXwTWYTVRBq0PihcmT0XEbO4AF7gA3BoYtr2rRpELQ/edit?usp=sharing)
- [Comex Stat 2](https://docs.google.com/spreadsheets/d/1m7kSd-jhIThahMCMQcyhmxFm-Cce7BPLi3rvENqu2D4/edit?usp=sharing)
- [UN Comtrade Database](https://docs.google.com/spreadsheets/d/1HCycwyItPBSOfJ3Srr4jyNtr__-2m-56jwofPF7h4FQ/edit?usp=sharing)
- [FranceAgriMer](https://www.franceagrimer.fr/chiffre-et-analyses-economiques/fiche-filiere-foie-gras)
- [HS Codes/NCM - Brazil Comex Stat](https://docs.google.com/spreadsheets/d/1emPnQGGI00XLj5gHJ7jJdWdc4O9bWU-dTCRPM_98QIg/edit?usp=sharing)

## Overview of the data analysis process

The data was analyzed based on the CSV and pdf files obtained on the websites of each database. The
main steps were:

- Loaded the different datasets and analyzed the CSV files with pandas on the Jupyter Notebook to create the different visualizations;
- Used the API of the Comex Stat website to confirm if there was no data under the two Harmonized System Code (HS Code) codes that specifically classify foie gras: 02074300 (fatty duck livers) and 02075300 (fatty goose livers). 

## Notebooks 

- [Jupyter notebook Price per Kilo (Comex Stat)](Priceperkilo-imports.ipynb)
- [Jupyter notebook Imports (Comex Stat) vs Exports (UN Comtrade Database)](ImportsvsExports.ipynb)
- [Jupyter notebook Comex Stat API](APIcomexstat.ipynb)


## What new skills and approaches I developed

- Building and customizing charts in Datawrapper
- Analyzing data of importation and exportation 
- Using API to confirm that there was no specific information I was looking for on a website 

## Things I tried to do or wanted to do but did not have the skills/time

- I was not abble to do more complex charts as I do not have experience with that
