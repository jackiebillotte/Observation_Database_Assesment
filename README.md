# Observation_Database_Assesment

This pipeline is designed to evaluate taxonomic consistency, how well geo-tagging fits known distributions, and the image quality of crowd-sourced biodiversity data acquired from iNaturalist, a crowd-sourced biodiversity database.

While this pipeline was written using images and metadata from iNaturalist (iNaturalist.org), it can also be employeed for the evaluation of metadata and images from other obersvationally based databases.

Input
Sample input files can be found in the "Sample Input" folder. Metadata spreadsheets containing obervational IDs, taxonimic labels, and coordinates are the minimum required. An additional taxonmic referece file("Taxon_reference.csv) is also needed.

Out
The piplines will output results to the current working directory. 
Outputs include:
      Raw taxon consistency results
      Taxon consistency overall 
      Taxon consistency by genus
      Taxon consistency by species
      Geo-tagging consistency results
      Raw BRISQUE scores by observational ID
      Average and range of BRISQUE scores by family
      Average and range of BRISQUE scores by genus
      Average and range of BRISQUE scores by species
