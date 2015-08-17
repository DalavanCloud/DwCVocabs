VertNet Darwin Core Vocabularies
=========

This repository contains files containing lists of distinct combinations of verbatim original values for data passing through data set-specific instances of the VertNet Darwin Core Migrator Toolkit (). As much as possible, these vocabularies have also been annotated with recommended standardized values for the verbatim orignal terms. These files are used in the VertNet Darwin Core Migrators to reconcile real-world values for Darwin Core terms to somewhat more standardized values to facilitate searching in aggregated data stores.

Classification provides higher classifications (according to Catalog of Life wherever possible) based on genus only.

Geography provides continent, country, countryCode, stateProvince, county, municipality, waterbody, islandGroup, island based on verbatim values of these same Darwin Core terms. Innumerable sources have been used to reconcile these geographic combinations, and the sources are not cited. More often than not, Wikipedia has been used, though the Global Administrative Areas data set (GADM, http://www.gadm.org/) and The Getty Thesaurus of Geographic Names (TGN, http://www.getty.edu/research/tools/vocabularies/tgn/) have also been a good sources.

## Standardized Reference Data Set for Vertebrate Taxon Name Resolution

[https://github.com/tucotuco/DwCVocabs/blob/master/vocabs/tests/VertNetTaxonomyTestSet.csv](https://github.com/tucotuco/DwCVocabs/blob/master/vocabs/tests/VertNetTaxonomyTestSet.csv)

This data set consists of a random set of 1000 records of distinct taxon name combinations from the 18 April 2015 snapshot of the data aggregated in VertNet. The data were carefully vetted to track various kinds of errors as well as synonyms. Entries were resolved to determine valid taxon name wherever possible using the workflow documents at (https://github.com/tucotuco/DwCVocabs/wiki/VertNet-Taxonomy-Test-Set).
