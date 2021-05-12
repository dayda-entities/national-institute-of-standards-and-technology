---
title: >-
  Data to accompany the paper "Entropy Scaling of Viscosity -- II Predictive
  Scheme for Normal Alkanes"
created: '2021-03-11T17:23:18.881292'
modified: '2021-03-11T17:23:18.881299'
state: active
type: dataset
tags:
  - Entropy
  - Thermodataengine
  - Viscosity Data
groups: []
csv_url: 'https://data.nist.gov/od/ds/mds2-2289/MIDAS_alkanes.csv'
json_url: ''
layout: post

---
Viscosity data for normal alkanes (methane, ethane, etc.) taken from the literature to accompany the paper "Entropy Scaling of Viscosity -- II: Predictive Scheme for Normal Alkanes". The data were obtained from an internal version of the NIST ThermoDataEngine database version 10.4.2. File contents include 

## Contents ##

* MIDAS_alkanes.csv: The data file containing all the data considered in this study

* MIDAS_alkanes.bib: The bibliography associated with each datasource in BibTeX format

* allbibs.pdf: A PDF conversion of the bibliography

## Data File format ## 

* The data are in a comma-separated text format, with the column headings indicating the contents of the column, along with units, where appropriate

* The phase indicates how the data were measured "L" indicates a liquid phase, "G" a gas phase, "G L" a saturated vapor, and "L G" a saturated liquid

* For saturated states ("G L" or "L G"), the saturation temperature fully specifies the state

* For liquid and gaseous states, either the temperature and pressure or temperature and density are provided, and the unused state variable is empty

* Fluid names match the default names of the compound from NIST REFPROP library

* The column "TRC_code" indicates the reference code for the data point, and the same references (with spaces and & replaced with hyphens) are used as keys in the BibTeX file
