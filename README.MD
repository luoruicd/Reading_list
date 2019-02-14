Classical:

ResNet: https://arxiv.org/pdf/1512.03385.pdf

2019/01/31

1. Predicting non-small cell lung cancer prognosis by fully automated microscopic pathology image features https://www.nature.com/articles/ncomms12474

This paper used CellProfile (https://github.com/CellProfiler/CellProfiler/wiki/CellProfiler-as-a-Python-package) to generate ~9000 features for cell images and used that for modeling. 

Quick look in CellProfile shows it can extract some cell image info like nuclei, plasma ratio etc, but the training data is limited, and have high knowledge gap to use. Has python package. If python package is easy to use, no harm to combine these features with DNN features. 

2. A cloud-compatible bioinformatics pipeline for ultrarapid pathogen identification from next-generation sequencing of clinical samples 
https://cs.stanford.edu/~matei/papers/2014/genome_research_surpi.pdf

3. Hybrid deep supervision: multi-task for both classification and segementation on medical imaging: https://arxiv.org/pdf/1808.10646.pdf

related previous work - deep supervision: https://arxiv.org/pdf/1505.02496.pdf

4. Source:

Standford DAWN: https://dawn.cs.stanford.edu/

Snorkel: https://github.com/HazyResearch/snorkel

AI blog: https://zhuanlan.zhihu.com/p/34357771

2019/02/13

1. image classification transfer learning, imagenet feature +  original
images, gradient features, and distanced transform features for ultrasound image classification: https://arxiv.org/ftp/arxiv/papers/1801/1801.00224.pdf

Note: interesting ideas to make 2D ultrasound image to RGB channels

