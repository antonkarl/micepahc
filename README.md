# MIcePaHC

The Machine-Parsed IcePaHC, MIcePaHC is a treebank that builds on the IcePaHC project, the Icelandic Parsed Historical Corpus. The idea behind MIcePaHC is to use the machine-parsing setup of the Language and Technology Lab at the University of Iceland to create a treebank of historical Icelandic that contains texts that are not included in IcePaHC (which is a manually corrected treebank). Our parsing setup draws on training a parser on IcePaHC. Because the manually annotated training data include a wide range of input from different stages and genres of historical Icelandic, we hope that the system will perform well on diverse texts to be included in MIcePaHC.

# Version 0.1

The current release is version 0.1. It is the first release of the corpus and it is a little rough around the edges but it is nevertheless quite usable for various types of studies. It contains the full text of all the Icelandic sagas as published by online publisher Netútgáfan. Because it is an early 0.1 release, users should expect things to change in future versions.

# Format

The treebank contains the raw text used as input for the parser, machine-tokenized into (roughly) main clauses as in the IcePaHC corpus (txt directory), as well as full phrase structure parses of everything (psd directory). The psd files are in the same labeled bracketing format as many other similar treebanks, including IcePaHC and the Penn Treebank. They can be queried using tGrep or CorpusSearch.

# Contact

Contact Anton Karl Ingason, antoni@hi.is, for further information.