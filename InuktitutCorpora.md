


# Nunavut Hansard #

This a large corpus of parliamentary proceedings in Nunavut from ~1990-2000. It contains a surprisingly diverse set of vocab (including people discussing birthday parties, however it is a translation from the English transcripts, and it contains many different dialects of translators so the spelling is not systematic.

It was aligned and cleaned by the NRC. [Download Version 2.0 (gzipped 21 MB)](http://www.inuktitutcomputing.ca/NunavutHansard/data/SentenceAligned.v2.txt.zip)
More info:
http://www.inuktitutcomputing.ca/NunavutHansard/en/index.html


# Inuktitut Magazine #

This is a magazine which has over 100 issues published since the 1950s. Many of the issues are available for download on the [ITK website](http://www.itk.ca/inuktitut-magazine)

We downloaded the issues that were available to see if it is possible to extract reasonable text from the pdfs.

## Vocabulary Size ##

Unknown so far, still compiling.

### Words with known roots ###

We have a list of roots from [inuktitutcomputing.com](http://www.inuktitutcomputing.ca/DataBase/en/index.html) which we turned into Jape rules to find known roots. At the moment it looks like ~30% of the vocabulary in Inuktitut Magazine are based off of known roots from Spaulding's  and other's dictionaries.

## Orthography ##

The syllabics are in Nunacom encoding which is very very problematic. We wrote a transcoder to turn it into unicode (using http://www.inuktitutcomputing.ca/Transcoder/index.php?lang=en) .

We have <&>/ɬ/ {lateral, fricative} in the [inuktitutcomputing.com](http://www.inuktitutcomputing.ca/DataBase/en/index.html)  but non in the romanized Inuktitut of Inuktitut Magazine. We need to look into what this segment is in the Inuktitut Magazine's version of romanized Inuktitut. At the moment we are ignoring roots which contain <&>.