# jor-multimod
Corpus-based lexical statistics of Jordanian Arabic

## About
This contains lexical statistics from a subset of a multimodal Jordanian corpus. 

This release contains:
- token ngram lists. Created with NLTK (Loper & Bird 2002)
- lemma+part of speech (POS) ngram lists. Created with MADAMIRA (Pasha et al. 2014) and NLTK (Loper & Bird 2002)
- root ngram lists. Created with a manually Jordanian-augmented version of Khoja (Khoja & Garside 1999) and NLTK (Loper & Bird 2002)
- stem:whole word transition probability: contains one value per multimorphemic word (see Lewis, Solomyak, and Marantz 2011)
This release is sourced from the following:
- blogs
- opinion columns
- transcription of YouTube videos
- novels/short stories
Complete information about creation of this corpus and detailed information about its sources can be found by consulting the citation below (Wray 2016).

## Format

Ngram lists are formatted into comma-separated columns as follows:

> ngram , frequency , /newline

Stem:whole word transition probability (TP) is formatted as follows:

> word , frequency of stem , frequency of whole word , TP , /newline

## Citation
If you use these resources, please cite: 

> Wray, S. 2016. Decomposability and the effects of morpheme frequency in lexical access. Unpublished Doctoral Dissertation. University of Arizona. Tucson, Arizona, USA.
