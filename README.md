# corona-ES
Analysis for corona cases 30/1/2020 - 03/12/2020
In this notebook you could find an analysis for the corona cases in Spain from 30/1/2020 to 03/12/2020. The purpose of the investigation is to analyse the access to PCR test by 
region during the first and the second wave.
 
 The analysis is mainly focus in the first stage of the study on the different regions in Spain giving the following variables:
  - Total cases per region and distribution on time series.
  - Cases detected by PCR test, antibodies, others and unknknown.
    
Variables:
 - Total: Sum of new cases detected y PCR, antibodies, others and unknown.
 - PCR: New cases detected by a PCR test for Covid - 19.
 - Antibodies: New cases detected by blood speed test, to find presence of antibodies to Covid - 19.
 - Others: New cases detected by other methods, mainly antigen detection Elisa test.
 - Unknown: New cases without information from the laboratory.

The time series given by the dataset is distributed by days. In order to display a propper visualization for 11 months of data, the time series is modified by weekly results.
Once the data is stablished on weekly time series, the analysis is followed by grouping the regions to the geographical location defining three big areas in the peninsula.

    - North, south and islands.

