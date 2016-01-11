Language models
===============

This folder contains free language models for the Block World Corpus estimated with IRSTLM.

The models with SM in the name use markers for start and end of sentence (<s> and </s>).

IRSTLM was used with  parameters to estimate a 3-gram LM, removing singletons, smoothing with improved Kneser-Ney:

Example:

~/irstlm/bin/build-lm.sh -i  ~/block_world_corpus/blockworld.full.SM.en  -t ./tmp  -p -s improved-kneser-ney -o ~/block_world_corpus/lm/blockworld.full.SM.lm.en



Enjoy!

Per Tunedal
