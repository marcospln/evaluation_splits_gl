# Splits to evaluate NLP models for Galician
This repository includes some splits used to evaluate NLP models for Galician.

## SLI_POS
This folder contains custom splits of the [SLI_POS dataset](https://github.com/xavier-gz/SLI_Galician_Corpora). The SLI_POS dataset is based on the [CTG Galician Technical Corpus](http://ilg.usc.gal/ctg/) tagged with Part-of-Speech (POS) tags.

This version simply removes the (duplicate) dev set, and splits the train into train+dev, keeping the original test data intact.

## SLI_NERC
This folder contains custom splits of the [SLI_NERC dataset](https://github.com/xavier-gz/SLI_Galician_Corpora), annotated with _enamex_ entities (LOC, ORG, PER, MISC).

This version simply adds a dev test by splitting the train data into train+dev, and also keeps the test set intact.
