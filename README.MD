
2019/01/31

1.Predicting non-small cell lung cancer prognosis by fully automated microscopic pathology image features https://www.nature.com/articles/ncomms12474

This paper used CellProfile (https://github.com/CellProfiler/CellProfiler/wiki/CellProfiler-as-a-Python-package) to generate ~9000 features for cell images and used that for modeling. 

Quick look in CellProfile shows it can extract some cell image info like nuclei, plasma ratio etc, but the training data is limited, and have high knowledge gap to use. Has python package. If python package is easy to use, no harm to combine these features with DNN features. 

2. A cloud-compatible bioinformatics pipeline for ultrarapid pathogen identification from next-generation sequencing of clinical samples 
https://cs.stanford.edu/~matei/papers/2014/genome_research_surpi.pdf

Source:

Standford DAWN: https://dawn.cs.stanford.edu/

Snorkel: https://github.com/HazyResearch/snorkel
