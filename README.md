

This Genes_Araya-Salas_Dahlin_Wright_FronBirdSci_2023_README.txt file was created on July 17, 2023 by Molly Genes
---

This Genes_Araya-Salas_Dahlin_Wright_FronBirdSci_2023_README.md file was created on July 17, 2023 by Molly Genes

-------------------
GENERAL INFORMATION
-------------------

Title of Dataset: Genes_Araya-Salas_Dahlin_Wright_FronBirdSci_2023

Corresponding Author Information:

    Timothy Wright
    Department of Biology, New Mexico State University
    Las Cruces, NM 88003
    wright@nmsu.edu

Dates of data collection: June - July, 2016 - 2019

Data collection locations: Mexico, Guatemala, (Bay Islands) Honduras*, Nicaragua, Costa Rica (geographic coordinates available in metadata with the exception* of one location in the Bay Islands which remains anonymous at the owner’s request)

Funding:

This work was supported by the World Parrot Trust and New Mexico State University’s College of Arts & Sciences.


--------------------------
DATA USE/ACCESS INFORMATION
--------------------------

Restrictions and limitations of data reuse: We do not place restrictions on the use of this data, although we do ask that we be contacted prior to its use, and any collaboration or co-authorship discussed as appropriate. 

Recommended citation data use: See the Dryad Data repository page for this data.

Other publicly accessible locations of data: The code for analyses listed below will be made available in a GitHub repository (mgenes/cultural-atlas-of-vocal-variation).


--------------------
DATA & FILE OVERVIEW
--------------------

Files are stored in Data and Code folders. See below for more specific information.

--------------------------
DATA-SPECIFIC INFORMATION
--------------------------

Data Pre-processing
---------------------

Code:

- Call_Pre_Processing.Rmd (code in R Markdown format)

Data:

We provide pre-processed data consisting of calls selected from longer sound files and filtered via quality control methods.

The metadata containing selection table for quality-controlled calls used for analysis in .csv format. The metadata includes the selection table, as well as call identifying information, identity of the bird calling, and site information:

- Yellow_naped_amazon_vocal_metadata.csv

The R object containing metadata containing the selection table for quality-controlled calls used for analyses:

Yellow_naped_amazon_vocal_metadata.RDS

The extended selection table for quality-controlled calls used for analysis in .RDS format (an R object written to a file). Extended selection tables contain the selection table data frame (here, the same selection table information from the above .csv format), as well as .wav files for selected calls.

- Yellow_naped_vocal_data_EST.RDS


----------------
Sound Analysis
----------------

Code:

- YNA_MDS_PCA.Rmd (code in R Markdown format)

Data:

An R object containing the spectrographic cross-correlation peak correlation values for each pair of calls.

- SPCC_YNA_vocal_data.RDS

An R object containing the Kruskal non-metric multi-dimensional scaling values used to make the kernel plot graphics

- YNA_kernel_isoMDS.RDS


Mantel Tests & Spatial Autocorrelation
----------------------------------------

Code for mantel testing and spatial autocorrelations can be found at the following GitHub repository:
https://github.com/maRce10/geographic_call_variation_yellow-naped_amazon


--------------------------
METHODS AND INFORMATION
--------------------------

See the associated publication for more information on how data were collected, processed and analyzed. These materials contain information about the software and versions of software used, quality control processing, and those who contributed to this research.
