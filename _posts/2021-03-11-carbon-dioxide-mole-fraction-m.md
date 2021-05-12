---
title: >-
  Carbon Dioxide Mole Fraction Measurements and Model Output in the Northeast
  Corridor Baltimore/Washington for February 2016
created: '2021-03-11T17:20:32.291430'
modified: '2021-03-11T17:20:32.291438'
state: active
type: dataset
tags:
  - Emission Inventories
  - Ghg Concentration Measurements
  - Greenhouse Gas Measurements And Models
  - Urban Greenhouse Gas Domes
groups: []
csv_url: >-
  https://data.nist.gov/od/ds/6A4D752E493C3B19E053245706819BFD1917/NDC-2016-co2-91m-1-hour-20170504.csv
json_url: ''
layout: post

---
Dataset accompanying publication:

Martin, C. R., Zeng, N., Karion, A., Mueller, K., Ghosh, S., Lopez-Coto, I., Gurney, K. R., Oda, T., Prasad, K., Liu, Y., Dickerson, R. R., and Whetstone, J.: Investigating sources of variability and error in simulations of carbon dioxide in an urban region, Atmos. Environ., https://doi.org/10.1016/j.atmosenv.2018.11.013, 2018.

Data files presented here include both carbon dioxide (CO2) mole fraction observations from NIST-Earth Networks tower stations in the region surrounding Washington, D.C. and Baltimore, MD and modeled mole fractions for these same sites.  Please refer to the publication above for all details, including locations of sites, and abbreviations of models and site codes.  Observations from SNP are not included, as they can be obtained from NOAA/ESRL.

Model Output Files:

All files are comma-delimited text files.  The filename indicates the site (three letter code: SNP, ARL, NDC, HAL), followed by the inlet height above ground (in meters), followed by the name of the inventory (Vulcan, ODIAC, ODIACFIX, EDGAR, FFDAS, VEGAS), or Back, indicating the incoming CO2 mole fraction background.  The total modeled CO2 mole fractions, for example, for FFDAS, are the sum of Back, VEGAS, and FFDAS tracers.

Example: HAL_29_FFDAS.csv contains the CO2 mole fraction contribution at HAL at 29m from the FFDAS inventory.  The sum shown in the paper is HAL_29_FFDAS + HAL_29_Back + HAL_29_VEGAS.

Model output files contain two columns:
The date-time stamp (UTC), and the CO2 mole fraction in micromoles of CO2 per mole of dry air, or ppm.

Observation Files:

CO2 Measurements are reported on the WMO X2007 (CO2) scales. Refer to Verhulst et al, 2017 for measurement and calibration details.

Verhulst, K. R., A. Karion, J. Kim, P. K. Salameh, R. F. Keeling, S. Newman, J. Miller, C. Sloop, T. Pongetti, P. Rao, C. Wong, F. M. Hopkins, V. Yadav, R. F. Weiss, R. M. Duren and C. E. Miller (2017), Carbon dioxide and methane measurements from the Los Angeles Megacity Carbon Project Part 1: calibration, urban enhancements, and uncertainty estimates, Atmos. Chem. Phys., 17(13), 8313-8341, doi:10.5194/acp-17-8313-2017.

Each file name is encoded with the site, year, revision number and date, as follows:

For all sites, all file names follow this naming scheme: 

[site]-[year]-[gas]-[measurement height]-[averaging-interval]-[revision date].csv

Example:  ARL-2016-co2-100m-1-hour-20160504.csv

Column Headers (with description) for observation CO2 files:

datetime_UTC (date, dd-mm-yyyy HH:MM:SS)

dec_year_UTC (decimal year)

yyyy (year)

mm (month)

dd (day)

HH (hour, UTC)

co2_ppm (dry air mole fraction, ppm, averaged over the hour following the time stamp)

co2_SD (standard deviation of air data in 1 hour)

co2_n_minutes (number of 1-minute values in each 1-hour average)

co2_min (ppm, minimum 1-min value in each 1-hour)

co2_max (ppm, maximum 1-min value in each 1-hour)

co2_uncertainty (ppm, 1-sigma measurement uncertainty)

co2_flags (data quality flag: "..P" indicates preliminary data, which might change if a final calibration is applied at a later date)

