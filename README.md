# Project: Cleaning data and Analysis
 

## Getting Started

The main purpose of this project is to determine if the is a correlation between Developed Countries and Shark Attacks.
Furthermore, we expect to see a decreasing tendency in Shark Attacks.

In order to do so, databases need to be cleaned.
The process is described below.

### Process

FIRST DataFrame. 
Table that contains the information for Shark Attacks;

*Blank Spaces,
*Empty cells,
*Random numbers as Years,
*Cities as Countries,
*Geograohic Areas as Countries,

Thus, some names of the countries have been re-named in order to standarize this list.

The first part of the code will be used to clean all the unrelevant information that this dataframe contains for relevant columns (Year and Country). 

SECOND DataFrame.
Table that contains the information for Human Development Index;

This table did not contain any of the above constraints.
However, it contains:

*Empty Columns.
*Double header.
*Remove irrelevant years and information.

Furthermore, a column has been added in order to know the real status for each country. 
Also, some names of the countries have been re-named in order to standarize this list.

Find listed below relevant information about developed countries:

*Ratings Human Development Report: Values ranging from 0 to 1 (1=highest grade, 0=lowest grade). There are 4 groups:

(“High Human Development”), with more than 0,80
(“Medium Human Development”), from 0,70 to 0,80
(“Medium Human Development”), from 0,50 to 0,70
(“Low Human Development”), with less than 0,55


LAST STEP OF THE PROCESS.
This two DataFrames have been merged in order to proceed with the analysis of the data.

The TOP20 Developed Countries are listed with the total accumulated amount of Shark Attacks.

With this data input, some of the countries with larger number of attacks have been plotted in order to perform individual analysis. This data apparentaly shows no correlation with the initial hypothesis, thus, a full trend with all the countries and years has been plotted to repeat the analysis.

The new graph repeats the same behaviour, so we can conclude that there is no trend to confirm the initial hypothesis, as number of attacks seem to have no correlation with Developed Countries.

### Installing

Importing the relevant libraries.

import pandas as pd
import numpy as np
import re
import matplotlib
import matplotlib.pyplot as plt


## Built With

* [UNDP - Human Development Reports](http://hdr.undp.org/en/data#) - The web used to extract Human Development Report for all countries
* [Economipedia - Definition](https://economipedia.com/definiciones/indice-desarrollo-humano.html) - Explanation of Human Development Report 
* [Kaggle](https://www.kaggle.com/teajay/global-shark-attacks/version/1) - Information about Shak Attacks

