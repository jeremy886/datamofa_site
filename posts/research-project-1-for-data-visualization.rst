.. title: Research Project 1 for Data Visualization
.. slug: research-project-1-for-data-visualization
.. date: 2017-08-27 21:46:31 UTC+10:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text




Step 1: Selection of Data Set
#############################

The data set is aggregated by the Australian Burea of Statistics from the 2016 census.

Source
======

Source of the data set: `the Australian Bureau of Statistics website`_.

If you want to download the files: `Link`_

.. _the Australian Bureau of Statistics website: https://datapacks.censusdata.abs.gov.au/datapacks/

.. _Link: http://www.censusdata.abs.gov.au/CensusOutput/copsubdatapacks.nsf/All%20docs%20by%20catNo/2016_GCP_POA_for_Vic/$File/2016_GCP_POA_for_Vic_short-header.zip?OpenElement&key=ded92a6f-4e19-ead5-9518-f22966129223

Step 2: Topic of Interest
#########################

Income, Gender and Residence

1. Is Australian weekly income associated with sex?
2. Is Australian weekly income associated with the postal code?


Step 3: Codebook
################

The Australian Bureau of Statistics (ABS) uses filename, sex and ages to differentiate data and this creates a unique way of storing data.

After checking the meta files, I know income records are stored in these three files:

* 2016Census_G17A_VIC_POA.csv
* 2016Census_G17B_VIC_POA.csv
* 2016Census_G17C_VIC_POA.csv

Code
====

POA_CODE_2016: Postal Areas (POA)
---------------------------------
It is recorded like POA3000. 3000 is the postal code. All postal code in Victoria, Australia has 4 digits and starts with 3.

Income per Sex Per Age
----------------------
Sex is denoated by:

* M for Male, 
* F for Female, 
* P for Persons (all sexes).

Ages are grouped in:

* 15-19: 15_19_yrs
* 20-24: 20_24_yrs
* 25-34: 25_34_yrs
* 35-44: 35_44_yrs
* 45-54: 45_54_yrs
* 55-64: 55_64_yrs
* 65-74: 65_74_yrs
* 75-84: 75_84_yrs
* 85 and over: 85_yrs_ovr or 85ov
* Total: Tot

Weekly Income are denoated by:

* Negative/Nil income: Neg_Nil_income
* $1-$149: 1_149
* $150-$299: 150_299
* $300-$399: 300_399
* $400-$499: 400_499
* $500-$649: 500_649
* $650-$799: 650_799
* $800-$999: 800_999 
* $1,000-$1,249: 1000_1249
* $1,250-$1,499: 1250_1499
* $1,500-$1,749: 1500_1749
* $1,750-$1,999: 1750_1999
* $2,000-$2,999: 2000_2999
* $3,000 or more: 3000_more
* Personal income not stated: PI_NS_ns

Therefore: 

F_300_399_Tot represents:

* Female
* Weekly income between 300 and 399
* Across all age groups (total)


P_PI_NS_ns_25_34_yrs:

* Persons (male, female or others)
* Personal Income not stated
* Age between 25 to 34


Literature Review
=================

Search by keywords: gender income inequality

Data from the 1976 Australian census, which allow some assessment of how worker characteristics and the sex-typing of jobs affect the lower incomes of women, lead to the general conclusion that, while direct wage discrimination may have been virtually eliminated, occupational segregation by gender, discontinuous career patterns and part-time employment continue to depress the earnings of women.

Citation:

`F. L. Jones`; Sources of Gender Inequality in Income: What the Australian Census Says, Social Forces, Volume 62, Issue 1, 1 September 1983, Pages 134–152, https://doi.org/10.1093/sf/62.1.134

Search by keywords: income residence OR income postal (zip) code

For income and residence, probably because this type of data is collected directly so I cannot really find any paper talking about this. Most people probably treat the association of income and residence as common sense. I am interested in examining it by statistical measure.

Hypothesis
==========

1. Australian Females earn significant less weekly than their male counterparts.
2. Australians' weekly income is linked to where they live.




