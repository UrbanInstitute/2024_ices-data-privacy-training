# Introduction to Data Privacy and Data Synthesis Techniques

## Welcome

This book contains materials for **Introduction to Data Privacy and Data Synthesis Techniques** at the [2024 International Conference on Establishment Statistics](https://ww2.amstat.org/meetings/ices/2024/) in Glasgow, Scotland. 

## Abstract

This course will provide an overview of current data privacy methodology, focusing on the generation of synthetic data and application of differentially private methods. Through examinations of case studies, attendees will learn to apply data privacy techniques and evaluate the resulting disclosure risk and data utility.

## Instructor

Aaron R. Williams is a lead data scientist for statistical computing at the Urban Institute. He works on data privacy, data imputation, microsimulation modeling, and survey analysis with a focus on income, wealth, tax, and retirement policies.

Williams has developed systems for safely releasing administrative data for research, including the Urban-Brookings Tax Policy Center's synthesis of individual tax records and the US Department of Labor's Safe Transfer, Restricted-Use Data Lake. He is a member of the Bureau of Labor Statistics Technical Advisory Committee, an adjunct professor in the McCourt School of Public Policy at Georgetown University, and the leader of Urban's R Users Group.

## Rendering the Documentation

This documentation is organized in a [Quarto Book](https://quarto.org/docs/books/). The documentation renders as a website for GitHub pages and a standalone PDF. We will follow the process for [rendering Quarto books](https://quarto.org/docs/books/#publishing).

0. Never render individual .qmd pages. 
1. Open `2024_ices-data-privacy-training.Rproj`. This should open RStudio and you should see "2024_ices-data-privacy-training" in the top right corner instead of "Project: (None)". Make desired edits.
2. In the Terminal, submit `quarto render`. It will take several minutes to render but all files associated with the website. 
3. Add, commit, and push your files to GitHub. Open a PR to the `development` branch. 