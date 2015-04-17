# Introduction #

This is Hisako's initial investigation.

# Research Questions #
  * What are problems when developing a language independent search algorithm that also works with Inuktitut? (technical)
  * What linguistic factors should be taken into consideration? (linguistic)
  * What are necessary steps to solve such problems?

# Problems #
## Encoding ##
  1. Encoding format of Inuktitut syllabary is not uniform, different corpora uses different formats (e.g. ProSyl, Nunacom, Unicode)
  1. Transliterated/romanized Inuktitut uses "&" for the lateral fricative, however "&" is an operating symbol in computer languages (that is, "&" won't be processed as part of a morpheme)

## Orthography and Phonology ##
  1. Phonological alternation (e.g. voice assimilation: Inuk+lu > Inuglu) may change the orthographic form of a morpheme in a word

# Methodology #

  * Locate existing Inuktitut search utilities: http://www.inuktitutcomputing.ca/SearchEngine/en/InuktitutSearchEngine.htm
  * Locate existing Inuktitut stemmers
  * List of morphemes: http://www.inuktitutcomputing.ca/DataBase/en/index.html
  * Get a corpus as test documents: Inuktitut Magazine - useful in that it has four languages in a package, Inuktitut, romanized, English and French
  * Pre-process corpus: UTF-8 encoding, stemming
  * Test the corpus on Recall & Precision: three paradigms: 1) no encoding, no stemming; 2) encoding, no stemming; 3) encoding, stemming ( 4) no encoding, stemming to complete the paradigm)


## Solutions ##

## Further Research ##

## To Do ##


