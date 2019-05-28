Classical:

ResNet: https://arxiv.org/pdf/1512.03385.pdf

MaskRCNN: https://arxiv.org/pdf/1703.06870.pdf

Unet: https://arxiv.org/abs/1505.04597

standford medical image DNN: https://aimi.stanford.edu/projects/deep-learning-computer-vision

standford ML group: https://stanfordmlgroup.github.io/

GAN model pool: https://github.com/tangzhenyu/Generative_Model_Zoo


Tutorial:

keras: https://www.pyimagesearch.com/2017/03/20/imagenet-vggnet-resnet-inception-xception-keras/

tensorflow: https://www.tensorflow.org/hub/tutorials/image_retraining

pytorch: https://github.com/skyuuka/pytorch-tutorial

medical AI database:

https://github.com/beamandrew/medical-data

https://stanfordmlgroup.github.io/competitions/mura/

https://grand-challenge.org/challenges/

***************************************************************
********** 2019/05

2019/05/28

Deep Learning under Privileged Information Using Heteroscedastic Dropout:https://arxiv.org/pdf/1805.11614.pdf

SPIGAN: PRIVILEGED ADVERSARIAL LEARNING FROM SIMULATION: https://arxiv.org/pdf/1810.03756.pdf

Recognizing RGB Images by Learning from RGB-D Data: http://www.vision.ee.ethz.ch/~liwenw/papers/Chen_CVPR2014.pdf

A DOMAIN-ADAPTIVE TWO-STREAM U-NET FOR ELECTRON MICROSCOPY IMAGE SEGMENTATION: https://infoscience.epfl.ch/record/263574/files/Bermudez18.pdf

Deep Learning under Privileged Information Using Heteroscedastic Dropout: https://arxiv.org/pdf/1805.11614.pdf


2019/05/22
Impossibility Theorems for Domain Adaptation: http://proceedings.mlr.press/v9/david10a/david10a.pdf

Domain Adaptation from Multiple Sources: A Domain-Dependent Regularization Approach: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6135800

Note: traditional method, for kernal method like SVM. 

AutoDIAL: Automatic DomaIn Alignment Layers: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8237804

Note: DNN based, but not GAN, add DA layer (BN modified)

2019/05/21
Maximum Mean Discrepancy: http://alex.smola.org/teaching/iconip2006/iconip_3.pdf

Deep Domain Adaptation by Geodesic Distance Minimization: https://arxiv.org/pdf/1707.09842.pdf

UNSUPERVISED DOMAIN ADAPTATION FOR DISTANCE METRIC LEARNING: https://openreview.net/pdf?id=BklhAj09K7


***************************************************************
********** 2019/04


2019/04/25
AutoAugment - Learning Augmentation Policies from Data: https://github.com/DeepVoltaire/AutoAugment
Self-Ensembling Attention Networks: Addressing Domain Shift for Semantic Segmentation: https://github.com/YonghaoXu/SEANet

2019/04/24:
Unsupervised Domain Adaptation for Automatic Estimation of Cardiothoracic Ratio: https://arxiv.org/pdf/1807.03434.pdf

Adversarial Domain Adaptation for Classification of Prostate Histopathology Whole-Slide Images: https://arxiv.org/pdf/1806.01357.pdf

2019/04/22:

domain adaptation review blog: https://artix41.github.io/static/domain-adaptation-in-2017/index.html#fn2

transfer learning and domain adaptation paper pool: https://github.com/artix41/awesome-transfer-learning#adversarial-methods

ImageNet-trained CNNs are biased towards texture; increasing shape bias improves accuracy and robustness: https://openreview.net/forum?id=Bygh9j09KX

few-shot learning review: https://arxiv.org/pdf/1904.05046.pdf

Low-Shot Learning from Imaginary Data: https://arxiv.org/pdf/1801.05401.pdf

drug study:

1. Synergistic Drug Combination Prediction by Integrating Multi-omics Data in Deep Learning Models: https://arxiv.org/pdf/1811.07054.pdf

2. Low Data Drug Discovery with One-Shot Learning: https://pubs.acs.org/doi/pdf/10.1021/acscentsci.6b00367

