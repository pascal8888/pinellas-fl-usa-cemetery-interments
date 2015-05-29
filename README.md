# Pinellas-FL-USA-Cemetery-Interments
*A project to transform multiple disparate data collections about cemetary interments into a clean tidy data set optimized for analyzing geneological data.*
## Experimental Design
The Pinellas Genealogical Society (PGS) has a set of text-based lists of interments of cemeteries in Pinellas county.  [They can be accessed here:](http://www.rootsweb.ancestry.com/~flpgs/pgs-cemetery-indexes.htm).
### Primary Objectives
1. Provide comprehensive data set representing all interments in Pinellas County
2. Provide dynamic, interactive web site to enable rich access to the data

#### Secondary Objectives
1. Provide process for updating records

##### Other Objectives

##### Structure
The structure of each of the source tables is not consistent accross the lists. Different levels of detail of the variables were captured for various cemeteries.  For example one cemetery may list the surname, first name/middle initial or middle name, name suffix, honorifics, years born and died.  Another may have these variables plus month and day of birth/death, and notes about additional inscriptions on the headstone.  The collection methods and current freshness of data varies for each list.  There are numerous data anamolies found in each list also (e.g. obscure entry: "DSC" in a name suffix variable, missing or incomplete records, suffix and honorifics intermingled, inconsistent capturing of maiden/previous name).

