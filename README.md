# Pinellas-FL-USA-Cemetery-Interments
*A project to transform multiple disparate data collections about cemetary interments into a clean tidy data set optimized for analyzing genealogical data.*
## Experimental Design
The Pinellas Genealogical Society (PGS) has a set of text-based lists of interments of cemeteries in Pinellas county.  [They can be accessed here:](http://www.rootsweb.ancestry.com/~flpgs/pgs-cemetery-indexes.htm).
The design will produce a single data set optimized for genealogical research and analysis constructed from these data sources.
### Primary Objectives
1. Provide comprehensive data set representing all interments in Pinellas County
2. Provide dynamic, interactive web site to enable rich access to the data

#### Secondary Objectives
1. Provide process for updating records

##### Other Objectives

##### Structure
The structure of each of the source tables is not consistent accross the lists. Different levels of detail of the variables were captured for various cemeteries.  For example one cemetery may list the surname, first name/middle initial or middle name, name suffix, honorifics, years born and died.  Another may have these variables plus month and day of birth/death, and notes about additional inscriptions on the headstone.  The collection methods and current freshness of data varies for each list.  There are numerous data anamolies found in each list also (e.g. obscure entry: "DSC" in a name suffix variable, missing or incomplete records, suffix and honorifics intermingled, inconsistent capturing of maiden/previous name). The final output will provide the following variables with observations for each interment in Pinellas County:

**Surname** | **First_Name** | **Middle_Name_MI** | **Honorific** | **Suffix1** | **Suffix2** | **Born_Year** | **Born_Month** | **Born_Day** | **Died_Year** | **Died_Month** | **Died_Day** | **Inscription** | **Cemetery**

For a data dictionary describing classes and definitions of each of these variables see codebook.md.
######  Missing Data
            There are a large number of records missing the born/died details of month & day.  The design should capitalize on the information when it is available and make it clear when calculations are made with or without that level of detail.  This can have a significant affect on some calculations so care must be exercised.