3. Explainable machine learning prediction of synergistic drug combinations for precision cancer medicine: https://www.biorxiv.org/content/biorxiv/early/2018/05/27/331769.full.pdf

2019/04/17:

nanoSV: https://www.nature.com/articles/s41467-017-01343-4.pdf

2019/04/15

split reads in samtools: https://www.biostars.org/p/146178/

sam/bam file tag info: http://www.biotrainee.com/thread-1598-1-1.html

2019/04/10

List of object detection framework(fastRCNN, fasterRCNN etc): https://zhuanlan.zhihu.com/p/44599606

CE-Net: Context Encoder Network for 2D Medical Image Segmentation：https://arxiv.org/pdf/1903.02740.pdf

MASK-RCNN AND U-NET ENSEMBLED FOR NUCLEI SEGMENTATION: https://arxiv.org/pdf/1901.10170.pdf

Deeplab v3+: https://github.com/tensorflow/models/tree/master/research/deeplab

2019/04/09

review of unsupervised and semi-supervisded methods: https://arxiv.org/pdf/1903.11260.pdf

2019/04/08

L1000 drug+cell line expression database: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5990023/pdf/nihms917441.pdf

AVT from guojun: https://arxiv.org/pdf/1903.10863.pdf

Predicting drug response of tumors from integrated genomic profiles by deep neural networks: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6357352/pdf/12920_2018_Article_460.pdf

Cancer Drug Response Profle scan (CDRscan): A Deep Learning Model That Predicts Drug Efectiveness from Cancer Genomic Signature: https://www.nature.com/articles/s41598-018-27214-6.pdf

Highly-accurate long-read sequencing improves variant detection and assembly of a human genome: https://www.biorxiv.org/content/biorxiv/early/2019/01/13/519025.full.pdf

2019/04/04

SV reading: https://www.jianshu.com/p/4c8e109f0e6a

Making the difference: integrating structural variation detection tools: https://academic.oup.com/bib/article/16/5/852/217239

***************************************************************
********** before 2019/04
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

3. Chiron: DNN for Nanopore basecalling (CNN+RNN): from eletronic signal to ATGC: https://academic.oup.com/gigascience/article/7/5/giy037/4966989

4. DeepBinner: DNN for Nanopore multiplex barcode classification (CNN, softmax): from eletronic signal to barcode classification: https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1006583

Note: did data augmentation, added gausian noise in training data. 

5. WaveNano: use WaveNet to classify k-mer label and move/stay label, but not the final ATGC sequence: https://link.springer.com/content/pdf/10.1007%2Fs40484-018-0155-4.pdf

2019/02/21

1. machine learning/DNN for SV, currently only has on 2nd generation seq, the idea is only to combine the results and build a model to remove false positive from other SV call softwares:

1) CNNdel: https://www.hindawi.com/journals/bmri/2017/6375059/

2) RF based: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3427657/

2. Sniffles, software for 3rd generation SV call: https://www.biorxiv.org/content/biorxiv/early/2017/07/28/169557.full.pdf

2019/02/22

1. panoptic segmentation (semantic segmentation + instance segmentation) review: https://www.jiqizhixin.com/articles/2018-12-24-12

2019/02/25

1.Chest Xray data and model from standford: https://arxiv.org/pdf/1901.07031.pdf

2019/02/26

1. Clairvoyante: a multi-task convolutional deep neural network for variant calling in Single Molecule
Sequencing : https://www.biorxiv.org/content/biorxiv/early/2018/04/28/310458.full.pdf

note: multi-task CNN for detecting SNP/Indel in 3rd generation seq

2019/02/28

1. DeepVariant: https://www.biorxiv.org/content/10.1101/092890v6


2019/03/05

1. Medical image data augmentation: https://arxiv.org/pdf/1902.09383.pdf space + appareance transform model for one-shot learning

2. Unsupervised learning for learning encoders: https://arxiv.org/pdf/1901.04596.pdf

3. good architecture for image classification and segmentation: https://arxiv.org/pdf/1411.5752.pdf

2019/03/13

1. DNN for somatic mutation detection: https://www.biorxiv.org/content/biorxiv/early/2018/09/04/393801.full.pdf

note: learn how it constructs the tensor from sequencing data.



