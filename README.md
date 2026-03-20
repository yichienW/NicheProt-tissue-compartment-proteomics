# NicheProt-tissue-compartment-proteomics
--------------------
GENERAL INFORMATION
--------------------
​
**Publication or Dataset title:** NicheProt: Cell-type-resolved proteomics of tissue compartments  

​
**Authors:** Yi-Chien Wu, Dylan Schwartz, Elie Abi Khalil, Aditi Upadhye, Jalees Rehman, Steve Seung-Young Lee  

​
**Please cite this data as the following:**  NicheProt: Cell-type-resolved proteomics of tissue compartments
Yi-Chien Wu, Dylan Schwartz, Elie Abi Khalil, Aditi Upadhye, Jalees Rehman, Steve Seung-Young Lee
bioRxiv 2025.10.23.684231; doi: https://doi.org/10.1101/2025.10.23.684231  

  
**Relevant links:** <remove links that are not relevant>  
> * Publication DOI: [doi.org/MY-PAPER-DOI](https://doi.org/MY-PAPER-DOI-URL) 
> * To view an archived record of this repository: [My-ZENODO-DOI](https://zenodo.org/doi/MY-ZENDODO-DOI-URL) 
> * Mass spectrometry proteomics dataset, visit: [My-PRIDE-dataset](https://www.ebi.ac.uk/pride/)


--------------------
PROJECT SUMMARY
--------------------
​In this project, we present **NicheProt**, a 3D optical microscopy–guided, photobleaching-mediated cell barcoding approach for isolating intact, specific cell types from defined microanatomical tissue compartments (niches). 

This method enables cell type– and microregion–resolved proteomic analysis, facilitating the discovery of previously unrecognized cell subtypes and their functional roles within distinct tissue environments.

This repository contains R scripts used to:
- assess whether tissue cryopreservation introduces detectable protein artifacts, 
- evaluate the NicheProt workflow for potential protein artifacts, and
- analyze two compartment-specific dendritic cell populations in a lipopolysaccharide (LPS)-induced inflammation mouse spleen model.


--------------------
SCRIPT OVERVIEW
--------------------

| Analysis | Script | Description |
|----------|--------|-------------|
| Cryopreservation artifact assessment | `Validation1.Rmd` | Evaluates whether cryopreservation introduces detectable protein artifacts |
| NicheProt workflow artifact validation | `Validation2.Rmd` | Assesses potential protein artifacts introduced by the NicheProt workflow |
| Dendritic cell analysis | `LPSspleen_DCsubsets.Rmd` `LPSspleen_DCsubsets_GSEAanalysis.Rmd`| Identifies compartment-specific dendritic cell populations and differential protein expression |
