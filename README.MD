Classical:

keras: https://www.pyimagesearch.com/2017/03/20/imagenet-vggnet-resnet-inception-xception-keras/

tensorflow: https://www.tensorflow.org/hub/tutorials/image_retraining

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

2019/02/18

1. genetic SNP + image for disease classification. using SVM+: http://lxduan.info/papers/DuanMICCAI2014.pdf

2019/02/19

2. Oxford Nanopore sequencing, hybrid error correction, and de novo assembly of a eukaryotic genome https://genome.cshlp.org/content/25/11/1750.full.pdf+html

Note: use 2nd generation seq to correct the error of 3rd generation, then do de novo assembly. platform: Oxford Nanopore
similar paper for PacBio: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3464235/pdf/pone.0046679.pdf

2019/02/20

1. good overview of sequencing data analysis: http://www.im.cas.cn/kytjpt/jsjl/201412/P020141208537486451133.pdf ; for NGS analysis: https://www.zhihu.com/question/23492496?rf=26011991

2. comparison of nanopore and pacificBio: http://www.sohu.com/a/227171939_464200

3. Ciron: DNN for Nanopore basecalling (CNN+RNN): from eletronic signal to ATGC: https://academic.oup.com/gigascience/article/7/5/giy037/4966989

4. DeepBinner: DNN for Nanopore multiplex barcode classification (CNN, softmax): from eletronic signal to barcode classification: https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1006583








