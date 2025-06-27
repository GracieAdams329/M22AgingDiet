# ONT RNASeq Pipeline for M22AgingDiet (GracieM22AgingDiet_130424)
**Please see https://github.com/GracieAdams329/ONT-RNASeq-Pipeline.git if there are any default bits of code missing, especially at the start eg. to install certain packages!**
Pipeline for analysis of whole transcriptome data generated using ONT's PCR-cDNA barcoding kits on the GridION (or PromethION).  
Previously tracked/stored using Google Docs on the Simons Lab Google Drive/ONT Sequencing folder (up until 21/10/24).

Help for formatting: https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

Gracie’s version of notes from [Copy of Nanopore_RNAseq_pipeline_cleaned_up](https://docs.google.com/document/d/1Itus_OteYWvJQwgSaKjMoCFGclphFPsdYA5sjoX6CVY/edit?usp=sharing)

## TERMINOLOGY:
**FLOW CELL:** the physical flow cell the library is run on.  
**LIBRARY:** the prepared library of (usually) 12 barcodes (12 samples).  
**RUN:** the individual sequencing run on the GridION - a new one starts when the library is first run on the flow cell and extra runs will be added when the flow cell is cleaned and reloaded with library during the experiment.  
**BARCODE:** each individually barcoded sample within the library (usually 12 barcoded samples per library).  

## [Notes and info on Simons Lab Google Drive  ](https://drive.google.com/drive/folders/1sj6Gr44TPnA9NQvY7-rOnP5ToNrBDRg7?usp=drive_link)
[Bioinformatics - Handy Notes](https://drive.google.com/drive/folders/1RptxJ11FY9PhAjUSbzz1uFpFnqcjdmCe?usp=drive_link)  
[Using the HPC Systems ](https://docs.hpc.shef.ac.uk/en/latest/hpc/index.html#gsc.tab=0)  
[Gracie RNA Seq Nanopore Pipeline Notes](https://docs.google.com/document/d/1UFiE2f2-SWXBRz_2JHGRO0K69vlv31UealYjHEpKmpM/edit?usp=sharing)  
[Notes on alternative splicing packages - April 2024](https://docs.google.com/document/d/1rPRdeZvj9XnTXJ-aj3geMLI2yCJgcn_zdt2O4tAytKg/edit?usp=sharing)
